# In Memory Storage

## Why this is important

If anyone has seen any code, I think it's obvious as to why debugging is important.

Knowing how call stacks works helps in the design of writing code, understanding how and when it will be used determines where it should be placed in the stack.

## Javascript Call Stack

1.  Function invocation

2.  One at a time

3.  Last in, first out

4.  function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

[call stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

5.  Stack overflow is when function calls itself, but doesn't have an exit point, the function will run itself until the browser throws a "maximum call size exceeded"

## Javascript error messages

1.  Reference error: using an undeclared variable or using a variable before it's declared

2.  Syntax error:  errors in the code itself, missing trailing comma, or missing `, '', etc

3.  Range error:  an object with an invalid length, such as an array with a negative length (outside cited example) [ex:](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

4.  Type error:  > "...when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable."[Typer Errors](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

5.  Breakpoint:  will stop code from running either through a condition set (if a value = true or false) or just setting it to stop to make sure a code block functions correctly.

6.  the word 'debugger' can create a breakpoint in the code line to be broken.

## Things I want to know more about

Breakpoints seem like they would be helpful, I think VScode has it built in to select a red dot on the line you want a breakpoint installed.

## References & links

[Errors & Debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
