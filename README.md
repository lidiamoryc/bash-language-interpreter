# Bash-like language interpreter 

This project is an interpreter for a custom programming language, developed using Python and the ANTLR4 library to handle parsing based on a comprehensive grammar specification.

The language supports a variety of data types and structures. Here are some of the key features:

- Variable Declarations: Supports string, integer, boolean, and array types.
- Operations: Includes basic arithmetic operations with correct order of operations.
- Control Structures: Conditional statements with logical operations. Loop constructs including for and while.
- Functions: Function definition and invocation capabilities. Supports arguments and recursive calls.
- Echo Statements: Outputting expressions and variable values.

Example Usage:
```
int_var x = 5;
string_var y = "Hello, World!";
echo x;  # Outputs: 5
echo y;  # Outputs: Hello, World!

if [x == 5] then echo "x is five"; else echo "x is not five"; fi
```
