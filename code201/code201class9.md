# Class 09 Forms and JS Events

## HTML Forms

Forms matter because instead of having users input reponses into endless and cycling alerts, it can be done all at once in one place.

Events allow me to hold off on functions until they're called by the user.

[MDN Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

Forms are important because they are a main point of interaction between a site and its user.  When the user inputs data, that information can be processed and stored or immediately used to make the page more relevant to that user.

When designing a form, as with other site designs, the first thing is to sketch it out so that you know what kind of data you are trying to get from the user.  To minimize frustration, get the least amount of input as is needed.  

< form > defines the form and is a container element like section but specifically for containing forms.

< label > provides text for the names the input fields

< input > defines how the input element appears and behaves (< input type="email" designates this to only accept an email address), empty element no closing tag.

< textarea > is a multi-line text field

< button > allows the user to do something by simply clicking the element on the page, submitting or resetting.

## JS Events

To a non-technical friend:  an event is something that happens in the system I'm programming and the system tells me so that my code can react.  Example: you click a button on your amazon to 'buy now', that is an event that tells the amazon site programming code to change pages and bring up the checkout forms.

addEventListener( ) method needs the following two arguments: the name of the event and a function to handle that event.

Event objects: is inside an event handler function and is automatically passed to event handlers to provide more features and information.  The target is useful because it is always a reference to the element the event occurred upon.

Event bubbling is when all the elements trigger a click event, ex: a button is clicked, the button fires first, then the parent in the div, then the parent in the body, bubbling up from the innermost element, the button in this case.

Event capturing is when the browser works from the outside in to reacth the most direct parent of the element that was clicked, starting at < html > and working down.

### Things I want to know more about

I understand why bubbling can be bad, but I really need to see it work.
