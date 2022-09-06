# Azure Pipelines Task Codecoverage SDK

Codecoverage libraries for [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) tasks.

## Status

|   | Build & Test |
|---|:-----:|
|![Win-x64](res/win_med.png) **Windows**|[![Build & Test][win-build-badge]][build]| 
|![macOS](res/apple_med.png) **macOS**|[![Build & Test][macOS-build-badge]][build]| 
|![Linux-x64](res/ubuntu_med.png) **Linux**|[![Build & Test][linux-build-badge]][build]|

[win-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks-coverage-tools-ci?branchName=main&jobname=windows
[macOS-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks-coverage-tools-ci?branchName=main&jobname=macOS
[linux-build-badge]: https://dev.azure.com/mseng/PipelineTools/_apis/build/status/azure-pipelines-tasks-coverage-tools-ci?branchName=main&jobname=linux
[build]: https://dev.azure.com/mseng/PipelineTools/_build/latest?definitionId=

[![NPM version][npm-lib-image]][npm-lib-url]

[npm-lib-image]: https://img.shields.io/npm/v/azure-pipelines-tasks-codecoverage-tools.svg?style=flat
[npm-lib-url]: https://www.npmjs.com/package/azure-pipelines-tasks-codecoverage-tools

# Build

Once:  
```bash
$ npm install
```

Build:  
```bash
$ npm run build
```

The tool cache will be in the `_build` folder.  To clear the cache, build again.

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Security issues

Do you think there might be a security issue? Have you been phished or identified a security vulnerability? Please don't report it here - let us know by sending an email to secure@microsoft.com.