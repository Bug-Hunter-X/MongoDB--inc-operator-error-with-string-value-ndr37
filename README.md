# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value. However, if a string value is provided, it will result in an error.

## Bug Description
The provided code snippet attempts to increment the `count` field by the string value "10".  This will lead to an error because `$inc` expects a number. 

## Solution
The solution is to ensure that the value passed to the `$inc` operator is a number. The updated code snippet demonstrates the correct usage.