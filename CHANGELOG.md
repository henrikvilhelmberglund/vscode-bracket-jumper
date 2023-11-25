# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## 0.0.0 (2023-11-25)


### Features

* add .vscode-test (not used yet) ([e1c313a](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/e1c313a09e9fa4778ebd8473c092c6b6939acf0c))
* add alwaysstrict ([671d26e](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/671d26edd907ee8ce5fa351c447bac80798df403))
* add commit-and-tag-version ([fc8e0ce](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/fc8e0ce2274b919654a415267bef0f7c1a22ff99))
* add dist to .gitignore ([7952a60](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/7952a6092c3be1f906ced7885d61e8a6eb16fca1))
* add LICENSE to stop annoying prompt when running script ([ef79f75](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/ef79f751cf6d12bfe8ad19b8ef7a95b3f6134595))
* export functions, remove offset when jumping ([e63d016](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/e63d0165adb1f9d275bff6b9d87deca683bcf377))
* install packages, prettier formatting ([d4bf9a5](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/d4bf9a5e9fdae71216238e1440cb1182e689fce7))
* shift cursor right when a left bracket is found ([761e367](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/761e36735956e3333bf0ca1911d2cbfa56c81ce8))
* update tasks and README ([18b72ca](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/18b72cac40dab31c170ffca061775d00a36d7e95))
* update/remove packages ([ca6f04d](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/ca6f04d6f3d7c25888df36f322607e0eb87e4f2c))


### Bug Fixes

* remove use strict ([3bd4c5e](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/3bd4c5e9de04cce2cd5458153606d8595972943f))
* substring has start and end instead of substr's start and length ([6929570](https://github.com/henrikvilhelmberglund/vscode-bracket-jumper/commit/69295706fbe7d990a75792a220e0dd78d8a35907))

## [1.1.8] - 8/30/2017
- Fix homepage and issues link

## [1.1.7] - 8/29/2017
- Update CHANGELOG

## [1.1.6] - 8/29/2017
- Fix bug with crashing command when jumping left from first position in a file

## [1.1.5] - 4/8/2017
### Fixed
- selectAscend commands were not registering, mistyped

## [1.1.3] - 3/27/2017
### Changed
- README

## [1.1.0] - 3/26/2017
### Added
- Configure what is considered a bracket

## [1.0.0] - 3/26/2017
### Added
- Simple jumping to nearest bracket
- Default keybindings

### Changed
- Previous functionality renamed to "ascending", commands changed
- Default keybindings

### Fixed
- Bug that caused doing any rightward movement to infinite loop in CRLF files (see https://github.com/Microsoft/vscode/issues/23247)

## [0.0.1] - 3/24/2017
### Added
- Jump and select text to nearest enclosing right or left bracket
- Default keybindings
