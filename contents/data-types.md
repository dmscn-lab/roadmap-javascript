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