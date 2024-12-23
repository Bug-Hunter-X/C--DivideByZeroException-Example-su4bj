# C# DivideByZeroException Example

This repository demonstrates a common runtime exception in C#: the `DivideByZeroException`.  The `bug.cs` file contains code that attempts to divide by zero, resulting in this exception.  The solution, found in `bugSolution.cs`, shows how to prevent this error using proper error handling.

## How to reproduce

1. Clone this repository.
2. Compile and run `bug.cs`. You should see an unhandled exception.
3. Run the `bugSolution.cs` file to see the corrected version with error handling.

## Learning Points

* Always validate inputs before performing divisions.
* Use `try-catch` blocks to gracefully handle potential exceptions.
* Understand common runtime exceptions in your chosen programming language.