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

## HTML

Semantics give content a specific meaning, appearance or function.  An h1 heading will always be the top level heading, or a footer will contain certain information consistently.  Something without semantics like <span> just lets me wrap content so I can do something with it in CSS or JS as a whole.

There are 6 levels of heading in HTML, h1 - h6.
  
<sup> or superscript allows numbers or letters to be applied half way above another character, such as the th in the 25th of December or the 2 in x squared.
<sub> does the opposite of <sup> and allows numbers to be put half-way down another character, such as a chemical formula.

The title attribute is used to provide the full expansion of a term.
  
## CSS

A <link> element is used to apply cSS to HTML, <link rel="stylesheet" href="location">
  
We avoid using CSS inline because it's the least effecient and it mixes with presentational code in HTML and content which really makes for a messy look in code.

h2 is the selector
color and padding are the declarations
black and 5px are the properties
  
## JS

The data type enclosed in single quote marks is a string
  
addition, subtraction, multiplication and division signs are 4 types of js operators
  
A real world problem that could be solved with a function is to perform some sort of math computation, running the function with the variables will produce that result when called.
  
## Conditionals
  
An if statement checks a condition and evaluates if it is true, then runs a code block.
  
An else if statement allows for more than 2 choices or outcomes to be evaluated
  
comparison operators:

  === or !== test if values are identical or not
  < or >  test if values are less than or greater than another
  <= or >= test if values are less/greater than or equal to another

The logical operators && require both to be true for the whole to be true, while the || only requires one statement to be true for the whole to be true.


## Sidenotes from class:

console.log can help with troubleshooting by letting me see the output to js functions and tells me what is happening.

alert is used to display something to a user, but not really used as a question, because there is no way for the user to provide input

prompt is used to get input from the user, such as 'what is your name?', gives us a value from the user

let name = prompt('What is your name?');  from let to semicolon is the entire js statement, prompt is going to be the expression located in the statement.

if 'let name =' is removed, then we don't get a value of the user's name stored so when the next line to call for the valuue is added, nothing will happen:
prompt('What is your name?');
console.log('Your name is : ' + name);

The prompt will appear, but the value won't be created.

## Things I want to know more about

Functions
I haven't used console.log much and should ask

