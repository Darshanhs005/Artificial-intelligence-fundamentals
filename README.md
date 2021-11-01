# Artificial-intelligence-fundamentals
## Solving the Towers of Hanoi Problem using State Space Search

Among many classic AI problems is the Towers of Hanoi problem; one of many versions of this, forms the basis of this assignment and is told as follows:

In a monastery in the deepest parts of Tibet there are three crystal columns and 64 golden rings. The rings are different sizes and rest over the columns. At the beginning of time, all of the rings rested on the leftmost column, and since then the monks have toiled ceaselessly trying to perfectly transfer the rings to their resting place on the final column.

The objective of this problem is to move the entire stack of rings from the first, to the last column, while obeying 3 simple rules:

1.	Only one ring can be moved at time.

2.	Each move consists of taking the upper ring from one of the stacks and placing it on the top of another stack or an empty pole.

3.	A larger ring must not be placed on top of a smaller ring.
## This file must contain:
    •	A function containing your Breadth-First Search implementation;

    •	A function containing your A* Search implementation;

    •	A correct representation of the problem state, indicating all variables required to solve the problem;

    •	The ability to switch between both search algorithms without major modification to any part of the code.

As well as correctly solving the problem, your code must display good programming style:

    •	appropriate function and parameter naming;

    •	appropriate and consistent documentation;

    •	appropriate use of Classes;

    •	appropriate and consistent indentation that reflects logical structure of the code.
    

## Expected Output
The output of your program must be a count of the total number of steps taken to reach the solution; and a path list, showing the rings positions at each level of the search. E.g.:


Path Output:

    [5, 4, 3, 2, 1], [0], [0]
    
    [5, 4, 3, 2], [1], [0]
    
    [5, 4, 3], [1], [2]
    
    …
    
    [0], [0], [5, 4, 3, 2, 1, 0]

Steps Taken: 100
