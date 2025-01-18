# Uncommon Assembly Code Errors

This repository demonstrates some uncommon errors that can occur in assembly code, specifically focusing on memory access violations and stack overflow/underflow issues.  The examples provided highlight potential pitfalls and offer solutions for improved code robustness and error handling.

## Errors Covered:

* **Memory Access Violations:** Incorrect memory addressing can lead to exceptions.  The code illustrates how improper use of registers (EBX, ECX, EAX) in addressing calculations can result in accessing invalid memory locations.
* **Stack Overflow/Underflow:**  Issues related to stack management, such as unbounded recursion or improper stack pointer manipulation, are demonstrated. 

## How to Use:

1. Clone the repository.
2. Examine the `bug.asm` file to see examples of error-prone code.
3. Review the `bugSolution.asm` file for corrected versions and explanations.
4. Compile and run the code (using an appropriate assembler and linker) to observe the results and understand the impact of these errors.