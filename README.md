# MongoDB $inc Operator Type Error
This example demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical value.  Using a string instead of a number results in an error.

## Bug
The provided code uses the `$inc` operator with a string value ("1") instead of a numerical value (1). This will result in an error.

## Solution
The corrected code uses the numerical value 1 to increment the counter, resolving the error.