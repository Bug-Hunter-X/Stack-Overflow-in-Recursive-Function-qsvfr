# Stack Overflow Bug in JavaScript

This repository demonstrates a common error in JavaScript: stack overflow due to uncontrolled recursion.

The `bug.js` file contains a recursive function that attempts to compute something, but doesn't handle large inputs correctly, leading to a stack overflow.

The `bugSolution.js` file provides a corrected version that avoids the stack overflow by using iteration instead of recursion.