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
