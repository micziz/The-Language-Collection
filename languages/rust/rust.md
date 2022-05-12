# Rust

Rust is a multi-paradigm, general-purpose programming language designed for performance and safety, especially safe concurrency. It is syntactically similar to C++, but can guarantee memory safety by using a borrow checker to validate references. It achieves memory safety without garbage collection, and reference counting is optional. It is a systems programming language with mechanisms for low-level memory management, but also offers high-level features such as functional programming.

**Creator**: Graydon Hoare

**First Appeard**: July 7, 2010; 11 years ago

**License**: MIT or Apache 2.0 (at your option)

**Type**: Implementation


## History

The Rust programming language grew out of a personal project begun in 2006 by Mozilla employee Graydon Hoare. Hoare has stated that the project was possibly named after rust fungi and that the name is also a subsequence of "robust". Mozilla began sponsoring the project in 2009 and announced it in 2010. The same year, work shifted from the initial compiler (written in OCaml) to an LLVM-based self-hosting compiler written in Rust. Named rustc, it successfully compiled itself in 2011.

## Overview

Rust is intended to be a language for highly concurrent and highly safe systems, and programming in the large, that is, creating and maintaining boundaries that preserve large-system integrity. This has led to a feature set with an emphasis on safety, control of memory layout, and concurrency.

Rust is designed to be memory safe. It does not permit null pointers, dangling pointers, or data races. Data values can be initialized only through a fixed set of forms, all of which require their inputs to be already initialized. To replicate pointers being either valid or NULL, such as in linked list or binary tree data structures, the Rust core library provides an option type, which can be used to test whether a pointer has Some value or None. Rust has added syntax to manage lifetimes, which are checked at compile time by the borrow checker. Unsafe code can subvert some of these restrictions using the unsafe keyword.

## Versioning

**Latest Version**: 1.60.0
