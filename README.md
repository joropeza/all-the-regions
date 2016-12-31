all-the-regions
=========

Every United Nations-designated region and subregion with all their countries in a nice neat hash.

Inspired by

https://www.npmjs.com/package/countryjs

and sourced from 

http://unstats.un.org/unsd/methods/m49/m49regin.htm

Intended as a much lighter-weight way of accessing regions and subregions directly, without having to output a huge blob of full country data from countryjs and groupby.

## Installation

  npm install all-the-regions --save

## Usage ES5

  var regions = require('all-the-regions').regions
  console.log(regions);
  
## Usage ES6

  const subregions = import { subregions } from 'all-the-regions';
  console.log(subregions.Micronesia);

## Tests

  no tests as of yet

## Contributing

hit me with a PR if you see anything that needs fixin

## Release History

* 1.0.0 Initial release
