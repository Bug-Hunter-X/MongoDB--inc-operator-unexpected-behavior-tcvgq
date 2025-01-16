# MongoDB $inc Operator Unexpected Behavior

This repository demonstrates an issue with the MongoDB `$inc` operator, specifically concerning its use within update operations.  The provided `bug.js` file illustrates an incorrect application of the operator leading to unexpected results or errors.  The `bugSolution.js` file provides the correct implementation.

## Bug Description

The primary issue lies in how the `$inc` operator is used, potentially leading to unexpected increments or errors when dealing with specific scenarios involving data types or missing fields.  The solution provides a robust approach.

## How to Reproduce

1.  Ensure you have a MongoDB instance running.
2.  Create a collection and insert some documents.
3.  Run `bug.js`.
4. Observe the unexpected behavior.
5. Run `bugSolution.js` for the correct behavior.

## Solution

The corrected usage is detailed in the `bugSolution.js` file, addressing the potential pitfalls associated with the `$inc` operator.