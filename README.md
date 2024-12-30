# MongoDB $inc operator error with non-numeric value
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value.  However, if a non-numeric value is provided as the increment, it results in an error.

The `bug.js` file shows the incorrect usage, and `bugSolution.js` provides the corrected version.
