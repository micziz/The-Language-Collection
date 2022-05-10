# Haskell

Haskell (/ˈhæskəl/[27]) is a general-purpose, statically-typed, purely functional programming language with type inference and lazy evaluation.[28][29] Designed for teaching, research and industrial application, Haskell has pioneered a number of programming language features such as type classes, which enable type-safe operator overloading. 

**Creators**: Lennart Augustsson, Dave Barton, Brian Boutel, Warren Burton, Joseph Fasel, Kevin Hammond, Ralf Hinze, Paul Hudak, John Hughes, Thomas Johnsson, Mark Jones, Simon Peyton Jones, John Launchbury, Erik Meijer, John Peterson, Alastair Reid, Colin Runciman, Philip Wadler

**First Appeard**: 1990; 32 years ago

**License**: ? Up to the implementation.

**Type**: Spec

## History

Following the release of Miranda by Research Software Ltd. in 1985, interest in lazy functional languages grew. By 1987, more than a dozen non-strict, purely functional programming languages existed. Miranda was the most widely used, but it was proprietary software. At the conference on Functional Programming Languages and Computer Architecture (FPCA '87) in Portland, Oregon, there was a strong consensus that a committee be formed to define an open standard for such languages. The committee's purpose was to consolidate existing functional languages into a common one to serve as a basis for future research in functional-language design.

## Overview

Haskell features lazy evaluation, lambda expressions, pattern matching, list comprehension, type classes and type polymorphism. It is a purely functional language, which means that functions generally have no side effects. A distinct construct exists to represent side effects, orthogonal to the type of functions. A pure function can return a side effect that is subsequently executed, modeling the impure functions of other languages.
Haskell has a strong, static type system based on Hindley–Milner type inference. Its principal innovation in this area is type classes, originally conceived as a principled way to add overloading to the language,[42] but since finding many more uses.[43]
The construct that represents side-effects is an example of a monad: a general framework which can model various computations such as error handling, nondeterminism, parsing and software transactional memory. They are defined as ordinary datatypes, but Haskell provides some syntactic sugar for their use.

## Versioning

Haskell's semantics are historically based on those of the Miranda programming language, which served to focus the efforts of the initial Haskell working group

**Latest Version**: Haskell 2010