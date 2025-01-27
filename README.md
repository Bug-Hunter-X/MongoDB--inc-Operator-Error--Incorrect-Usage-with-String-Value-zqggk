# MongoDB $inc Operator Error: Incorrect Usage with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB: attempting to increment a field by a non-numerical value.  The `$inc` operator is used to increment a numerical field by a specified amount. Using a string value results in an error.

## Bug
The provided `bug.js` file shows incorrect usage of the `$inc` operator, attempting to increment the `field` by the string 'abc'.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator, providing a numerical value to increment the `field`.

## How to reproduce
1. Install MongoDB.
2. Run `bug.js` and observe the error.
3. Run `bugSolution.js` to see the correct implementation.