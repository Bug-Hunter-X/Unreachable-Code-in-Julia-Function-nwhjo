# Unreachable Code in Julia

This repository demonstrates a simple example of unreachable code in a Julia function.  The `return 0` statement in `myfunction` is never reached because the `if` and `else` blocks handle all possible conditions (x > 0 or x <= 0).  The solution demonstrates how to remove the unreachable code for better code clarity and efficiency.