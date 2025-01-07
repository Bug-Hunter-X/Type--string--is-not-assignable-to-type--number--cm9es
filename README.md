# Type 'string' is not assignable to type 'number'

This repository demonstrates a common type error in TypeScript: `Type 'string' is not assignable to type 'number'`.  The error arises when a function expecting a number argument is called with a string.  This is a powerful feature of TypeScript as it prevents runtime errors by detecting these type mismatches during compilation. 

The `bug.ts` file shows the error. The `bugSolution.ts` file demonstrates how to fix the error by ensuring that the arguments passed to the function are of the correct type.

## How to Reproduce

1. Clone this repository.
2. Open `bug.ts` in a TypeScript compiler (like the one built into VSCode).
3. Observe the compilation error.

## Solution

The solution involves ensuring type safety.  You can use type guards or input validation to prevent incorrect types from being passed to the function.