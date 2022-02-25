# JavaScript Fundamentals

`console.log()` - Logs to the console everything inside the parentheses.

`alert()` - Do a popup box on the page.

## Variables

Variables are named storage for data. We use the `let` keyword to create
a variable.

```js
let message
message = 'This is a message'
alert(message)

// OR a cleaner way to write it:
let message = 'This is a message'
alert(message)

// We can declare more then one variable at the same line:
let name = 'John',
  age = 19,
  message = 'Hello world'

// Change a variable value:
let message = 'hello'
message = 'world'

// copy variable
message = name // message = "John"
```

### Naming a variable:

Variables name uses camelCase, if there are more than one word then the next word will start
with capital letter. Ex: `myLongName`

The naming is matter: `apple` and `AppLE` are two different variables.

> Non-Latin values are allowed but not recommended

Also, the symbols: \_ and \$ are allowed in naming.

## Constants

Constants are unchangeable variables. Use the `const` keyword to create them.

### Naming:

- If the constant is known in load time he will use UPPER_CASE only.
- Otherwise, will be named like a normal variable.

## Operators & Numbers

[All the operators and examples](https://javascript.info/operators)

- `+` before a string makes it a number.

- Chaining assignments make is easier to assign multiple variables to the same value [ref](https://javascript.info/operators#chaining-assignments)

## Strings

Useful functions:

- `replace(word, newWord)`
- `trim()` - Trim the whitespaces
- `slice(startPos, endPos)` - return new string
- `split(at)` - split at the giving value
