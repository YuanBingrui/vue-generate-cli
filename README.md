# vue-generate-cli

A cli tool for auto-generating vue template component.

### Installation

Prerequisites: [Node.js](https://nodejs.org/en/) (>=4.x, 6.x preferred), npm version 3+ and [Git](https://git-scm.com/).

``` bash
$ npm install -g vue-generate-cli
or
$ yarn global add vue-generate-cli
```

### Usage

``` bash
// default generate a new file in './src' directory or sub-directory
// add -R [rootDir] option to generate new file in custome root directory
$ vue-g g <filename> || vue-g g <filename> -R doc
or
// default generate a new file in components directory
// add -r option to generate new file in current root directory
$ vue-g g <filename> || vue-g g <filename> -r
or
// generate a new file in custom directory
$ vue-g g <dirname> <filename>
or
// generate more new files in custom directory
$ vue-g g <dirname> <filename01> <filename02> <filename03> <filename(2N+1)>
or
// generate more new files in custom path
$ vue-g g path <filename01> <filename02> <filename03> <filename(2N+1)>
or
// generate a new files in custom path with -P and -C option
$ vue-g g path <filename01> <filename02> <filename03> -P -C
// -P filename is PascalCase format
// -C generate CSS file
```

Example:

``` bash
$ vue-g g my-component
or
$ vue-g g libs my-component
or
$ vue-g g libs my-component01 my-component02 my-component03
or
$ vue-g g ./components/libs my-component01 my-component02 my-component03
```
