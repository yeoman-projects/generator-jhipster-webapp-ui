# generator-jhipster-webapp-ui
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> JHipster module, advanced ui screens for the project being generated by jhipster

# Introduction

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application.

I wrote a yeoman module on top of this jhipster project to create some customizable UI and REST API based on templates. My module creates commonly used standard UI components such as accordion, panel grids, matrix, add buttons, list group - to name a few.  It also creates REST API, APIs for navigations to parent screen, Service methods in Angular Factories and a new customised UI screen. Since it uses template based approach, more and more components and complex REST API can be added as we go. 

The creator needs to specify the settings in a JSON file about which components needs to be used and how the data should be accessed by that components. e.g. specify that i want to use an Accordion and the data should come from Study entity.   or specify that i want to create a new REST API that will get all the Plates in a given study.

# Prerequisites

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have JHipster and its related tools already installed:

- [Installing JHipster](https://jhipster.github.io/installation.html)

# Installation

To install this module:

```bash
npm install -g generator-jhipster-webapp-ui
```

To update this module:
```bash
npm update -g generator-jhipster-webapp-ui
```

# Usage

# License

Apache-2.0 © [Sanket Sangwikar]

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-webapp-ui.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-webapp-ui
[travis-image]: https://travis-ci.org/sanketsw/generator-jhipster-webapp-ui.svg?branch=master
[travis-url]: https://travis-ci.org/sanketsw/generator-jhipster-webapp-ui
[daviddm-image]: https://david-dm.org/sanketsw/generator-jhipster-webapp-ui.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/sanketsw/generator-jhipster-module
