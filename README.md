# Uncommon JavaScript Error: Handling Undefined in Length Check

This repository demonstrates a common yet subtle error in JavaScript related to accessing the `length` property of an undefined value.  The `foo` function aims to return the length of an array or 0 if the input is null. However, it fails when given `undefined` as input.

The bug is in the lack of explicit handling for the `undefined` case. The solution introduces a check to handle undefined values gracefully.

## Bug
The original `bug.js` file contains the flawed function which throws a `TypeError` when called with `undefined`.

## Solution
The `bugSolution.js` file presents the corrected function which uses a more robust check to prevent the error.

This example highlights the importance of thorough input validation in JavaScript to avoid runtime errors.