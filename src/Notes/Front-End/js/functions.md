#JavaScript: Functions

## What are functions exactly?

a function ais block of code that groups together a sequence of instructions to preform a task.

functions help keep the code DRY

function have a input that results in an output

## Function Declarations

hoisting allows a function to be called before the function declaration.

a function declaration binds a function to a name or identifier

```
  function greetWorld(){
    code block
  }
```

A function declaration consist of:

-a function keyword
-the function name or identifier followed by a ()
-the function code block{ }

## Calling a function

- you can call a function by following the function name with ()
- functionName();

https://gist.github.com/489b414cd5f1c17bdc45aedfff7a5940

## Parameters and Arguments

Parameters: allows functions to take in input and preform task using input.

Arguments: when calling a function we pass in arguments.

arguments are passed in the order parameters are assigned.

https://gist.github.com/98e7605289760fe87dec40aba79ac7c6

## Default Parameters

default arguments allow parameters to have predetermined values incase to arguments are present or the argument is undefined.

- default values are great to include non personalized values

<code>
  function greeting (name = 'stranger') {
  console.log(`Hello, ${name}!`)
  }
 
  greeting('Nick') // Output: Hello, Nick!
  greeting() // Output: Hello, stranger!
</code>

https://gist.github.com/be67dc767d817418e1aa88d262f98dee

## Return

https://gist.github.com/7eb90d8eaca8f1b4f032d58846295113

## Helper Functions

https://gist.github.com/9ae317e28d05ceec7a8af0be9d071358

## Function Expressions

https://gist.github.com/911a225a361ea36ad2b33a1cadf93829

## Arrow Function

https://gist.github.com/75269f5de06a74b353d7b790d38b7c0e

## Scope

scope defines when and where variables can be accessed or referenced. the scope can be defined globally or locally.

the context in which our variables are declared.

## Blocks and Scope

the block is the code found inside of curly braces of functions and if statements. inside the block tends to be the local scope.

### example
https://gist.github.com/09aa5f833a7b3526c2708850469f17b4

## Global Scope

this is when a variable is declared outside of the local code block. these are called global variables.

global variables can be accessed inside of the functions code block.

### example

https://gist.github.com/6190f127948aa8cd1938a862949314f9

## Block Scope

the variable is defined inside of the the local code block. this is called block scope because it is only accessible to the lines in the block.

trying to access this block scope variable outside of the scope will result in a ReferenceError

## examples

https://gist.github.com/88ad203ee8ea27e6b142db4152612d95

## Scope Pollution

when creating a global variable, they go to the global namespace.

scope pollution : is when their are to many global variables, which makes it difficult to keep track of the many variables.

global variables can collide with local variables.

### examples
https://gist.github.com/2da7236e4e6136be0635489c79261acb

## Practice Good Scoping
tightly scoping variables will greatly improve your code.
- the blocks will organize the code into discrete sections.
- this clarifies the code so that the code is easier to read.
- since the code is modular the code is easier to maintain.
- it saves memory because the variable is used when needed.

### example

https://gist.github.com/bc27e8a98ea0d7c9d29c0c5482a606d1

https://gist.github.com/788e82d1edf3d5a2b3e5eb290059e719

https://gist.github.com/b0386f03508e18c869d87f789eb3ead2


