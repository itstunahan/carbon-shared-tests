# Project Overview

A test suite of re-usable UI unit tests aligned to the [Carbon Design System](https://carbondesignsystem.com/). Tests focus on user interactions to verify consistent behavior across implementations. The suite is UI and testing framework agnostic using the [Exported Tests](https://github.com/IBM/exported-tests#project-overview) architecture. This project is a collaboration between teams creating and using Carbon components.

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

_(recommended)_ Use [NVM](https://github.com/nvm-sh/nvm#node-version-manager---) for managing versions of Node when working on multiple projects.

### Installing

We develop using a [forking workflow](https://guides.github.com/activities/forking/) for all users looking to do any work on Carbon Shared Tests.

Now that you you have Carbon Shared Tests set up locally, navigate to the project using the `cd` command in the terminal and install dependencies using this command:

```bash
yarn
```

### Deployment

We distribute Carbon Shared Tests in multiple formats for increased support of various testing frameworks. Import the desired format from the following locations:

* ES 2015 (ES6) Modules- `dist/es/index.js`
* Common JS (ES5) - `dist/cjs/index.js`
* Browser compatible (UMD) - `dist/umd/index.js`

To run the transpiler and generate the previous files use this command:

```bash
yarn build
```

## Contribution Guide

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
