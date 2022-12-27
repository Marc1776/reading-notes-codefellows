# Linked List

## Why this matters

## Big O

Describes worst case efficiency of an algorithm measured in following 4 areas:  

1. input size:  size of parameter values read by the algorithm (if a list is used, the higher number of elements in that list will increase the input size)

2. units of measurement:  

   - Time measured in milliseconds, operations (number of lines of code executed from start to finish of a function) and 'basic operations' (operation that contributes the most to the toal run time)

   - Space needed to hold the actual algorithm, amount of space to hold input data, output data, and amount of space needed to hold the 'working space' during calculation

3. orders of growth: representation of the increase in running time or memory space

## Linked Lists

    "Linked List - A data structure that contains nodes that links/points to the next node in the list.

    Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.

    Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.

    Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.

    Next - Each node contains a property called Next. This property contains the reference to the next node.

    Head - The Head is a reference of type Node to the first node in a linked list.

    Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list."[Terminology](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

Cannot use a for loop or foreach to traverse a linked list, we use the Next value in each node to go to the next reference.  

Best to use a while loop, allows us to check the Next value to see if it's null.  Traversing a null node will crash the program with a NullReferenceException.

Current variable tells us where we are in the linked list