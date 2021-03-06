
<!-- TITLE/ -->

# QueryFilter

<!-- /TITLE -->


<!-- BADGES/ -->

[![Build Status](http://img.shields.io/travis-ci/keystonejs/queryfilter.png?branch=master)](http://travis-ci.org/keystonejs/queryfilter "Check this project's build status on TravisCI")
[![NPM version](http://badge.fury.io/js/queryfilter.png)](https://npmjs.org/package/queryfilter "View this project on NPM")
[![Dependency Status](https://david-dm.org/keystonejs/queryfilter.png?theme=shields.io)](https://david-dm.org/keystonejs/queryfilter)
[![Development Dependency Status](https://david-dm.org/keystonejs/queryfilter/dev-status.png?theme=shields.io)](https://david-dm.org/keystonejs/queryfilter#info=devDependencies)<br/>
[![Gittip donate button](http://img.shields.io/gittip/keystonejs.png)](https://www.gittip.com/keystonejs/ "Donate weekly to this project using Gittip")

<!-- /BADGES -->


<!-- DESCRIPTION/ -->

Create query filters, stringify them, humanize them

<!-- /DESCRIPTION -->


<!-- INSTALL/ -->

## Install

### [NPM](http://npmjs.org/)
- Use: `require('queryfilter')`
- Install: `npm install --save queryfilter`

### [Browserify](http://browserify.org/)
- Use: `require('queryfilter')`
- Install: `npm install --save queryfilter`
- CDN URL: `//wzrd.in/bundle/queryfilter@0.0.4`

### [Ender](http://ender.jit.su/)
- Use: `require('queryfilter')`
- Install: `ender add queryfilter`

<!-- /INSTALL -->


## Usage

``` javascript
var QueryFilter = require('queryfilter');
var queryFilter = new QueryFilter();

// whether or not we should invert this query
// boolean
queryFilter.inverse = false;

// whether or not we should exactly match the value
// boolean
queryFilter.exact = false;

// the human readable name of the field
// null/string
queryFilter.name = null;

// the key used to identify the field
// required, string
queryFilter.key = "some key";

// the data type of the field
// null/string
queryFilter.type = null;

// the operator used to compare the field with the value
// null/"bt"/"gt"/"lt"
queryFilter.operator = null;

// the value used on the field
// required, any type
queryFilter.value = "some value";

// Transformations
console.log(queryFilter.toString());
console.log(queryFilter.fromString());
console.log(queryFilter.toHumanString());
```

<!-- HISTORY/ -->

## History
[Discover the change history by heading on over to the `HISTORY.md` file.](https://github.com/keystonejs/queryfilter/blob/master/HISTORY.md#files)

<!-- /HISTORY -->


<!-- CONTRIBUTE/ -->

## Contribute

[Discover how you can contribute by heading on over to the `CONTRIBUTING.md` file.](https://github.com/keystonejs/queryfilter/blob/master/CONTRIBUTING.md#files)

<!-- /CONTRIBUTE -->


<!-- BACKERS/ -->

## Backers

### Maintainers

These amazing people are maintaining this project:

- Benjamin Lupton <b@lupton.cc> (https://github.com/balupton)
- Jed Watson <jed@thinkmill.com.au> (https://github.com/jedwatson)

### Sponsors

No sponsors yet! Will you be the first?

[![Gittip donate button](http://img.shields.io/gittip/keystonejs.png)](https://www.gittip.com/keystonejs/ "Donate weekly to this project using Gittip")

### Contributors

These amazing people have contributed code to this project:

- [JedWatson](https://github.com/JedWatson) — [view contributions](https://github.com/keystonejs/queryfilter/commits?author=JedWatson)

[Become a contributor!](https://github.com/keystonejs/queryfilter/blob/master/CONTRIBUTING.md#files)

<!-- /BACKERS -->


<!-- LICENSE/ -->

## License

Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT license](http://creativecommons.org/licenses/MIT/)

Copyright &copy; 2014+ Jed Watson <jed@thinkmill.com.au> (https://github.com/jedwatson)

<!-- /LICENSE -->


