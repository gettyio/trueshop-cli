# Trueshop CLI 

[![Greenkeeper badge](https://badges.greenkeeper.io/feathersjs/feathers-cli.svg)](https://greenkeeper.io/)

> The command line interface for Trueshop applications based on the awesome feathersjs-cli

## Installation

```bash
npm install -g trueshop-cli
```

## Usage

```
$ mkdir myproject

$ cd myproject

$ trueshop help

  Usage: feathers generate [type]


  Commands:

    generate [type]  Run a generator. Type can be
      • app - Create a new Trueshop ecommerce in the current folder
      • authentication - Set up authentication for the current application
      • connection - Initialize a new database connection
      • hook - Create a new hook
      • middleware - Create an Express middleware
      • service - Generate a new service
      • plugin - Create a new Feathers plugin

    *

  Options:

    -h, --help     output usage information
    -V, --version  output the version number

$ feathers generate app

$ npm start
```

## About


## License

Copyright (c) 2017

Licensed under the [MIT license](LICENSE).
