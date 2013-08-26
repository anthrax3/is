# is
  
  Simply type checking.

## Installation

    $ component install ianstormtaylor/is

## Example

```js
var is = require('is');
is.array([]);              // true
is.object({});             // true
is.number(42);             // true
is.element(document.body); // true
```

## API

### is.arguments(val)
### is.array(val)
### is.boolean(val)
### is.date(val)
### is.element(val)
### is.function(val)
### is.null(val)
### is.number(val)
### is.object(val)
### is.regexp(val)
### is.string(val)
### is.undefined(val)

## License

  MIT
