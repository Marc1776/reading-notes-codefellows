# Class 13 Storage

## Local storage and how to use it on websites

Developers use local storage for web applications to reduce loading times of their page, because the information is already on the user's machine.  It also reduces the number of times a site has to actually pull the information to send fully to a user's machine.

The implication from reading the article and evercookie is that a user's personal information should not be stored locally where it can be accessed whenever.

Local storage only stores strings, it would require the use of JSON.stringify() and JSON.parse() in order to convert an object.

EX: var car = {};

car.wheels = 4;

car.doors = 2;

car.sound = 'vroom';

car.name = 'Lightning McQueen';

console.log( car );

localStorage.setItem( 'car', JSON.stringify(car) );

console.log( JSON.parse( localStorage.getItem( 'car' ) ) );

## Things I want to know more about

I wasn't super thrilled with the resource being 12 years old, but it does raise some interesting questions.  In the current day, a lot of data useage is unlimited, but in Alaska, it is not, so I can really see how using a local storage host would make much more sense than constantly re-sending all the information, especially for frequented sites.  I am curious how this plays out with the security concerns, spam, and scammers.
