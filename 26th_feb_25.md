Today, I started the "How JavaScript Works Behind the Scenes" section, where I learned core concepts:

Execution Context and the Call Stack:
I learned that JavaScript runs code inside an execution context, which consists of three phases—creation, execution, and deletion.

Global Scope: Variables declared outside any function are accessible everywhere.

Function Scope: Variables declared inside a function are only accessible within that function.

Block Scope (introduced in ES6): Variables declared with let and const inside a block {} are only accessible within that block.

The scope chain ensures that when a variable is not found in the local scope, JavaScript looks for it in the outer scopes until it reaches the global scope.

Hoisting and Temporal Dead Zone (TDZ):
Hoisting allows function declarations and variables (declared with var) to be moved to the top of their scope before execution.
Variables declared with let and const are also hoisted but remain in the Temporal Dead Zone (TDZ) until they are initialized, preventing access before declaration.

The this Keyword:
The value of this depends on how a function is called.
In the global scope, this refers to the global object (window in browsers).
In regular functions, this is undefined in strict mode.
In arrow functions, this is lexically inherited (it takes this from its surrounding function).

Primitive vs. Reference Values:
Primitive values (numbers, strings, booleans, null, undefined, Symbol, BigInt) are stored directly in memory.
Reference values (objects, arrays, functions) are stored in the heap, and variables hold a reference to the memory location rather than the actual value.



After completing this section, I moved on to "Data Structures, Modern Operators, and Strings". Here, I learned about destructuring arrays and objects, which allows for easier extraction of values. I also learned about the spread operator (...), which helps expand elements, and the rest pattern & parameters, which work in the opposite way by collecting multiple elements into an array. This section is still in progress.
