# Cryptic Error in Node.js Server Due to Improper Content-Type Header

This repository demonstrates a common yet subtle error in Node.js HTTP servers related to setting the `Content-Type` header. The improper setting can lead to unexpected behavior or cryptic errors in the client application.

## The Bug
The `bug.js` file contains a simple Node.js HTTP server.  The issue lies in how the `Content-Type` header is handled in the response. Although functional in this simple example, it lacks robustness and could cause issues with more complex applications.

## The Solution
The `bugSolution.js` file presents a corrected version. The fix involves ensuring the header is properly set, accounting for potential encoding issues or other scenarios that might cause problems. 

This detailed explanation and the provided code samples help highlight a potential pitfall in setting HTTP headers, leading to a more robust and reliable server.