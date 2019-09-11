# Go RESTful

A real world production-grade RESTful proof-of-concept project.

## Objectives

- An optimized Go implementation follows clean architecture, provides mechanism to declare entities, use cases - - and external services (e.g. data access).

- An optimized Go implementation provides mechanism to exposes entities and use cases as RESTful web services.

- An optimized Go implementation of token-based authentication and authorization.

- An optimized Go implementation provides abstract mechanism to access relational databases.

- An optimized Go development environment with Git, Docker, Golang/dep, Golang debuggers (GDB/Delve) and editors (VSCode/GoLand).

- A scalable and highly available production deployment solution over AWS cloud using Terraform.

- An optimized staging environment replicating production environment for testing purposes.

- An optimized CI/CD solution with CircleCI and AWS.

- An optimized issues tracking mechanism with Github projects, issues and pull requests.

- Continual improvements.

## Issues Tracking

[![Issue Tracking](https://img.shields.io/static/v1?label=issue%20tracking&message=Github%20project&color=lightgrey)](https://github.com/the-evengers/go-restful/projects/1)
[![Open issues](https://img.shields.io/github/issues/the-evengers/go-restful)](https://github.com/the-evengers/go-restful/issues) [![Closed issues](https://img.shields.io/github/issues-closed/the-evengers/go-restful)](https://github.com/the-evengers/go-restful/issues?q=is%3Aissue+is%3Aclosed) [![Open PRs](https://img.shields.io/github/issues-pr/the-evengers/go-restful)](https://github.com/the-evengers/go-restful/pulls) [![Closed PRs](https://img.shields.io/github/issues-pr-closed/the-evengers/go-restful)](https://github.com/the-evengers/go-restful/pulls?q=is%3Apr+is%3Aclosed)

This project use Github project, issues and pull requests to manage and track issues. Refer to [this Github project](https://github.com/the-evengers/go-restful/projects/1) for further details.

## Development

### Requirements

Local development machines need to have following tools installed and working properly:

- [Docker](https:://www.docker.com) for running a full-time containerized development environment.

- [Visual Studio Code](https://code.visualstudio.com) with [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) for writing code with Intellisense, running and debugging code within containers.

Windows users need to additionally have an Unix-shell emulator to be able to run utility scripts ([Git Bash](https://gitforwindows.org) is recommended).

### Usage

#### Develop with Visual Studio Code

With all of above requirements fullfiled, developers can experience a full-time local-quality VSCode-powered containerized development environment by just opening the repository in VSCode container mode.

Go [here](docs/DEV-WITH-VSCODE.md) for further details.

#### Develop without Visual Studio Code

Without VSCode, developers will not be able to achieve a full-time local-quality VSCode-powered containerized development environment. However, if there's any reason that you can not or do not want to work with Visual Studio Code, you can still start a containerized development environment and start working on that or even build your own development solution on top of that.

Go [here](docs/DEV-WITHOUT-VSCODE.md) for further details.

### License

[![Apache License 2.0](https://img.shields.io/github/license/the-evengers/go-restful)](https://github.com/the-evengers/go-restful/blob/master/LICENSE) ![Copyright © The Evengers](https://img.shields.io/static/v1?label=copyright&message=The%20Evengers&color=lightgrey)

Copyright © The Evengers. All rights reserved.

This project is licensed under the [Apache License 2.0](https://github.com/the-evengers/go-restful/blob/master/LICENSE) and is available for free.
