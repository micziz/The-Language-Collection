# Elixir

Elixir is a functional, concurrent, general-purpose programming language that runs on the BEAM virtual machine which is also used to implement the Erlang programming language. Elixir builds on top of Erlang and shares the same abstractions for building distributed, fault-tolerant applications. Elixir also provides productive tooling and an extensible design. The latter is supported by compile-time metaprogramming with macros and polymorphism via protocols.

Elixir is used by companies such as Ramp, PagerDuty and Discord.

**Creator**: José Valim

**First appeared**:	2012; 10 years ago

**License**: Apache License 2.0

**Type**: Implementation

## History

José Valim is the creator of the Elixir programming language, a research and development project created at Plataformatec. His goals were to enable higher extensibility and productivity in the Erlang VM while keeping compatibility with Erlang's ecosystem.

## Versioning

Elixir mostly[27] follows semantic versioning and has only 1 major version with no plans for a second. Each of the minor versions supports a specific range of Erlang/OTP versions.

Current Version: 1.13.4

## Features

- Compiles to bytecode for the Erlang Virtual Machine (BEAM).
- Everything is an expression
- Erlang functions can be called from Elixir, and vice versa, without run time impact, due to compilation to Erlang bytecode
- Meta programming allowing direct manipulation of abstract syntax tree (AST)
- Polymorphism via a mechanism called protocols. As in Clojure, protocols provide a dynamic dispatch mechanism. However, this is not to be confused with multiple dispatch as Elixir protocols dispatch on a single type.
- Support for documentation via Python-like docstrings in the Markdown formatting language
- Shared nothing concurrent programming via message passing (Actor model)
- Emphasis on recursion and higher-order functions instead of side-effect-based looping
- Lightweight concurrency utilizing Erlang's mechanisms
- Railway oriented programming via the with construct
- Built-in tooling for managing dependencies, code compilation, running tests, formatting code, remote debugging and more
- Lazy and async collections with streams
- Pattern matching to promote assertive code
- Unicode support and UTF-8 strings