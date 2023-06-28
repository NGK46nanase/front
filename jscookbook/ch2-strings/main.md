## Checking for an Existing, Nonempty string

```
if (typeof unknownVariable === 'string' || String.prototype.isPrototypeOf(unknownVariable) ) {
// more code
}
```

" typeof " operator returns the type name of the variable as a lowercase string.
The possible values are 
  * undefined
  * boolean
  * number
  * bigint
  * string
  * symbol
  * function
  * object

Important. 
 (1) null values return the string object instead.
 (2) function data type, even though a  function is technicallu a special case  of object
 (3) null, undefined, and empty strings ('') are fall falsy in JavaScript
 (4) number 0 always evaluates to false

 ## Converting a numeric value to a formatted string
