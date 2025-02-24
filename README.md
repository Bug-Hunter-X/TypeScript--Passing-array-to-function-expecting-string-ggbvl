# TypeScript Bug: Passing Array to String Function

This repository demonstrates a common TypeScript error: passing an array to a function that expects a string.  The bug occurs because the `greeter` function is explicitly typed to accept a single string argument, while an array is passed.

The solution demonstrates how to correctly handle this scenario, either by modifying the function signature to accept an array or by iterating over the array and calling the function for each element.

## How to Reproduce
1. Clone this repository.
2. Open `bug.ts`.
3. Run `tsc bug.ts` and then `node bug.js`. You'll see a compilation error because the array is being passed into the function expecting a string.

## Solution
The solution is provided in `bugSolution.ts`