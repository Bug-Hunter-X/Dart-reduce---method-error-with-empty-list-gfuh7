# Dart reduce() method error with empty list

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element to operate correctly.  Attempting to use it on an empty list will result in a runtime exception.

The `bug.dart` file shows the problematic code. The `bugSolution.dart` file provides a solution to handle this edge case.

## Solution

The best solution is to check if the list is empty before calling `reduce()`. If it is empty, return a default value or handle the case appropriately, preventing the exception.