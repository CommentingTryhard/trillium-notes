# Compilers & Interpreters
**Compiler:** Translates the entire source code into machine code before running the program. The machine code is stored and reused, making execution faster. Errors are detected before running the program.

**Interpreter:** Translates the source code line by line while the program is running. The translation is done on-the-fly, making it easier to test and debug. Changes take effect immediately.

Differences between compiler and interpreter:

|     |     |     |
| --- | --- | --- |
| **Feature** | **Compiler** | **Interpreter** |
| Speed | Faster execution as translation is done once | Slower execution as translation is done on-the-fly |
| Error Detection | Detects errors before running the program | Errors are detected during runtime |
| Usage | Ideal for production code | Ideal for testing and debugging |
| Flexibility | Less flexible as recompilation is needed for changes | More flexible as changes take effect immediately |

Error Types:

*   **Syntax Error:** A syntax error occurs when the source code does not follow the rules of the programming language.
*   **Logic Error**: A logic error occurs when the source code has issues with its algorithm.
*   **Arithmetic Error:** Cannot calculate leading to error

**Variable:** A named storage that can hold a value which may change during the execution of the program.

**Constant:** A named storage for a value that remains unchanged during the execution of the program.

**Solution:** A Boolean data type (bool) is suitable because it can represent two values: True (on) and False (off).