# JavaScript: Strings

Using the + operator with strings appends one string another this is called concatenation

 Add a space to the string after the initial string or the appending strings will join without any spaces

#### Examples

<code>
```
  console.log('front ' + 'space'); 
// Prints 'front space'
console.log('back' + ' space'); 
// Prints 'back space'
console.log('no' + 'space'); 
// Prints 'nospace'
console.log('middle' + ' ' + 'space'); 
// Prints 'middle space'
```
</code>

### String Concatenation with Variables

```
  - 'the (+) operator concatenates values event if the value is stored in a variable.
'
 -'
  let name = sam;

  console.log('My name is ' + name + '.') //output: my name is sam.;
 '
```

### String Interpolation

```
  -'When I first started to code I enjoyed using template literal'
  -'with template literal you use backticks`..`' to add values. unlike concatenation you do not have to use a + operator.
  -`you use ${value}`
  -'template literals allow your code to be more readable to others'

  example

  https://gist.github.com/1a1845fd7b7423f8ef3fa8d365695376

```