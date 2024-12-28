# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs because the loop condition `i <= arr.length` causes the loop to access an index beyond the array's bounds, leading to an `ArrayIndexOutOfBoundsException`.  The solution shows how to correctly iterate within the array's valid indices.