### Javascript String:
JavaScript has **seven primitive data types**, with String being one of them. 
- In JavaScript, a string represents a sequence of characters and can be enclosed in either single (`'`) or double (`"`) quotes.
- Note that strings are immutable, which means once they are created, they cannot be changed. The variable can still be reassigned another value.
- strings are case-sensitive.

### Variables Declaration & Initialization
- When you declare a variable without initializing it, it is considered `uninitialized`.
- The default value of an uninitialized variable is `undefined`. This is a special data type that represents a value that does not have a definition yet.

### Array
- An array is a non-primitive data type that can hold a series of values. Non-primitive data types differ from primitive data types in that they can hold more complex data. 
- Primitive data types like strings and numbers can only hold one value at a time.
- Arrays are denoted using square brackets (`[]`).
- `push()` -> returns the new length of the array, after adding the value you give it.
- `pop()` -> returns the value that was removed from the end of the array.
- `unshift()` -> push in the beginning, return the new length of the array.
- `shift()` -> pop in the beginning, return the popped value

### Const
- `const` variables are special.
- A `const` variable cannot be reassigned like a `let` variable.
- A `const` variable also cannot be uninitialized.

### for 
```
for (iterator; condition; iteration) {
  logic;
}
```
### for of
A `for...of` loop iterates over each item in an iterable object and temporarily assigns it to a variable.

The syntax for a for...of loop looks like:

Example Code:
```
for (const value of iterable) {

}
```
Note that you can use const because the variable only exists for a single iteration, not during the entire loop.

## Falsy values
JavaScript has a defined list of falsy values. Some of them include `false`, `0`, `""`, `null`, `undefined`, and `NaN`.