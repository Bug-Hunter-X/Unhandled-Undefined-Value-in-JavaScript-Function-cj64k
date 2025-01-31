# Unhandled Undefined Value in JavaScript Function

This repository demonstrates a common but easily overlooked error in JavaScript: not explicitly handling undefined values.  The `foo` function correctly handles `null` but fails to account for `undefined`, leading to a `TypeError`.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version that explicitly checks for and handles `undefined`. This highlights the importance of robust input validation in JavaScript functions to prevent unexpected errors.