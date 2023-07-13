## JS MUST KNOWS!

### What is the keyword `this` in JS?

### What is closure?

### What is a promise?


## Other Questions:

### What does `fn.call()` do?

### What does `fn.apply()` do?

### What does `fn.bind()` do?

### What does the `new` keyword do?
    1. makes an object
    2. assings `this` to be the object it created
    3. return `this` (implicity returns the object it created)
    4. The newly created object is linked to the prototype object of the constructor function. This linkage allows the object to access properties and methods defined on the constructor function's prototype.

###
## NOTES:
- Every function in JavaScript has a built-in property called `prototype`, which is an object used as a blueprint for creating new objects.
- When using the `new` keyword with a constructor function, a new object is created, and its `__proto__` property is set to the value of the constructor function's `prototype` property.
- When accessing a property on an object, JavaScript first looks for the property on the object itself. If not found, it looks at the object's prototype, and the search continues up the prototype chain until the property is found or the end of the chain is reached.