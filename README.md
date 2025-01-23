# Lua Default Argument Pitfall

This repository demonstrates a subtle bug that can arise when using default arguments in Lua functions, particularly when dealing with `nil` checks.  The `bug.lua` file contains code exhibiting the problem, while `bugSolution.lua` provides a corrected version.

The core issue lies in Lua's handling of `nil` values and the order of default argument assignments.  A naive implementation may lead to unexpected results under certain conditions, as highlighted in the example code.

The solution involves restructuring the logic to handle default arguments more robustly, preventing unexpected behavior and ensuring the intended functionality is achieved.