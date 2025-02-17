# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The `BuggyArraySum.java` file contains code that attempts to sum the elements of an array but incorrectly includes an index beyond the array's bounds. This leads to an `ArrayIndexOutOfBoundsException`. The `FixedArraySum.java` file provides the corrected code.

The error is a classic example of an off-by-one error; the loop condition should be `i < arr.length` instead of `i <= arr.length` to avoid accessing an element outside the array's valid indices.  This is a frequently encountered bug in programming, particularly when dealing with array indices and loops.