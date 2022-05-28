# @jackfish/map-form-to-object

Map form field values onto object properties, via matching form field and schema property names

## Installation

    npm install --save @jackfish/map-form-to-object

## Usage

```js
var mapFormToObject = require('@jackfish/map-form-to-object')
var schema = require('./article-schema')()

var formData = mapFormToObject($('form'), schema)
// formData will be an object with any values for schema properties
// that could be extracted from the form by [name] attributes.
```

## Credits

Built by developers at [Clock](http://clock.co.uk).

## Licence

Licensed under the [New BSD License](http://opensource.org/licenses/bsd-license.php)
