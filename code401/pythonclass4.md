# Classes, Objects, Thinking Recursively, Pytest

## Why this matters

## Classes and Objects

> Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects. [Definitions](https://www.learnpython.org/en/Classes_and_Objects)

Self can be thought of as 'this' from js.

## Thinking recursively

Taking a problem and breaking it into smaller chunks and solving the smaller chunks to eventually build out solving the whole problem. [Santa example 1/4 down](https://realpython.com/python-thinking-recursively/)

> Definition: A recursive function is a function defined in terms of itself via self-referential expressions.This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts: base case and recursive case. [Definition](https://realpython.com/python-thinking-recursively/)

Taking the results of one operation and adding it to the next operation, until everything has been exhausted.

## Pytest

Fixtures having objects that contain data you want to share across tests and you want them available to all tests

Under the hood, a fixture is a function, executing every time a test invokes the fixture. (can make calculations and decisions)

Coverage is used to help cover the many different paths through code.  Writing x test for x functions doesn't mean all the possible paths have been covered.

packaged called pytest-cov PyPI, invoked with --cov (add an argument so it doesnt run all the things, like this --cov=myprogram .) Followed by coverage html to make the report readable [Using coverage, bottom of page](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)

the report will indicate a path not covered

### Things I want to know more about

### References or links

[Learn Python](https://www.learnpython.org/en/Classes_and_Objects)
