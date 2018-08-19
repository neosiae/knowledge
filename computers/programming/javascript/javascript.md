# JavaScript

## this

Each function has its own `this` binding, that holds the _context_ of a function, whose value depends on how the function is called.

## Arrow functions

Arrow functions don't create their own `this`, but they can see `this` of the scope around them.

## Prototype

Prototype is an object that is used as a fallback source of properties. When an object gets a request for a property that it does not have, its prototype will be searched for the property, then the prototype's prototype... and so on until it reaches the end of the prototype chain.
