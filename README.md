# intro-to-markdown-lab
# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

__const__ functionName = (params) => {
  // code to be executed
}

+ const: __const__ should be used whenever a function expression is assigned to a variable.
+ __The function name__: The name you choose for the function.
+ __Parameters__: Optional comma separated __parameters__. This is the data passed into the function. If there are no __parameters__, the () is still required.
+ __The arrow syntax__: Indicates that this will be a function.
+ __The body__: The statements that make up the function itself. Surrounded by curly braces.

___Example___:

__const__ greet = (name) => {
  console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

___Example___:

greet('Alice'); // Outputs: Hello, Alice!

## 3. Return values

Functions can process data input and output a value using the _return_ keyword.

___Example___: 

__const__ addNums = (numA, numB) => {
  return numA + numB
}

__const__ total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
