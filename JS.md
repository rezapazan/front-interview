# JS Interview Questions

**1. What are the different data types present in javascript?**

- Primitive
  - String
  - Number
  - Boolean
  - BigInt
  - Undefined
  - Null
  - Symbol
- Non-primitive

**2. Difference between var and let keyword in javascript.**

- From the very beginning, the 'var' keyword was used in JavaScript programming whereas the keyword 'let' was just added in 2015.
- The keyword 'Var' has a function scope. Anywhere in the function, the variable specified using var is accessible but in ‘let’ the scope of a variable declared with the 'let' keyword is limited to the block in which it is declared. Let's start with a Block Scope.
- In ECMAScript 2015, let and const are hoisted but not initialized. Referencing the variable in the block before the variable declaration results in a ReferenceError because the variable is in a "temporal dead zone" from the start of the block until the declaration is processed.

**3. Explain Hoisting in javascript.**
Hoisting is the default behavior of javascript where all the variable and function declarations are moved on top. This means that irrespective of where the variables and functions are declared, they are moved on top of the scope. The scope can be both local and global.

**4. Explain Closures in JavaScript.**
Closures are an ability of a function to remember the variables and functions that are declared in its outer scope.

**5. Explain the event loop in JS.**
The Event Loop is a fundamental concept that ensures JavaScript's single thread remains responsive. It continuously checks the execution stack for tasks to be executed. If the stack is empty, it checks the task queue for pending asynchronous tasks. When a task is complete, its callback is pushed onto the stack for execution. This ensures that even though JavaScript processes tasks sequentially, it can still handle asynchronous tasks efficiently without blocking the main thread.

**6. Explain “this” keyword.**
The “this” keyword refers to the object that the function is a property of. The value of the “this” keyword will always depend on the object that is invoking the function.

**7. What do you think of cloning an Object in js?**

- Deep Copy
  - `JSON.parse(JSON.stringify())`
  - `structuredClone()`
  - Third Party Libs e.g. Lodash
- Shallow Copy
  - Spread Operator
  - `Object.assign()`
  - `Array.from()`
  - `Object.create()`
  - `Array.prototype.concat()`

**8. What is a Temporal Dead Zone?**
Temporal Dead Zone is a behavior that occurs with variables declared using let and const keywords. It is a behavior where we try to access a variable before it is initialized.

**9. What are object prototypes?**
All javascript objects inherit properties from a prototype. A prototype is a blueprint of an object. The prototype allows us to use properties and methods on an object even if the properties and methods do not exist on the current object.

**10. Explain JS design patterns.**

- Singleton
- Proxy
- Prototype
- Observer
- Mixin
- Factory
- etc.

**11. What is tree shaking?**
Tree shaking is a term commonly used within a JavaScript context to describe the removal of dead code. It relies on the import and export statements to detect if code modules are exported and imported for use between JavaScript files.

- Webpack
- Rollup
