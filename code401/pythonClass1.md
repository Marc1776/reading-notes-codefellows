# Class 1 reading

## Why this matters

The whole modular learning process has been pain and suffering, but hopefully I can reframe my thoughts a bit better and have less suffering.  

Big O Notation should be able to help identify how an algorithm is working within code, as more and more code is written, taking into account how much space is being used and how much machine performance is required can help developers write more efficient code.

## Pain and Suffering

What I took away here was that the knee-jerk mental reaction to something bad or annoying happening actually makes the situation worse.  The thoughts of 'I can't believe that just happened' or 'why me?' and so on just embeds the bad situation further into my brain which increases the amount of time I need in order to move past the event.  Like today, I realized I'm missing some prework assignments, my initial reaction is to kick myself for not being on top of things, but here I am so what I need to do is accept past me screwing up and plan for future me to make up for it.  I also feel like this is foreshadowing this class.  

## Beginner Big O

> "Big O notation is used in Computer Science to describe the performance or complexity of an algorithm. Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm." [Big O notation](https://robbell.io/2009/06/a-beginners-guide-to-big-o-notation)

O(1) will always execute in same time or space

O(N)  grows linearly and in direct proportion to the size of input data

O(N^2) (N squared) algorithm performance is drectly proportional to the squared size of the input data

O(2^N)  algorithm whose growth doubles with each addition to the input data set

O(log N) algorithm that halves the data search as it searches.  Binary search ex:  where a target value is compared against the middle element of a data set if the value matches, search complete.  If the search is higher or lower than the middle element, it will then search the upper or lower half of the data set in the same manner by starting at the middle element of the upper or lower half of data.  This continues until the value is found or it can no longer split the data.

## Names and Values in Python

Names refer to values (x = 23): x refers to 23

Many names can refer to one value (y = x) both y and x refer to the value 23

Names are reassigned indepedently  ((following above examples by adding on))  (x = 12)  now x refers to the value 12, but y still refers to value 23.  Changing x doesn't change y

Values live until no references.  If x = 2, then later down the code I reassign x = 3, the value of 2 is no longer accessible because the name has been reassigned and there is no name referencing 2.

Assignment never copies data:  nums = [1,2,3], other = nums.  There are two names refering to the list 1, 2, 3, but there is only 1 list.  This is why if we .append nums to add a four so the list becomes 1, 2, 3, 4, then using the name other, it will produce the list 1, 2, 3, 4 thus changes are visible through all names.

### Things I'd like to know more about

Big O, I've heard of it, but other than this simple break down, I know nothing.

### References

[python tutor](https://pythontutor.com/)

[Awesome python environment](https://towardsdatascience.com/how-to-setup-an-awesome-python-environment-for-data-science-or-anything-else-35d358cc95d5)

[Python module of the week](https://pymotw.com/3/index.html)
