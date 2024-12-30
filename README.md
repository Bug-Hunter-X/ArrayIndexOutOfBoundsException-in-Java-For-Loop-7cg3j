# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException` caused by an off-by-one error in a `for` loop.

The `bug.java` file contains the buggy code.  The `bugSolution.java` file provides the corrected version.

The bug is in the `for` loop where it iterates one element beyond the array's valid indices. This results in an `ArrayIndexOutOfBoundsException` when the program attempts to access a non-existent element. The solution shows how to fix this error by correctly using the `<` operator to iterate within the bounds of the array.