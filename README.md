# Lua Runtime Error: Arithmetic on String

This repository demonstrates a common runtime error in Lua caused by performing arithmetic operations on strings. Lua's dynamic typing allows this to compile without warnings but will result in a runtime error.

The `bug.lua` file contains the erroneous code, while `bugSolution.lua` provides a corrected version with robust type checking.