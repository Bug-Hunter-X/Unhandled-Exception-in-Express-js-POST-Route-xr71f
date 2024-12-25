# Unhandled Exception in Express.js POST Route

This repository demonstrates a common error in Express.js applications: unhandled exceptions arising from malformed or incomplete request bodies.  The `bug.js` file contains the flawed code, while `bugSolution.js` provides a corrected version.

The issue stems from directly accessing properties of the `req.body` object without proper error handling. If the request body is missing or contains unexpected data, this will result in an unhandled exception and the application will crash.

The solution involves comprehensive error handling to validate and sanitize the request body before further processing.  This prevents unexpected crashes and enhances the robustness of the application.