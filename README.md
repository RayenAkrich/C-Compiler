# C_compiler_class_project
This is a C compiler project for a university course. The project is designed to compile a subset of the C programming language. The compiler is implemented in C and generates x86-64 assembly code.
## Features
- Lexical analysis: The compiler can tokenize C source code into a stream of tokens.
- Syntax analysis: The compiler can parse the token stream and build an abstract syntax tree (AST).
- Semantic analysis: The compiler can perform type checking and other semantic checks on the AST.
- Code generation: The compiler can generate x86-64 assembly code from the AST.
## Requirements
- C compiler (e.g. gcc)
- x86-64 architecture
## Installation
1. Clone the repository: git clone https://github.com/RayenAkrich/c-compiler.git
2. Navigate to the project directory: cd c-compiler
3. Compile the compiler: make
## Usage
1. Write a C program in a file (e.g. program.c).
2. Compile the program using the compiler: ./compiler program.c
3. The compiler will generate an x86-64 assembly file (e.g. program.s).
4. Assemble the assembly file using an assembler (e.g. as): as program.s -o program.o
5. Link the object file using a linker (e.g. ld): ld program.o -o program
6. Run the program: ./program
## Limitations
- The compiler only supports a subset of the C programming language.
- The compiler does not support all C features, such as pointers, structs, and unions.
- The compiler may not handle all edge cases correctly.
## Contributing
Contributions to the project are welcome. Please fork the repository and submit a pull request with your changes.
## License
This project is licensed under the MIT License. See the LICENSE file for details.