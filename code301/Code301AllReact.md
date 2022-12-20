# Putting it all together

## Why it's important:

Thinking in React really helps to provide a structure moving forward for building in React.  Previous to this, I felt like I was just putting things places and hoping the parent-child relationship was what I thought it was.

## Thinking in React

1.  A component (like functions or objects) should only do one thing and should be broken into subcomponents if it grows.

2.  A static version renders the data model, but only uses props, state and interactivity is not used.

3.  Determine which data needs it's own state, the data that updates or changes.

4.  Determining state:
    - Is it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.
    - [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

5.  Identifying where state should live:
    - Identify every component that renders something based on that state.
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).
    - Either the common owner or another component higher up in the hierarchy should own the state.
    - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
    - [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

## Higher-Order Functions

1.  > Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.  [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

2.  Line 2 is returning whether or not m is greater than n by evaluating m against n.

3.  Map actually iterates a function over each individual element in an array and changes them to something new in a new array.  So a function can create an array while mapping would then adjust that array to final product.

## Things I want to know more about:

Higher-order Functions seems kind of asbstract at the moment, hoping that some class discussion and examples will clear it up a bit more.

## Personal Notes

Components, like functions or objects, should have a single responsibility, ie do one thing.  If it grows, reduce it into smaller subcomponents.

In smaller projects its easier to build top-down in terms of parent-child components.  Versus on larger products it is easier to write components from bottom-top and write test whild building.

### Reference Links

[THinking in React](https://reactjs.org/docs/thinking-in-react.html)

[Higher Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

