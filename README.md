# Yeoman generator producing ES6 node modules

A node module generator for yeoman. Opinionated in the sense that it creates

 - ES6 node modules, no transpiling via babel
 - Uses [yarn](https://yarnpkg.com/) for dependency management
 - Uses [Lab](https://github.com/hapijs/lab) for testing
 - eslint with airbnb rules ( with some minor tweaks )
 - installs a [pre-commit hook](https://www.npmjs.com/package/pre-commit) to ensure lint and tests are executed before a commit

## Install it

Install the genrator with npm:
```
$ npm install -g yo generator-node-es6
```


## Use it

Usage of the generator is via [yo](http://yeoman.io/)
```
$ yo node-es6
```

Answer the questions and celebrate that a new node module is generated for you.

## Contribute

 - Clone the repository
 - Add your awesome feature
 - make sure to add tests
 - use `npm link` to use your new version locally
 - Create a pull request

# TODO

 - use cache to save answers
 - submodule generator for tests
 - submodule generator for hapi-plugin
 - submodule generator for hapi-plugin test
 - submodule generator for hapi api
 - perhaps support for both Lab and Mocha tests?

