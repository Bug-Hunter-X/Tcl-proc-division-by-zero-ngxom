# Tcl Proc Division by Zero

This repository demonstrates a common error in Tcl: division by zero within a procedure.  The `bug.tcl` file contains code that can cause a runtime error if the first argument is zero.  The `bugSolution.tcl` file provides a corrected version with proper error handling.

## Bug Description
The `badproc` procedure in `bug.tcl` fails to handle the case where the first argument (`a`) is zero, leading to a division by zero error. 

## Solution
The solution in `bugSolution.tcl` adds error handling to explicitly check for `a` being zero before performing the division.  If `a` is zero, it returns an error message instead of causing a runtime crash.