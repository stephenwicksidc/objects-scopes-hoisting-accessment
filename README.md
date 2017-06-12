## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.


### Provide examples for all three, below:

#### Scope:
Scope refers to the area in which blocks of code are executed.  The global scope is the top level and other scopes are created within the global scope by other functions, methods, etc.

#### Hoisting:

Hoisting refers to how javascript will tend to rearrange code so that it can run properly.  If a variable or function is trying to be used before it's defined, javascript with hoist it up to the top so that it recognizes the item.  With variables, only the declaration is hoisted not the assignment.  With functions, the whole function is hoisted and can be used effectively after being hoisted.

#### Compartmentalization:

Compartmentalization refers to when code is used in an IFEE.  The variables and components are immediately invoked and used for that particular function and then it is not used again outside of the function.  This protects the codebase from potential common errors of reusing variable names, etc.
