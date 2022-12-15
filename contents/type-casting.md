Type conversion (or typecasting) means the transfer of data from one data type to another. Implicit conversion happens when the compiler (for compiled languages) or runtime (for script languages like JavaScript) automatically converts data types. The source code can also explicitly require a conversion to take place.

## Type Conversion
For example, given the expression `"foo" + 1`, the Number `1` is implicitly converted into a String and the expression returns `"foo1"`.

## Type Coercion
Type coercion is the automatic or implicit conversion of values from one data type to another (such as strings to numbers). Type conversion is similar to type coercion because they both convert values from one data type to another with one key difference — type coercion is implicit whereas type conversion can be either implicit or explicit.

```js
const value1 = "5";
const value2 = 9;
const sum = value1 + value2;

console.log(sum); // "59"
```

## Explicit
Type casting means transferring data from one data type to another by explicitly specifying the type to convert the given data to. Explicit type casting is normally done to make data compatible with other variables. Examples of typecasting methods are:

- `parseInt()`
- `parseFloat()`
- `toString()`

## Implicit
Implicit type conversion happens when the compiler or runtime automatically converts data types. JavaScript is loosely typed language and most of the time operators automatically convert a value to the right type.