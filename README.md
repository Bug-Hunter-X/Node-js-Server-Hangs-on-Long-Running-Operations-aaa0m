# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js where long-running operations in request handlers can block the event loop, causing the server to become unresponsive.  The `server.js` file shows the problematic code.  The solution is provided in `server-solution.js`, illustrating how to avoid this problem by using asynchronous operations or worker threads.