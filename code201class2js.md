# JavaScript Fundamentals

## Data Types

Loosely typed language = types can change

- String: natural language characters
- Numbers:  1 - 10000000 / fractions / decimals
- Boolean:  True / False (truthy / falsey)
- Undefined:  lacking a value (a value to say there is no value)
- Null:  setting something to have no value
- NaN: Not a Number (it only tells you what something is not, does not tell you what it is) usually means an error
- isNan(). (is something NaN?)

let nothing;  // value undefined

nothing = null; // assigned the value of null

## Conditional Statements

Controls which lines of code are run










## Sidenotes from class:

console.log can help with troubleshooting by letting me see the output to js functions and tells me what is happening.

alert is used to display something to a user, but not really used as a question, because there is no way for the user to provide input

prompt is used to get input from the user, such as 'what is your name?', gives us a value from the user

let name = prompt('What is your name?');  from let to semicolon is the entire js statement, prompt is going to be the expression located in the statement.

if 'let name =' is removed, then we don't get a value of the user's name stored so when the next line to call for the valuue is added, nothing will happen:
prompt('What is your name?');
console.log('Your name is : ' + name);

The prompt will appear, but the value won't be created.

