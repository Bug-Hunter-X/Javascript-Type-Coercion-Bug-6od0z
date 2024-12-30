# Javascript Type Coercion Bug
This example demonstrates a common issue in Javascript related to type coercion.  When adding numbers and strings, Javascript will implicitly convert the numbers to strings and perform string concatenation instead of numeric addition.

The `bug.js` file contains the buggy code, and `bugSolution.js` provides a corrected version using explicit type checking.

This is a common source of unexpected behavior, especially when dealing with user input or data from external sources.