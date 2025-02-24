# Handling Null Values in JavaScript

This repository demonstrates a common error in JavaScript: unexpected behavior when handling null values in functions. The `bug.js` file shows the initial code with the error, while `bugSolution.js` provides the corrected version.

## Bug Description

The `foo` function attempts to add two numbers. However, it doesn't explicitly handle cases where one or both input parameters are null. This leads to unexpected results or errors.

## Solution

The solution involves adding a check at the beginning of the function to handle null values. The corrected version returns null if either input is null, ensuring the function behaves as expected.