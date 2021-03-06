# ZeppelinOS Command Line Interface
[![NPM Package](https://img.shields.io/npm/v/zos.svg?style=flat-square)](https://www.npmjs.org/package/zos)
[![Build Status](https://travis-ci.org/zeppelinos/zos-cli.svg?branch=master)](https://travis-ci.org/zeppelinos/zos-cli)

This package provides a unified command line interface to [ZeppelinOS](https://zeppelinos.org/).

ZeppelinOS is a platform to develop, manage and operate smart contract applications in Ethereum. It can be used to create smart contract systems that can be fixed and improved over time, enabling developers to opt-in to mutability for their deployed code through [upgradeability patterns](https://blog.zeppelinos.org/proxy-patterns/). `zos` also provides an interface to connect your application code to already deployed standard libraries.

If you're looking for a lower-level development experience, see [`zos-lib`](https://github.com/zeppelinos/zos-lib).

## Table of Contents

- [Getting Started](#getting-started)
  - [Install](#install)
  - [Basic usage](#basic-usage)
- [Examples](#examples)
- [Links](#links)
- [Security](#security)
- [License](#license)

## Getting Started

### Install

To install `zos` simply run:
```sh
npm install --global zos
```

### Basic usage

#### Before you begin
```sh
mkdir myproject && cd myproject
npm init
```

#### Setup your project
Initialize your project with ZeppelinOS. The next command will create a new `zos.json` file:

```sh
zos init <name> [version]
```
Where `<name>` is your project's name, and `[version]` an optional initial version name. For example:
```sh
zos init my-project 0.1.0
```


## Guides

- [Installation and setup](https://docs.zeppelinos.org/docs/setup.html)
- [Building an upgradeable application](https://docs.zeppelinos.org/docs/building.html)
- [Using the stdlib in your app](https://docs.zeppelinos.org/docs/using.html)
- [Developing a new standard library](https://docs.zeppelinos.org/docs/developing.html)
- [Testing upgradeable applications](https://docs.zeppelinos.org/docs/testing.html)
- [Extend provided standard library code in your own contracts](https://github.com/zeppelinos/labs/tree/master/extensibility-study#extensibility-study) (experimental)
- [Migrate your non-upgradeable legacy ERC20 token into an upgradeable version with a managed approach](https://github.com/zeppelinos/labs/tree/master/migrating_legacy_token_managed#migrating-legacy-non-upgradeable-token-to-upgradeability-with-managed-strategy) (experimental)
- [Migrate your non-upgradeable legacy ERC20 token into an upgradeable version with an opt-in approach](https://github.com/zeppelinos/labs/tree/master/migrating_legacy_token_opt_in#migrating-legacy-non-upgradeable-token-to-upgradeability-with-opt-in-strategy) (experimental)


## Links

### Documentation
- [ZeppelinOS](http://zeppelinos.org)
- [Documentation site](https://docs.zeppelinos.org)
- [ZeppelinOS Blog](https://blog.zeppelinos.org)

### Code
- [ZeppelinOS CLI (this repository)](https://github.com/zeppelinos/zos-cli)
- [ZeppelinOS library (`zos-lib`)](https://github.com/zeppelinos/zos-lib)

## Security

If you find a security issue, please contact us at security@zeppelinos.org. We give rewards for reported issues, according to impact and severity.

## License

Code released under the [MIT License](LICENSE)
