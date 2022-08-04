# JS programming

## Control flow

The *control flow* is the order in which the computer executes statements in a script.
A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.
Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

## Functions 

A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" invokes it (calls it).

Example code:
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

The code inside the function will execute when "something" invokes (calls) the function:
   - When an event occurs (when a user clicks a button)
   - When it is invoked (called) from JavaScript code
   - Automatically (self invoked)

When JavaScript reaches a return statement, the function will stop executing.
If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
Functions often compute a return value. The return value is "returned" back to the "caller":
Ex:
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

