#typecast
Easy typecasting in javascript.

##Example
```js
var typecast = require('typecast');

typecast(123, 'string') // => '123'
typecast('123', 'number') // => 123
typecast('a, b, c', 'array') // => ['a', 'b', 'c']
typecast('false', 'boolean') // => false
```

##Api

###typecast(val, [type])
Cast given `val` to `type`

###typecast#string(val)
Cast `val` to `String`

###typecast#number(val)
Cast `val` to `Number`

###typecast#array(val)
Cast `val` to `Array`

###typecast#boolean(val)
Cast `val` to `Boolean`

##Licence
MIT