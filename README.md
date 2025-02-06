# Ada Array Index Out of Bounds Bug

This repository demonstrates a common error in Ada programming: accessing an array element outside of its defined bounds.  The bug involves an incorrect loop iteration that attempts to access an element beyond the array's last index, causing a runtime error.  The solution demonstrates the correct approach to ensure safe array access.

## Bug
The `bug.ada` file contains the erroneous code, where the loop attempts to access `My_Arr(I+1)`, which will cause an error on the last iteration. 

## Solution
The `bugSolution.ada` file provides the corrected code, demonstrating the correct method for iterating through the array without causing an index out of bounds error.