# Javascript Notes

[JS help](https://www.w3schools.com/js/default.asp)

- Variables are containers for storing values.
- JavaScript identifiers are case-sensitive.

- The "equal to" operator is written like == in JavaScript.
The Assignment Operator
In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.
This is different from algebra. The following does not make sense in algebra:
x = x + 5
In JavaScript, however, it makes perfect sense: it assigns the value of x + 5 to x.
(It calculates the value of x + 5 and puts the result into x. The value of x is incremented by 5.)

- It's a good programming practice to declare all variables at the beginning of a script.

All JavaScript variables must be identified with unique names.
These unique names are called identifiers.
Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).
The general rules for constructing names for variables (unique identifiers) are:

    Names can contain letters, digits, underscores, and dollar signs.
    Names must begin with a letter
    Names can also begin with $ and _ (but we will not use it in this tutorial)
    Names are case sensitive (y and Y are different variables)
    Reserved words (like JavaScript keywords) cannot be used as names

JavaScript Data Types
JavaScript variables can hold numbers like 100 and text values like "John Doe".
In programming, text values are called text strings.
JavaScript can handle many types of data, but for now, just think of numbers and strings.
Strings are written inside double or single quotes. Numbers are written without quotes.
If you put a number in quotes, it will be treated as a text string.

Ex:
 <p id="demo"></p>

<script>
let carName = "Volvo";
document.getElementById("demo").innerHTML = carName;
</script> 

Key note:
When to Use JavaScript var?
Always declare JavaScript variables with var,let, orconst.
The var keyword is used in all JavaScript code from 1995 to 2015.
The let and const keywords were added to JavaScript in 2015.
If you want your code to run in older browser, you must use var.

Good to know:
One Statement, Many Variables
You can declare many variables in one statement.
Start the statement with let and separate the variables by comma:
Example
let person = "John Doe", carName = "Volvo", price = 200;
A declaration can span multiple lines:
Example
let person = "John Doe",
carName = "Volvo",
price = 200;

## Notes to self:

Several screen shots have been saved under "102" in Code Fellows folder for ideas and help.  

**This will take some time, but it will make sense**

