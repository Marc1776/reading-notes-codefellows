# Ten Thousand Game 1

## Why this matters

## Random Module

Allows dev to generate random numbers and access functions that support several operations.

Can randomize picking a number in a range, card from a deck, element from a list, create random strings.

randint() takes 2 numbers as input argument, first as the start of the range and second as the end of the range; when executed a random integer in the range is returned.  Key notes:  first integer must be less than the second.  Ex:  

```python
import random
print random.randint(0,5)
```

random()  creates and returns a random float number between 0 and 1.  Multiply by 100 to get a larger number.

```python
import random
random.random() * 100
```

choice()  returns a random element from an input collection object: list, set, tuple  Ex::

```python
#will return a color
random.choice(['red', 'black', 'green])  
#or
import random
myList = [2, 109, False, 10, "Lorem", 482, "Ipsum"]
random.choice(myList)
```

shuffle()  elements of a list are shuffled and returned in a new list

```python
x = [[i] for i in range(10)]
shuffle(x)
#output:
#[[9], [2], .....etc thru 10 indeces]
```

randrange()  selects a random element from a range, 3 numbers as input start, stop, step.  Acts like a combo of choice() and range()

```python
random.randrang(start, stop [, step])

import random
for i in range(3):
  pring random.randrange(0, 101, 5)
  ```

## Risk analysis

## Test coverage

### Things I want to know more about

### Links and references
