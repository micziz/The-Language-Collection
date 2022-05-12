# Kotlin

Kotlin is a cross-platform, statically typed, general-purpose programming language with type inference. Kotlin is designed to interoperate fully with Java, and the JVM version of Kotlin's standard library depends on the Java Class Library, but type inference allows its syntax to be more concise. Kotlin mainly targets the JVM, but also compiles to JavaScript (e.g., for frontend web applications using React) or native code via LLVM (e.g., for native iOS apps sharing business logic with Android apps). Language development costs are borne by JetBrains, while the Kotlin Foundation protects the Kotlin trademark.

**Creator**: JetBrains

**First appeard**: July 22, 2011; 10 years ago

**License**: Apache 2.0

**Type**: Implementation (Can compile natively or on the JVM)

## History

In July 2011, JetBrains unveiled Project Kotlin, a new language for the JVM, which had been under development for a year. JetBrains lead Dmitry Jemerov said that most languages did not have the features they were looking for, with the exception of Scala. However, he cited the slow compilation time of Scala as a deficiency. One of the stated goals of Kotlin is to compile as quickly as Java. In February 2012, JetBrains open sourced the project under the Apache 2 license.

The name comes from Kotlin Island, near St. Petersburg.

## Overview

Development lead Andrey Breslav has said that Kotlin is designed to be an industrial-strength object-oriented language, and a "better language" than Java, but still be fully interoperable with Java code, allowing companies to make a gradual migration from Java to Kotlin.
Semicolons are optional as a statement terminator; in most cases a newline is sufficient for the compiler to deduce that the statement has ended.
Kotlin variable declarations and parameter lists have the data type come after the variable name (and with a colon separator), similar to Ada, BASIC, Pascal, TypeScript and Rust. This, according to an article from Roman Elizarov, current project lead, results in alignment of variable names and is more pleasing to eyes especially when there are a few variable declarations in succession and one or more of the types is too complex for type inference or needs to be declared explicitly for human readers to understand.
Variables in Kotlin can be read-only, declared with the val keyword, or mutable, declared with the var keyword.
Class members are public by default, and classes themselves are final by default, meaning that creating a derived class is disabled unless the base class is declared with the open keyword.

## Versioning

**Latest Version**: 1.6.20