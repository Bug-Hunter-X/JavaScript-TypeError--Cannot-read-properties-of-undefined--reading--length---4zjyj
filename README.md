# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: attempting to access the 'length' property of an undefined value.  The `bug.js` file contains code that throws a `TypeError` when an undefined value is passed to a function. The `bugSolution.js` file demonstrates how to handle the undefined case appropriately to prevent the error.

## How to Reproduce

1. Clone the repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` in your terminal.

You should see a `TypeError`. 

## Solution

The solution involves explicitly checking for undefined before attempting to access the `length` property.  See the corrected code in `bugSolution.js`.