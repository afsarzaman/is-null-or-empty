# is-null-or-empty

A Node.js package that checks whether a given string is null or empty. A basic package for an npm publish tutorial.

## Usage

First, install the package using npm:

    npm install is-null-or-empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('is-null-or-empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License