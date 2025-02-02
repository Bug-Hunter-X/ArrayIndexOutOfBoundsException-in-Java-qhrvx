# ArrayIndexOutOfBoundsException Bug in Java
This repository demonstrates a common Java programming error: an ArrayIndexOutOfBoundsException.  The provided code attempts to access an array element beyond its defined size, resulting in a runtime exception.  A solution is also provided to fix the issue.

## Bug Description
The Java code in `Bug.java` contains a `for` loop that iterates one element past the end of the array.  This causes an `ArrayIndexOutOfBoundsException` when attempting to assign a value to `arr[5]` while the array's valid indices are 0 through 4.

## Solution
The corrected code in `BugSolution.java` modifies the loop condition to prevent accessing an invalid array index.  The loop condition `i < arr.length` ensures that the loop terminates before reaching the invalid index. 
