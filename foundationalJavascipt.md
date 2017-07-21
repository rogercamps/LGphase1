# Foundational JavaScript Programming

In this module we're going to cover some of the basics of general programming
as well as the basics of programming in JavaScript. You might have covered some
of this before you arrived at the guild but make sure you have these skills
before moving on from this module.

## Skills

### General Programming

- [x] Can describe what a variable is
- [x] Can describe the difference between a local and global variable
- [x] Can describe a Function
- [x] Can describe a Hash
- [x] Can describe a Array
- [x] Can describe a Set  

- Sets eliminate duplicates, https://www.youtube.com/watch?v=mzlIYyY6he4  

- [x] Can describe the ! (bang) operator
- [x] Can describe an "if statement"
- [x] Can describe a pure vs. impure function  
- Pure functions produce always the same output given the same input, and produces no side effects like network or database calls. They dont modify the arguments which are passed to them.  

- https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976

- Impure functions, their return value dont solely depend on its arguments, the same set of arguments might give you different return values.

- [x] Can describe operator precedence
- Operator precedence determines the order in which operators are evaluated. Operators with higher precedence are evaluated first.

- [x] Can describe the `push` Array method
- [x] Can describe the `pop` Array method
- [x] Can describe the `shift` Array method
- [x] Can describe the `unshift` Array method
- [x] Can describe the `each` Array method
- [x] Can describe the `map` Array method

- Creates a new array of the same length and with the modification we ask it to do.

- [x] Can describe the `filter` Array method
- Accepts another function as an argument that will use to return a filtered (usually smaller) version of the new array. Can modify and trim a new array.

- [x] Can describe the `reduce` Array method
- The way it works is similar to a mix of map and filter together.
- [x] Can describe a closure
- A function that can use the variables or elements around it at the time that it is created

### JavaScript Specific

- [x] Can write a Function in JavaScript
- [x] Can write an Object literal in JavaScript  
- [x] Can write an Array literal in JavaScript
- [x] Can write an String literal in JavaScript
- [x] Can write an Number literal in JavaScript
- [x] Can write and `if`/`else` statement in JavaScript
- [x] Can write and `switch` statement in JavaScript
- [x] Can write and `while` loop in JavaScript
- [x] Can write and `for` loop in JavaScript
- [x] Can write a pure function in JavaScript
- [x] Can set the value of a property on a JavaScript Object using `.` syntax  
```javascript
  var obj = {
    student1: 'Roger',
    student2: 'Jordi'
  }

  console.log(obj.student1); -> returns Roger

  obj.student1='Xevi';

  console.log(obj.student1); -> returns Xevi
```

- [x] Can set the value of a property on a JavaScript Object using `[]` syntax
```javascript
  var obj = {
    student1: 'Roger',
    student2: 'Jordi'
  }

  console.log(obj.student1); -> returns Roger

  obj['student1']='Xevi';

  console.log(obj.student1); -> returns Xevi
```
- [x] Can get the value of a property on a JavaScript Object using `.` syntax
```JavaScript
  obj.student1
```
- [x] Can get the value of a property on a JavaScript Object using `[]` syntax
```JavaScript
  obj['student1']
```
- [x] Can describe the difference between `==` and `===` in JavaScript
- == and === check if two values are equal to each other, == being not strict and === being strict. Being strict meaning that it doesn't only check the values but also the type of those values.

- [x] Can describe the difference between `var`, `let`, and `const` in JavaScript
- [x] Can use `Array#push` in JavaScript
- [x] Can use `Array#pop` in JavaScript
- [x] Can use `Array#shift` in JavaScript
- [x] Can use `Array#unshift` in JavaScript
- [x] Can use `Array#forEach` in JavaScript
- [x] Can use `Array#map` in JavaScript
- [x] Can use `Array#filter` in JavaScript
- [x] Can use `Array#reduce` in JavaScript
- [x] Can declare local vs. global variables in JavaScript
- declared inside or outside of a function

- [x] Can get all the keys on a JavaScript object
- Object.keys(obj)

- [x] Can get all the values on a JavaScript object
- Object.values(obj)

