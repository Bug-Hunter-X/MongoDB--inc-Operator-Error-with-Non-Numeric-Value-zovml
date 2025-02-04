# MongoDB $inc Operator Error with Non-Numeric Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numeric field by a specified value.  However, if a non-numeric value is provided, an error will occur.

## Bug Description
The bug arises from attempting to increment a numeric field using a non-numeric value with the `$inc` operator.  This results in a database error. The provided code snippet shows the incorrect usage of the operator.

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is a numeric type (integer or decimal). This corrected code demonstrates the proper usage.
