# Type Error in TypeScript Function Parameter

This example demonstrates a common type error in TypeScript that occurs when passing an array to a function expecting a string.  The function `greeter` is designed to take a single string and concatenate it to a greeting.  However, when an array of strings is passed as an argument, a type error results because TypeScript's type checker correctly identifies that an array is not a string.

## How to reproduce

1. Save the code in `bug.ts`
2. Compile the code using the TypeScript compiler (tsc bug.ts)
3. Observe the compilation error message indicating the type mismatch.

## How to solve

The solution involves either modifying the function's type signature to handle arrays or changing the way the array is passed to the function.  See `bugSolution.ts` for both approaches.