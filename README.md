# Unexpected Type Inference in TypeScript

This repository demonstrates a subtle bug related to type inference in TypeScript.  The `combine` function appears straightforward, but under certain conditions, TypeScript's type inference might not behave as expected, potentially leading to runtime errors or unexpected behavior.

The `bug.ts` file showcases the problem.  The `bugSolution.ts` file provides a solution demonstrating how to resolve the type inference issues. This is a common issue for developers to encounter, especially those new to TypeScript's type system and its intricacies.  Understanding type inference limitations in TypeScript is key to writing robust and reliable code. 