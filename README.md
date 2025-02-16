# Dart Null Safety Gotcha: Unexpected Behavior with Getter and Setter

This example demonstrates a potential unexpected behavior when using null-aware operators with getters and setters in a Dart class under null safety.

The `bug.dart` file contains code that initializes an optional integer variable to `null`. The getter uses the null-aware operator (`??`) to return 0 if the variable is null, otherwise, it returns the variable's value. The setter simply assigns a value to the variable. The `main` function demonstrates the usage and the unexpected behavior (it may not be completely clear at first glance). 

The `bugSolution.dart` provides a corrected implementation.