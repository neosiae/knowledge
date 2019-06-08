# JavaScript

## this

Each function has its own `this` binding, that holds the _context_ of a function, whose value depends on how the function is called.

## Arrow functions

Arrow functions don't create their own `this`, but they can see `this` of the scope around them.

## Prototype

Prototype is an object that is used as a fallback source of properties. When an object gets a request for a property that it does not have, its prototype will be searched for the property, then the prototype's prototype... and so on until it reaches the end of the prototype chain.

## Converting to Boolean

There are three ways any value can be converted to a boolean:

|                      |                                                                                      |
| -------------------- | :----------------------------------------------------------------------------------: |
| Boolean(value)       |                    (Invoked as a function, not as a constructor)                     |
| value ? true : false |                                                                                      |
| !!value              | A single “not” converts to negated boolean; use twice for the nonnegated conversion. |

### See Also

- [Chapter 10. Booleans](http://speakingjs.com/es5/ch10.html)
- [Using Double Not-Operator (!!) For Boolean Type Casting](https://www.bennadel.com/blog/1784-using-double-not-operator-for-boolean-type-casting.htm)