- [x] Can write a closure in JavaScript
- function declared inside another function. Also called lexical scope.
```JavaScript
// Scope A
  var myFunction = function () {
    // Scope B
    var name = 'Todd'; // defined in Scope B
    var myOtherFunction = function () {
      // Scope C: `name` is accessible here!
    };
  };
```

- [ ] Can pass multiple objects into a function using a plain object as a single argument, in JavaScript

- [x] Can describe lexical scope inheritance in JavaScript
- Lexical scope is easy to work with, any variables/objects/functions defined in its parent scope, are available in the scope chain. Lexical scope does not work backwards.
``` JavaScript
  var name = 'Todd';
  var scope1 = function () {
  // name is available here
    var scope2 = function () {
      // name is available here too
      var scope3 = function () {
        // name is also available here!
      };
    };
  };
```
- [x] Can split a string into an array in JavaScript
- [x] Can join an array into a string in JavaScript


## Glossary of Terms

### General Programming

| Term         | Explanation |
| ------------ | ----------- |
| String       | An ordered list of text characters |
| Number       | An object type representing either an Integer or a Float |
| Object       | A data structure |
| Array        | An array is an ordered set of values that you refer to with a name and an index. |
| Hash         | A data type mapping keys to values |
| Index        | AKA Hash |
| Map          | AKA Hash |
| Function     | A code snippet that can be called by other code or by itself, or a variable that refers to the function. When a function is called, arguments are passed to the function as input, and the function can optionally return an output. A function in JavaScript is also an object. |
| Boolean      | A logical data type that can have only the values true or false |
| Conditional  | A set of rules that can interrupt normal code execution or change it, depending on whether the condition is true or not |
| Literal      | A way of declaring an object as it is literally meant to be interpreted |
| Truthy       | A value that translates to true when evaluated in a Boolean context |
| Falsy        | A value that translates to false when evaluated in a Boolean context |
| Comment      | A part of your source code that is ignored by the computed and is meant for other developers to read |
| Error        | An unindented event or outcome |
| Syntax Error | A error that is thrown when your source code is written incorrectly |

### JavaScript Specific

| Term           | Explanation |
| -------------- | ----------- |
| Number         | In JavaScript, Number is a numeric data type that can represent both an Integer and a Float |
| Object         | Almost all values in JavaScript are objects |
| ReferenceError | The error that is thrown when your code attempts to use something that was not declared |

[More](https://www.codecademy.com/articles/glossary-javascript)
[A Lot More](https://developer.mozilla.org/en-US/docs/Glossary)
[JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

## Search Terms

```
javascript split string into array
```

## Exercises

- https://www.codecademy.com/courses/getting-started-v2/0/1
- https://www.freecodecamp.com/challenges/use-conditional-logic-with-if-statements
- https://www.freecodecamp.com/challenges/iterate-with-javascript-for-loops
- https://www.freecodecamp.com/challenges/iterate-odd-numbers-with-a-for-loop
- [Freecodecamp - Basic Javascript (10 hours)](https://www.freecodecamp.com/map)
- https://www.freecodecamp.com/challenges/iterate-with-javascript-while-loops
- https://www.freecodecamp.com/challenges/iterate-with-javascript-for-loops
- https://www.freecodecamp.com/challenges/declare-javascript-variables
- https://www.freecodecamp.com/challenges/iterate-over-arrays-with-map
- https://www.freecodecamp.com/challenges/filter-arrays-with-filter
- https://www.freecodecamp.com/challenges/condense-arrays-with-reduce
- https://www.freecodecamp.com/challenges/split-strings-with-split
- https://www.freecodecamp.com/challenges/join-strings-with-join
- https://github.com/workshopper/javascripting



## Resources

- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors
- http://javascriptissexy.com/javascript-objects-in-detail/
- https://medium.com/@prufrock123/js-dot-notation-vs-bracket-notation-797c4e34f01d
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys
- https://www.w3schools.com/jsref/jsref_obj_array.asp
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/prototype?v=example
- https://auth0.com/blog/glossary-of-modern-javascript-concepts/#purity
- https://medium.com/@zfrisch/destroying-buildings-a-simple-guide-to-javascript-closures-ef9fc326c73d
