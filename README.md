# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion and the '+' operator.  When adding a number and a string in JavaScript, the '+' operator performs string concatenation instead of numeric addition. This can lead to unexpected results and difficult-to-debug issues.

## Bug Description
The `foo` function attempts to add two values. However, because one input is a number and the other a string, JavaScript implicitly converts the number to a string and concatenates the two strings. This is a common source of errors.

## Solution
The solution involves explicitly converting the input to numbers before performing the addition, thereby avoiding the unexpected type coercion.