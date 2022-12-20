# Code 201 Class 7 reading 

## Domain modeling

"Domain modeling is the process of creating a conceptual model in code for a specific problem." [MDN](Domain modeling is the process of creating a conceptual model in code for a specific problem.)  It can allow both tehcnical and business teams understand the specific problem.

## HTML Tables

Tables are more complex structures than a basic HTML layout, so if they're used to layout a page they reduce accessiblity of screen readers, makes code harder to write, maintain, and debub, and they're not automatically responsive so tehy don't default to parent width, but rather size according to content.
  
< td > table data is the table cell, smallest container inside a table
  
< tr > table row, defines a table row and allows the addition of more rows
  
< th > table header, allows column and row headings to stand out
  
## Constructors

A constructor is a function called using a new keyword that will create a new object, bind 'this' to the new object, run the code in the constructor and returns the new object.  The advantage is that devs won't have to input every single obect every single time using object literal; multiple objects can be made without reinputing similar data constantly.
  
## Prototype
  
*Will have to revisit this question*
  
[prototype](https://ui.dev/beginners-guide-to-javascript-prototype)

## Personal notes and observations

[HTML table basics MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

### Things I want to know more about
  
[advanced html table](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## In class notes:

Object is a storage container for key value pairs.  Constructor functions are functions that create objects. The function defines the sahpe (the properties on the object).  The parameters represent values.

Items that are different go in the constructor.

Items that are the same go in the prototype.

Almost 2 hour mark for adding dynamic objects (useful example)

Object - single data thing, contains values organized by "key".  Key is how to find the value.  Anything can be a value.
Constructor Functions - something (function) that produces objects => storage containers for key value pairs
Prototype - an object shared by all objects that are produced from the constructor, separate object that tells what other objects from the constructor will share.
