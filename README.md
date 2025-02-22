# Uninitialized Property Access in C#

This repository demonstrates a common error in C#: accessing a property before it has been initialized.  Uninitialized properties can lead to unexpected behavior, such as exceptions or incorrect calculations.  The `bug.cs` file shows the problematic code, and `bugSolution.cs` provides a solution.

## Bug
The `bug.cs` file contains a class with a property `MyProperty` and a method `MyMethod`.  `MyMethod` attempts to use `MyProperty` before it's been given a value, which can result in an unpredictable outcome depending on the property's type and the program's runtime.

## Solution
The `bugSolution.cs` file demonstrates how to fix this by ensuring the property is properly initialized before use, either through a constructor or by setting a default value. 