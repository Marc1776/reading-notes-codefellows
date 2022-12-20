# Code 201 class 6 Problem domain, Objects, and DOM

## JS object basics

I would describe an object as a spare room, I can put whatever I need in it, I can continuously add to it and it won't interfere with other aspects of my house.

Object literals are good when only creating one object which, when transferring, is much more efficient than sending several items to a server for example.

Objects map strings to values, where arrays map numbers to values.  Arrays are single objects that contain multiple values, and that's the end, obejcts can contain multiple variables and functions.

Dot notation cannot be used if an object property name is defined at run time, to access the value you need bracket notation.

'This' is a keyword referring to the current object code is being written in.  Using 'this' allows us to create more than one object literal while using the same method definition for each object created.

## DOM

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page. [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

DOM is not a programming langue, while JS is, however documents can be manipulated and accessed through the DOM and JS together.  The DOM gives JS a model of web pages, HTML documents, SVG documents and components.  

### Personal notes/observations

name value pairs written name:"value"

Inside an object, variables and functions are called properties and methods.

The data, numbers or array are the properties and functions are methods

[JS Object example](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

Objects allow us to store information and prevents information from clashing with other variables and functions.

[Problem DOmain](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)

[Primitive values vs Object references in JS](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

### Things I want to know more about

Using an object vs an array.
Extremely loose understanding of the DOM

### In class notes

Re-visit warm up for some HTML/CSS practice

let person = {
name: 'Marc',
age: 38,
hobbies: ['skateboarding', 'video games'],
greet: function () {
console.log('Hello.');
 },
 // contextual 'this' keyword
 sayName: function () {
 // in a metho 'this' refers to the object that the method is attached to.
   console.log('My name is' + this.name);
   }
};

person['name']; // reading the value, stored at the key: 'name'

let people = [person];

console.log(people[0], person['hobbies'][0]);

person.greet();
person.sayName();

C - create
R - 
U - Update
D - Delete
