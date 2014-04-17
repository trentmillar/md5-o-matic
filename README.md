md5-o-matic
===========

Simple & fast MD5 hashing for Node.js that requires no other module dependencies since it is pure javascript.

## Installation

	npm install md5-o-matic
	
## Usage
	
	var md5omatic = require('md5omatic');
	
	var hash;
	hash = md5omatic('the quick brown fox jumps over the lazy dog');
	console.log(hash);
	
## Tests

	mocha test/*.js

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release