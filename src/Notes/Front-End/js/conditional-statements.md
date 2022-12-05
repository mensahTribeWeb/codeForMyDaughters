# JavaScript: Conditional Statements

Life is about choices even when you don't make a choice will be a choice a lead to a output.

In programming we also make choices they are if.. else if... and else, which helps the program go down a particular path.


## If Statement
```
  we do things daily based on conditions, for example 
  -if you are sleepy then you will sleep. 
  -if the clock goes off its time for school
  -if its nice out you will go into the yard to play

  <code>
    if(true) {
      console.log('this message will print!');
    }
    //output: this message will print!
  </code>

  https://gist.github.com/685af9d3834dd49ed8aaf73b6aeac2aa
```

### Syntax
```
  - if is a keyword followed by a (condition(true or false)) which then is followed by a {} code block
  -if the condition is true the code block executes
  - if the condition is false the block will not execute.
```

## if..else Statement
```
  - when a code block results in a false condition we will run the if.. else statement
  - a else statement is paired with an if statement

<code>
  if (false) {
  console.log('The code in this block will not run.');
} else {
  console.log('But the code in this block will!');
}
 
// Prints: But the code in this block will!
</code>

https://gist.github.com/fd85010114bd8695e8322cd39202516a
```

### Syntax
```
 - else is a keyword it follows the if statement
 - the else statement is wrapped by a set of {}
 - the code in the else statement executes when the if statement is false
```

## Comparison Operators
```
  - Less than: <
  - Greater than: >
  - Less than or equal to: <=
  - Greater than or equal to: >=
  - Is equal to: ===
  - Is not equal to: !==

  comparison operators compare items on the right to the left.

  comparison operator in a sense s just a question yes or no true or false.

  Strings can also be compared but with String the unicode value is compared for the characters in the the string

  https://gist.github.com/21977293cf26211870bdd71dd8b19dfd
```
<code>
  10 < 12 // Evaluates to true

  'apples' === 'oranges' // false
</code>

## Logical Operators
```
  add more sophisticated logic to our conditionals. 
  There are three logical operators:

  -the and operator (&&)

    -checks if two things are true
    if two things are true the result is true
    -if either condition is false the entire statement is false and the else block executes

  -the or operator (||)

   -if we only are concerned with only one condition being true then we use the or operator
   -if one condition is true the the other is ignored and the code block will execute
   -if both statement are false the else code block will execute


  -the not operator, otherwise known as the bang operator (!)

    -this negates the condition, it makes the condition the reverse of itself 
    -a true value returns false
    -a false value returns true
```
<code>
  let mood = "sleepy";
let tirednessLevel = 6;

if (mood === "sleepy" && tirednessLevel > 8) {
  console.log("time to sleep");
} else {
  console.log("not bed time yet");
}
https://gist.github.com/1d7299e5372a760134f4f11aac8c354f
</code>

## Truthy and Falsy
```
  -sometimes you only want check if a value is present
  -only checking if a value was assigned
  -truthy: not true but not false
  -falsy: evaluates to false
    -0
    -Empty string "" or ''
    -null
    -undefined
    -NaN
```
<code>
  let myVariable = 'I Exist!';
 
if (myVariable) {
   console.log(myVariable)
} else {
   console.log('The variable does not exist.')
}
</code>

<code>
  let numberOfApples = 0;
 
if (numberOfApples){
   console.log('Let us eat apples!');
} else {
   console.log('No apples left!');
}
 
// Prints 'No apples left!'
</code>

### examples
https://gist.github.com/16cdd2b7dcd50912f22953d69ab0e4d3

## Ternary Operator

```
 - we can write the if ...else condition in short hand form
 - the condition is placed before the ?
 - two expressions are separated by :
 - the first expression is executed when true
 - the second expression is executed when false

```
 <code>
    isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');
 </code>

 ### example
 https://gist.github.com/9b901940dd48752b04e798eacdc1e6c7

## Else If Statement

```
  - allows for more than two possible outcomes
  - else if always comes after the if statement
  - each outcome is checked until one is true or else will be  the default condition.

``` 
### examples
https://gist.github.com/8f8c78f5376634f6778b74ff4c4b85ca

## The Switch keyword

```
 - a different syntax for writing else if statements
 - switch is followed by the condition in (...)
 - inside the code block their are multiple cases followed by breaks
 -the break keyword indicates that the computer should exit the code block and not execute anymore statements
 - the default is like the else of the switch statement it will be the last to executed if all statements fail
```

### examples
https://gist.github.com/7a201832adb01c124f44d5acafa471fc


