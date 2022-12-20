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

Accessing a function without () will return the function object instead of the function result.

## JS operators

Operator 	Description
+ 	      Addition
- 	      Subtraction
*       	Multiplication
** 	      Exponentiation (ES2016)
/ 	      Division
% 	      Modulus (Division Remainder)
++ 	      Increment
--      	Decrement

Assignment operators

Operator 	Example 	Same As
=       	x = y 	  x = y
+=      	x += y 	  x = x + y
-=      	x -= y 	  x = x - y
*=      	x *= y  	x = x * y
/=      	x /= y 	  x = x / y
%=      	x %= y 	  x = x % y
**= 	    x **= y 	x = x ** y

The addition assignment operator (+=) adds a value to a variable.

The += assignment operator can also be used to add (concatenate) strings:
Example
let text1 = "What a very ";
text1 += "nice day";

The result of text1 will be:
What a very nice day

Adding two numbers, will return the sum, but adding a number and a string will return a string:
Example
let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;

The result of x, y, and z will be:
10
55
Hello5 

Comparison operators

Operator 	Description
== 	      equal to
=== 	    equal value and equal type
!= 	      not equal
!== 	    not equal value or not equal type
> 	      greater than
< 	      less than
>= 	      greater than or equal to
<= 	      less than or equal to
? 	      ternary operator

Logical operators

Operator 	Description
&& 	      logical and
||       	logical or
! 	      logical not




