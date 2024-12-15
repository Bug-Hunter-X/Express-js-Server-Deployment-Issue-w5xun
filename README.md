# Express.js Server Deployment Issue

This repository demonstrates a common issue encountered when deploying Express.js applications to a production environment. The server runs perfectly locally, but fails to start after deployment.

## Bug

The `server.js` file contains the basic Express.js setup. The issue lies in how the server handles port binding and environment variables in a production setting.

## Solution

The `server-fixed.js` file provides a solution to this problem by dynamically selecting a port and using environment variables more robustly.

## Setup

1. Clone the repository
2. Navigate to the directory
3. Run `npm install`
4. Run `node server.js` (for the buggy version)
5. Run `node server-fixed.js` (for the fixed version)