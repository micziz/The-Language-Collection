# C

C is a general-purpose computer programming language. It was created in the 1970s by Dennis Ritchie, and remains very widely used and influential. By design, C's features cleanly reflect the capabilities of the targeted CPUs. It has found lasting use in operating systems, device drivers, protocol stacks, though decreasingly for application software, and is common in computer architectures that range from the largest supercomputers to the smallest microcontrollers and embedded systems.

**Creator**: Dennis Ritchie

**First appeared**:	1972; 50 years ago

**License**: ? Up to the implementation.

**Type**: Spec

## History

A successor to the programming language B, C was originally developed at Bell Labs by Dennis Ritchie between 1972 and 1973 to construct utilities running on Unix. It was applied to re-implementing the kernel of the Unix operating system. During the 1980s, C gradually gained popularity. It has become one of the most widely used programming languages, with C compilers available for almost all modern computer architectures and operating systems.

## Overview

C is an imperative procedural language supporting structured programming, lexical variable scope, and recursion, with a static type system. It was designed to be compiled to provide low-level access to memory and language constructs that map efficiently to machine instructions, all with minimal runtime support. Despite its low-level capabilities, the language was designed to encourage cross-platform programming. A standards-compliant C program written with portability in mind can be compiled for a wide variety of computer platforms and operating systems with few changes to its source code.

## Features

- The language has a small, fixed number of keywords, including a full set of control flow primitives: if/else, for, do/while, while, and switch. User-defined names are not distinguished from keywords by any kind of sigil.
- It has a large number of arithmetic, bitwise, and logic operators: +,+=,++,&,||, etc.
- More than one assignment may be performed in a single statement.
- Functions:
- Function return values can be ignored, when not needed.
- Function and data pointers permit ad hoc run-time polymorphism.
- Functions may not be defined within the lexical scope of other functions.
- Variables may be defined within a function, with scope.
- A function may call itself, so recursion is supported.
- Data typing is static, but weakly enforced; all data has a type, but implicit conversions are possible.
- User-defined (typedef) and compound types are possible.
- Heterogeneous aggregate data types (struct) allow related data elements to be accessed and assigned as a unit.
- Union is a structure with overlapping members; only the last member stored is valid.
- Array indexing is a secondary notation, defined in terms of pointer arithmetic. Unlike structs, arrays are not first-class objects: they cannot be assigned or compared using single built-in operators. There is no "array" keyword in use or definition; instead, square brackets indicate arrays syntactically, for example month.
- Enumerated types are possible with the enum keyword. They are freely interconvertible with integers.
- Strings are not a distinct data type, but are conventionally implemented as null-terminated character arrays.
- Low-level access to computer memory is possible by converting machine addresses to pointers.
- Procedures (subroutines not returning values) are a special case of function, with an untyped return type void.
- Memory can be allocated to a program with calls to library routines.
- A preprocessor performs macro definition, source code file inclusion, and conditional compilation.
- There is a basic form of modularity: files can be compiled separately and linked together, with control over which functions and data objects are visible to other files via static and extern attributes.
- Complex functionality such as I/O, string manipulation, and mathematical functions are consistently delegated to library routines.
- The generated code after compilation has relatively straightforward needs on the underlying platform, which makes it suitable for creating operating systems and for use in embedded systems.

## Versions

C has been standardized by ANSI since 1989 (ANSI C) and by the International Organization for Standardization (ISO).

**Latest Version**: C17.
