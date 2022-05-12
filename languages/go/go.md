# GO

Go is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson. It is syntactically similar to C, but with memory safety, garbage collection, structural typing, and CSP-style concurrency. It is often referred to as Golang because of its former domain name, golang.org, but its proper name is Go.

**Creator**: Robert Griesemer, Rob Pike, Ken Thompson

**First appeard**: November 10, 2009; 12 years ago

**License**: BSD 3-Clause

**Type**: Implementation

## History

Go was designed at Google in 2007 to improve programming productivity in an era of multicore, networked machines and large codebases. The designers wanted to address criticism of other languages in use at Google, but keep their useful characteristics:

- Static typing and run-time efficiency (like C)
- Readability and usability (like Python or JavaScript)
- High-performance networking and multiprocessing

Its designers were primarily motivated by their shared dislike of C++

## Overview

Go is influenced by C (especially the Plan 9 dialect), but with an emphasis on greater simplicity and safety. It consists of:

A syntax and environment adopting patterns more common in dynamic languages:
- Optional concise variable declaration and initialization through type inference (x := 0 instead of int x = 0; or var x = 0;)
- Fast compilation
– Remote package management (go get) and online package documentation[49]
Distinctive approaches to particular problems:
– Built-in concurrency primitives: light-weight processes (goroutines), channels, and the select statement
– An interface system in place of virtual inheritance, and type embedding instead of non-virtual inheritance
– A toolchain that, by default, produces statically linked native binaries without external dependencies
A desire to keep the language specification simple enough to hold in a programmer's head,[50] in part by omitting features that are common in similar languages.

## Versioning

Each major Go release is supported until there are two newer major releases.

**Latest Version**: Go 1.18

