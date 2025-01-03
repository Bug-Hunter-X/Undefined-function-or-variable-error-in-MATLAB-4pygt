# Undefined function or variable error in MATLAB

This repository demonstrates a common error in MATLAB: the "Undefined function or variable" error. This error typically occurs when MATLAB cannot find a function or variable that you're trying to use.  The cause can be a simple typo, a missing file, or an incorrect path.  This example shows how to reproduce and solve this issue.

## Bug
The `bug.m` file contains a function definition and its call. The script attempts to execute before the function is defined, causing the error.

## Solution
The `bugSolution.m` file demonstrates the corrected code.  The solution ensures the function is defined before its invocation.