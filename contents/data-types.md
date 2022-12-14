## Primitive Types
In JavaScript, a primitive (primitive value, primitive data type) is data that is not an object and has no methods or properties.

### String
Any programming language a `String` is a sequence of characters used to text representation.

```js
"Hello World"
'Hello World'
```

### Number
In JavaScript, `Number` is a numeric data type in 64-bit double-precision floating point format. `(IEEE 754)`

```js
100
0
222
```

### BigInt
In JavaScript, `BigInt` is a numeric data type that can represent integers in arbitrary precision format.

```js
9007199254740991
```

### Boolean
In computer science, boolean is a logical data type that can only have the values ​​`true` or `false`. In JavaScript Boolean conditionals are used to decide which sections of code should be executed.

```js
true
false
```

### undefined
It is a primitive value automatically assigned to variables that have just been declared or to formal arguments for which there are no real arguments.

```js
let x;
console.log(x); // undefined
```

### null
In computer science, a `null` value represents a reference that points, usually to a nonexistent or invalid object or address. In JavaScript, `null` is marked as one of the primitive values ​​because its behavior is apparently primitive. However when using the typeof operator it returns:

```js
console.log(typeof null); // "object"
```

This is considered a bug, but one that cannot be fixed as it will break many scripts.

## Typeof Operator
The typeof operator returns a string indicating the type of the operand value.

```js
console.log(typeof 42); // "Number"
console.log(typeof "Blubber"); // "String"
console.log(typeof true); // "Boolean"
```

## Object
JavaScript object is a data structure that allows us to have key-value pairs; so we can have distinct keys and each key is mapped to a value that can be of any JavaScript data type. Comparing it to a real-world object, a pen is an object with several properties such as color, design, the material it is made of, etc. In the same way, JavaScript objects can have properties that define their characteristics.

```js
const user = new Object(); // constructor
const tasks = {}; // literal
```

```js
const tasks = {
  read: "10 pages",
  workout: 30,
};
```

> [JavaScript Info - Object](https://javascript.info/object)

> [MDN Docs - Working with Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

## Object Prototype
JavaScript is an object-oriented language built around a prototype model. In JavaScript, every object inherits properties from its prototype, if there are any. A prototype is simply an object from which another object inherits properties. To create complex programs using JavaScript, one has to be proficient in working with prototypes — they form the very core of OOP in the language.

> [JavaScript Info - Prototypes](https://javascript.info/prototypes)

## Prototypal Inheritance
The Prototypal Inheritance is a feature in javascript used to add methods and properties in objects. It is a method by which an object can inherit the properties and methods of another object. Traditionally, in order to get and set the Prototype of an object, we use Object.getPrototypeOf and Object.

> [JavaScript Info - Prototype Inheritance](https://javascript.info/prototype-inheritance)

