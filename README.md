# Unexpected Output in setTimeout Loop

This repository demonstrates a common issue in JavaScript involving closures and the `setTimeout` function within loops.  The example showcases how the expected behavior of logging numbers 0-9 with a 1-second delay can fail to achieve this due to how JavaScript handles variable scoping and closures.

The `bug.js` file contains the problematic code.  The `bugSolution.js` file provides a corrected version demonstrating how to solve this closure issue using an immediately invoked function expression (IIFE).