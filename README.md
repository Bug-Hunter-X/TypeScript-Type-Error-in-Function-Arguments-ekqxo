# TypeScript Type Error in Function Arguments

This repository demonstrates a common TypeScript error: type mismatch in function arguments. The function `add` expects two numbers, but the code calls it with a string as the second argument, resulting in a type error.

## Bug

The `bug.ts` file contains the erroneous code.  The type mismatch leads to a compilation error preventing the code from running.

## Solution

The `bugSolution.ts` file provides a corrected version.  It ensures that both arguments passed to `add` are numbers, resolving the type error.

This example highlights the importance of type safety in TypeScript and demonstrates how type checking helps catch potential runtime errors during compilation.