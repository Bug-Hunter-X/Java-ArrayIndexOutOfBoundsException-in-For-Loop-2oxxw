# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException` occurring in a `for` loop that iterates one element too far. The faulty code attempts to access an array element at an index equal to the array's length, while valid indices range from 0 to length - 1.

## Bug Description
The `bug.java` file contains a `for` loop that iterates from 0 to `arr.length` (inclusive).  This causes an `ArrayIndexOutOfBoundsException` when the loop tries to access `arr[5]` in an array of size 5. 

## Solution
The corrected code in `bugSolution.java` fixes the loop condition to `i < arr.length`, ensuring that the loop only iterates through valid array indices.