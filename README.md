# Express.js JSON Body Parsing Error
This repository demonstrates a common error encountered when using Express.js to parse JSON request bodies. The issue arises when the request body is either empty or contains invalid JSON data.

## Bug Description
The provided Express.js application fails to correctly handle JSON requests if the body is empty or improperly formatted.  This can lead to unexpected behavior or errors in the application.

## Solution
The solution involves adding error handling to gracefully handle cases where the request body is invalid or empty.  This solution provides more robust error handling and prevents application crashes.