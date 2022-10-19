# Passing Functions as Props

## Why this is important:



## Lists and Keys

1.  .Map () returns a new array that has a function applied to the variables.

2.  By using a curly braces {}, example below from [Reactjs.org](https://reactjs.org/docs/lists-and-keys.html)
 
const numbers = [1, 2, 3, 4, 5];

const listItems = numbers.map((number) => 

  < li> {number}  < /li>
  
 );
 
3.  key

4.  Keys identify which items have changed, added, or removed so React can identify them; creates a stable identity.

## Spread Operator

1.  The spread operator is an ellipsis (three dots ...)

2.  Adding items to an array, combining arrays, combining objects, and spreading an array into a function's arguments.

#### Combining two arrays

3. const bestArr = ['Army', 'Navy']

const mediocreArr = ['Marines', 'Coast Guard', 'Air Force']

const militaryArr = [...bestArr,...mediocreArr]

console.log (...militaryArr) would produce Army, Navy, Marines, Coast Guard, Air Force

#### Adding a new item to an array 

4. const animals = ['rabbit', 'cat', 'dog']

const moreAnimals = ['pig', 'horse', ...animals]

console.log (moreAnimals) would produce ['pig', 'horse', 'rabbit', 'cat', 'dog']
 
#### Combining two objects copied from [Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
 
5. const objectOne = {hello: "🤪"}

const objectTwo = {world: "🐻"}

const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }

const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}

objectFour.laugh() // 😂😂😂😂😂

## Video: Passing Functions Between Components

1.  Create the function where the state is that we want to change.

2.  The increment function passes through each index in the people array, if the name matches the name clicked then increases its count by 1.

3. In the parent component the method is passed down to the person object by including it inside the person object.  In the child component include a function for increment and include in it this.props.increment(this.props.name).  This is because the name is already being sent as part of the component previously created.

4.  By using props in the child components method. this.props.increment()

## Things I Want to Know More About



