[![Build Status](https://travis-ci.org/raghavbk/mdb-javascript.svg?branch=master)](https://travis-ci.org/raghavbk/mdb-javascript) [![star this repo](http://githubbadges.com/star.svg?user=raghavbk&repo=mdb-javascript&style=flat)](https://github.com/raghavbk/mdb-javascript) [![fork this repo](http://githubbadges.com/fork.svg?user=raghavbk&repo=mdb-javascript&style=flat)](https://github.com/raghavbk/mdb-javascript/fork) [![Badge](https://img.shields.io/github/license/raghavbk/mdb-javascript.svg)](https://img.shields.io/github/license/raghavbk/mdb-javascript.svg)

# Overview

This boilerplate is a set of utilities and plugins for NodeJs to tune and streamline your MDBootstrap (free version) application.

# Installation

First time installation process for Free users:

```bash
npm install
```
##### Start development server
```bash
npm start
```
Runs the project with webpack-dev-server, opens in a new tab on your default browser. Live-reload enabled.

##### Building your project
```bash
npm run build
```
Builds the project to **/dist/**

# Updating

When you want to update the project, it's dependencies and packages, I recommend installing npm-check-updates

```bash
npm i npm-check-updates -g
```

Once installed, run the following commands inside the repository:

```bash
ncu -u
```

If packages are updated, run:

```bash
npm install
```
