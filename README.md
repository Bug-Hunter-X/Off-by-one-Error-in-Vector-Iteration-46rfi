# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs when the loop condition `i <= vec.size()` is used, causing an attempt to access an element beyond the valid index range of the vector.

The `bug.cpp` file contains the erroneous code. The `bugSolution.cpp` file shows the corrected version.

**To reproduce the bug:**
1. Compile and run `bug.cpp`.
2. Observe the out-of-bounds access and potential crash or unexpected behavior.

**To see the solution:**
1. Compile and run `bugSolution.cpp`.
2. Notice the correct iteration and output.

This example highlights the importance of careful loop condition design when working with containers that have a defined size.