# Simple Angular2 Application with JWT Authentication

This repository contains a simple Angular2 Application that authenticates users with json web tokens. 
This project was made with help of [this tutorial](https://medium.com/@blacksonic86/authentication-in-angular-2-958052c64492#.geh2xuy70)
The list of capabilities of the application:
* Creates Users
* Displays Tasks Users Currently Have
* Taks Description Page

**In This Documentation**

1. [Overview](#overview)
2. [File Structure](#file-structure)
3. [Options & Settings](#options-and-settings)
4. [Continuous Integration](#continuous-integration)
5. [License](#license)

## Overview

### Dependencies
Make sure these are installed first.

* [Node.js](http://nodejs.org)
* [Gulp](http://gulpjs.com) `sudo npm install -g gulp`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files.
3. When it's done installing, run one of the task runners to get going:
	* `gulp` manually compiles files and runs unit tests.
	* `gulp watch` automatically compiles files, runs unit tests, and applies changes using [LiveReload](http://livereload.com/).
	* `gulp test` compiles files and runs unit tests.

## File Structure

Add your files to the appropriate `src` subdirectories. Gulp will process and and compile them into `dist`.

* Content in subdirectories under the `js` folder will be concatenated. Files directly under `js` will compile individually.
```
kickass-automation-script/
|—— dist/
|__ scripts/
|   |__ init.js
|   |__ parameters.js
|—— src/
|   |—— js/
|   |__ index.html/
|—— .travis.yml
|—— gulfile.js
|—— package.json
|—— README.md
```

## Options and Settingsbo

### Updating Project Details
Open up `package.json` to change the name, version, URL and other data about the project.

## Continuous Integration

### Travis CI

[TODO: Add Travis Settings]

## License

[TODO: Add License]
