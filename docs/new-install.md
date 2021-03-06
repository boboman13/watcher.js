# Installing from scratch

> This documentation article outlines the entire process of setting up watcher.js on *one server*. Documentation for setting up multiple daemons with one frontend can be found [here](./creating-external-daemon.md).

This entire documentation assumes you have the following installed:
* [NodeJS](http://nodejs.org/)
* [NPM](https://www.npmjs.org/)
* CoffeeScript & Gulp: `npm install -g coffee-script gulp`

### Clone repository
```bash
$ git clone https://github.com/brendanashworth/watcher
$ cd watcher
```

### Resolve dependencies
```bash
$ npm install
```

### Compile and start frontend (+daemon)
```bash
$ gulp
$ npm start
```

### Done!
The application is running on **\*:8080**. Just go there in your web browser to see it!

The basic installation is now completed. This installation does not require authentication and is only setup on one server. View [this tutorial](./creating-external-daemon.md) to learn how to install another daemon.
