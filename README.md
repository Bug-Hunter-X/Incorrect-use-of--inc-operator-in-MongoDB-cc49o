# Incorrect use of $inc operator in MongoDB

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value.  However, attempting to increment with a string value will result in an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  Instead of providing a numerical value, a string is used, causing a type error.

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is a number. Using a numerical value instead of a string fixes the problem.
