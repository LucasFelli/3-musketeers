# cash

## Features
- convert an amount of a currency into others currencies (http://akep.us/currencies)
- save default conversion

## Installation
required libraries: 
	- conf
	- chalk
	- update-notifier
	- got
	- money
	- ora
	
## API https://api.fixer.io/latest
This API is used to get the different exchange rates needed for the conversion.

## Examples
$ node bin/index.js 1 usd

$ node bin/index.js 1 usd eur pln aud

$ node bin/index.js --save usd eur pln aud

$ node bin/index.js --help