# VHDL Counter Bug
This repository demonstrates a common error in VHDL code related to handling integer ranges in counters.  The provided `bug.vhdl` file contains a counter that does not correctly wrap around when it reaches its maximum value. The solution, `bugSolution.vhdl`, illustrates the corrected implementation.

## Bug Description
The original VHDL code exhibits unexpected behavior when the counter reaches its maximum value (15). The counter fails to wrap around correctly, potentially leading to errors in the overall design.

## Solution
The corrected code ensures the counter properly wraps around from 15 back to 0. This is accomplished by using the mod operator to guarantee proper range handling.