# Let, var, and const in JavaScript

JavaScript has three keywords for declaring variables: `let`, `var`, and `const`.

## `let`

`let` is a block-scoped variable. This means that the variable is only accessible within the block in which it is declared.

- Brings errors if declared out of scope

```javascript
let x = 10;

if (x > 5) {
  console.log(x); // 10
}


## `var`

`var` is a function-scoped variable. This means that the variable is accessible within the function in which it is declared, and within any nested functions.

javascript
function foo() {
  var x = 10;

  function bar() {
    console.log(x); // 10
  }

  bar();
}

foo();


## `const`

`const` is a constant variable. This means that the value of the variable cannot be changed after it is declared.

javascript
const x = 10;

x = 20; // Error: Cannot assign to read only property 'x'


## Summary

| Keyword | Scope | Mutable |
|---|---|---|
| `let` | Block | Yes |
| `var` | Function | Yes |
| `const` | Global | No |

