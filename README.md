# Express.js Route Handler Error
This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The `bug.js` file contains code that attempts to fetch a user by ID, but lacks validation and error handling for non-numeric IDs. This can lead to crashes or unexpected behavior.

The `bugSolution.js` file provides a corrected version of the code that includes input validation and proper error handling.