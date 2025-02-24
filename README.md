# Missing Error Handling in Express.js Route Handler

This repository demonstrates a common error in Express.js applications: insufficient error handling within route handlers.

The `bug.js` file shows an Express.js route that fetches user data.  If the user is not found, it returns a simple 'User not found' message.  However, it lacks robust error handling for database-related issues (e.g., connection errors, query failures).

The `bugSolution.js` file provides a corrected version with improved error handling using try...catch blocks and more informative error responses.