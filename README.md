# MongoDB $inc Operator Error: Invalid Type

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value instead of a numeric value to the `$inc` operator.

## Bug Description
The bug is related to using the `$inc` operator in a MongoDB update operation.  The operator is designed to increment a numeric field by a specified value.  If you provide a string instead of a number, an error will occur.  This error can be difficult to catch because it might not be immediately obvious from the error message. 

## Solution
The solution is straightforward: use a numeric value (integer or float) with the `$inc` operator.