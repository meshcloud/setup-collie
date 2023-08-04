# setup-collie

The `meshcloud/setup-collie` action is a composite action that sets up [collie cli](https://github.com/meshcloud/collie-cli) in your GitHub Actions workflow.

# Usage

This action only supports `ubuntu-latest` GitHub Actions runners.

The default configuration installs the latest version of collie cli.

```
steps:
- uses: meshcloud/setup-collie@v1
```

# Inputs
The action supports the following inputs:
- `collie-version` (optional): Fix a specific version of collie cli. Example `v1.3.0`. If no version is given, it will default to latest.

# Outputs
This action does not configure any outputs.


<p align="center"><b>Made with ❤️ by <a href="https://meshcloud.io/?ref=gh-collie">meshcloud</a></b></p>
