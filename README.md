This repository demonstrates a common, yet subtle, error in Node.js: unhandled errors within an HTTP server.  The `bug.js` file shows a server that can crash without any informative error messages in the console if an unexpected error occurs. The `bugSolution.js` file shows how to correctly handle errors to prevent silent crashes and provide more useful debugging information.

This type of bug can be especially difficult to debug in production environments as it offers no clues as to the cause of the failure.