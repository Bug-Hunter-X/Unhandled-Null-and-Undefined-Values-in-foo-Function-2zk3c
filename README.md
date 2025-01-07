# Unhandled Null and Undefined Values in foo Function

This repository demonstrates a common JavaScript bug involving the improper handling of `null` and `undefined` values in a function. The `foo` function does not explicitly check for these values before performing operations, leading to potential errors.

The `bug.js` file contains the buggy function, and `bugSolution.js` provides a corrected version that handles `null` and `undefined` values appropriately.

## Bug

The original function fails to handle `null` or `undefined` values for the `a` and `b` parameters. This might lead to runtime errors, unexpected behavior, or incorrect results.

## Solution

The solution adds explicit checks for `null` and `undefined` values, providing alternative behavior or error handling to mitigate the issue. This ensures the function is more robust and less prone to errors.