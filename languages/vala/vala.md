# Vala

Vala is an object-oriented programming language with a self-hosting compiler that generates C code and uses the GObject system.
Vala is syntactically similar to C# and includes notable features such as anonymous functions, signals, properties, generics, assisted memory management, exception handling, type inference, and foreach statements. Its developers, Jürg Billeter and Raffaele Sandrini, wanted to bring these features to the plain C runtime with little overhead and no special runtime support by targeting the GObject object system. Rather than compiling directly to machine code or assembly language, it compiles to a lower-level intermediate language. It source-to-source compiles to C, which is then compiled with a C compiler for a given platform, such as GCC or Clang

**Creators**: Jürg Billeter and Raffaele Sandrini

**First Appeard**: 2006; 16 years ago

**License**: LGPLv2.1+

**Type**: Implementation


## History

Vala was conceived by Jürg Billeter and was implemented by him and Raffaele Sandrini, who wished for a higher level alternative for developing GNOME applications instead of C. They did like the syntax and semantics of C# but did not want to use Mono, so they finished a compiler in May 2006. Initially, it was bootstrapped using C, and one year later (with release of version 0.1.0 in July 2007), the Vala compiler became self-hosted. As of 2021, the current stable release branch with long-term support is 0.48, and the language is under active development with the goal of releasing a stable version 1.0.

## Overview

Vala is a programming language that combines the high-level build-time performance of scripting languages with the run-time performance of low-level programming languages. It aims to bring modern programming language features to GNOME developers without imposing any additional runtime requirements and without using a different ABI, compared to applications and libraries written in C. The syntax of Vala is similar to C#, modified to better fit the GObject type system.

## Versioning

**Latest Version**: 0.56.1
