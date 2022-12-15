## Declarations
You can create variables in JavaScript using keywords:
- `var`
- `let`
- `const`

### var
A `var` keyword declares a variable with function scope or global scope. 
It can optionally initialize with a value.

```js
var welcome = "Hello World!"; // "Hello World!"
welcome = "Hello Friend!"; // "Hello Friend!"
```

### let
A `let` keyword declares a variable with local scope.
It can optionally initialize with a value.

```js
let firstName = "Wesley"; // "Wesley"
let lastName; // undefined

lastName = "Damasceno"; // "Damasceno"
```

### const
A `const` keyword declares a variable with local scope. Not allowed re-declaration or reassignment <br>
To change your value if a value is `Object` or `Array`. (Updating props)

```js
const welcome; // Error: Missing initializer in const declaration
const welcome = "Welcome to JavaScript!"; // "Welcome to JavaScript!"

welcome = "Welcome to Python!"; // Error: Assignment to constant variable.
```

## Hoisting
JavaScript `Hoisting` is basically the process by the interpreter show move a function declaration,<br> 
variables or class to the top of the scope, before that code execution. 

Hoisting types:
1. Can use the value a variable at your scope before the line of declaration. (Hoisting value)
1. Can reference a variable at your scope before the line of declaration, and don't launch `Reference error`,<br> 
but the value is ever `undefined`. (Hoisting of the declaration)
1. A variable declaration cause comportaments changes in your scope before the line of declaration.

- Type 1: `function`, `function *`, `async function`
- Type 2: `var`
- Type 3: `let`, `const`, `class`

```js
console.log(firstName); // undefined
var firstName = "Wesley"; // "Wesley"
```
```js
console.log(lastName); // ReferenceError: lastName is not defined
let lastName = "Damasceno"; // ReferenceError: lastName is not defined
```

## Variables Naming Rules

1. Be descritive
    - The variable name should clearly describe what it should have. 
2. Don't descritive excessive
    - We have to make sure we stay within the confines of the description.

Ex:
```js
let theFirstNameOfUser; // Bad code 💩
let firstName; // Better code 🥳
```
We have to stay between the descriptiveness scale, not too little and not too much.

3. Abbreviate long words
    - Sometimes it is really useful to abbreviate long words in a given name to short and simple words, as the abbreviation seems sensible.

Ex:
```js
let databaseName; // Bad code 💩
let dbName; // Better code 🥳
```

```js
let propertyName; // Bad code 💩
let pName; // Bad code 💩
let propName; // Better code 🥳
```

## Variables Scope

In JavaScript, scope refers to a variable's visibility or how it can be used once declared.

1. Global
1. Function
1. Block

### Global
They are variables declared outside any function or `{}`. can be accessed from anywhere within the code.

### Function
These are variables declared within a function. Which can only be accessed within that same function. Outside of it these variables are undefined.

### Block
Is any part of code delimited by `{}`. Variables declared inside a block cannot be accessed outside of it.