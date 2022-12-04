# JavaScript: Variables

In programming you can look at a variable as a container to hold your values. a little box in your computers memory were information will be stored.

### When creating a variable

```
  -'assure you use descriptive names'
  -'store or update information stored in the variable'
  -'reference or retrieve data when needed'
  -'modern js uses let, and const not var'

```

### Changes with ES6(version 2015)

```
  -'before the changes with ES6 their was only var(variable) to create a variable'
  -'Now we have let and const'

```

### Variable Conventions

```
  -'camelCase is a standard naming convention'
  -'= use the equal sign as a means to assign the value to the variable'
  -'do not start variable names with numbers'
  -'variable names are case sensitive'
  -'its bad practice to name variables with the same same but different cases'
  -'do not name using keywords
    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#keywords
  '
```

### var

```
  -'their is still code out there using var'
  -https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var
  -'when var is used it can be hoisted meaning that it will be called before anything else its placed on top of the stack'
  -''use strict'; was used to prevent leakage when var was assigned to the global scope'

```

### let

```
  -'I love using let because it signals that the value can be reassigned'
  -'the variable can be declared without being  assigned anything, the value is initialized with undefined'

```

### const(constant)

```
  -'const values cannot be reassigned, attempting to reassign the value will result in a TypeError: Assignment to constant variable.'
  -'you must declare a const with a value to avoid a syntax error'

```

### The Increment and Decrement Operator

```
  -'the increment operator(++) increases the value by 1'
  -'the decrement operator(--) decrease the value by 1'

```

#### example

```
  let a = 10;
  a++;
  console.log(a); // output: 11

```

```
  let b = 20;
  a--;
  console.log(b); // output: 19

```

### typeof operator

```
  -'the typeof operator allows you to verify the datatype being used'
```
