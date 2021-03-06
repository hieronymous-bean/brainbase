<img src="./.github/brainbase.png" alt="Brainbase" width="100%" />

[![Development Status](https://img.shields.io/static/v1?label=status&message=Active&nbsp;Development&color=purple&style=flat-square&logo=open-source-initiative&logoColor=ffffff)](#) [![Version](https://img.shields.io/github/v/release/hieronymous-bean/brainbase?include_prereleases&style=flat-square)](#) [![Issues](https://img.shields.io/github/issues-raw/hieronymous-bean/brainbase?style=flat-square)](#) [![License](https://img.shields.io/github/license/hieronymous-bean/brainbase?style=flat-square)](#)


[![built with gulp](https://img.shields.io/badge/gulp-builds_this_project-eb4a4b.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAAYAAAAOCAMAAAA7QZ0XAAAABlBMVEUAAAD%2F%2F%2F%2Bl2Z%2FdAAAAAXRSTlMAQObYZgAAABdJREFUeAFjAAFGRjSSEQzwUgwQkjAFAAtaAD0Ls2nMAAAAAElFTkSuQmCC&style=flat-square)](http://gulpjs.com/)


:alembic: Full component and module toolkit for starting HTML-based projects. 

## Introduction
TBD

## Table of Contents
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Features](#features)
- [Updates](#updates)
- [Contributing](#contributing)
- [Credits](#credits)

## System Requirements
- Node.js ~14.15.0
- NPM ~6.14.8

Brainbase uses a core set of packages for its functionality:

*Focus*                             |  *Tool(s)*
------------------------------------|------------------------------------------------------------------------------------
Engine                              | Node.js
Primary Functions                   | Javascript
Build and Deployment Automation     | Gulp
Front-End                           | Bootstrap
Styling                             | SASS

## :inbox_tray: Installation

To get started, run:

```
npm run setup
```

This will install all required modules, run Gulp task automation, and compile application components. 

```bash
├──.github
├── dist
├── docs
|   ├── documentation.html
├── src /
|   ├── assets /
|   |   ├── data
|   |   ├── fonts
|   |   ├── html
|   |   ├── images
|   |   ├── js
|   |   ├── scss
|   |   ├── vendors
|   ├── index.html
.gitignore
 gulpfile.js
 LICENSE
 package.json
 README.md
```