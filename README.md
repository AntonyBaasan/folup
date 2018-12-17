folup
=====

folder upload cli tool

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/folup.svg)](https://npmjs.org/package/folup)
[![CircleCI](https://circleci.com/gh/AntonyBaasan/folup/tree/master.svg?style=shield)](https://circleci.com/gh/AntonyBaasan/folup/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/AntonyBaasan/folup?branch=master&svg=true)](https://ci.appveyor.com/project/AntonyBaasan/folup/branch/master)
[![Codecov](https://codecov.io/gh/AntonyBaasan/folup/branch/master/graph/badge.svg)](https://codecov.io/gh/AntonyBaasan/folup)
[![Downloads/week](https://img.shields.io/npm/dw/folup.svg)](https://npmjs.org/package/folup)
[![License](https://img.shields.io/npm/l/folup.svg)](https://github.com/AntonyBaasan/folup/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g folup
$ folup COMMAND
running command...
$ folup (-v|--version|version)
folup/0.0.0 win32-x64 node-v11.4.0
$ folup --help [COMMAND]
USAGE
  $ folup COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`folup hello [FILE]`](#folup-hello-file)
* [`folup help [COMMAND]`](#folup-help-command)

## `folup hello [FILE]`

describe the command here

```
USAGE
  $ folup hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ folup hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/AntonyBaasan/folup/blob/v0.0.0/src\commands\hello.ts)_

## `folup help [COMMAND]`

display help for folup

```
USAGE
  $ folup help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src\commands\help.ts)_
<!-- commandsstop -->
