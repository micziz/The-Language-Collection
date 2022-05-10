## Clojure

Clojure is a dynamic and functional dialect of the Lisp programming language on the Java platform.[17][18] Like other Lisp dialects, Clojure treats code as data and has a Lisp macro system.[19] The current development process is community-driven, overseen by Rich Hickey as its benevolent dictator for life (BDFL).

**Creator**: Rich Hickey

**First appeard**: 2007; 15 years ago

**License**: Eclipse Public License

**Type**: Implementation

## History

Rich Hickey is the creator of the Clojure language. Before Clojure, he developed dotLisp, a similar project based on the .NET platform, and three earlier attempts to provide interoperability between Lisp and Java: a Java foreign language interface for Common Lisp (jfli), A Foreign Object Interface for Lisp (FOIL), and a Lisp-friendly interface to Java Servlets (Lisplets).

Hickey spent about 2½ years working on Clojure before releasing it publicly in October 2007, much of that time working exclusively on Clojure with no outside funding. At the end of this time, Hickey sent an email announcing the language to some friends in the Common Lisp community.

Clojure's name, according to Hickey, is a word play on the programming concept "closure" incorporating the letters C, L, and J for C#, Lisp, and Java respectively—three languages which had a major influence on Clojure's design.

## Overview

Clojure runs on the Java platform and as a result, integrates with Java and fully supports calling Java code from Clojure,[53][15] and Clojure code can be called from Java, too.[54] The community uses tools like Leiningen for project automation, providing support for Maven integration. Leiningen handles project package management and dependencies and is configured using Clojure syntax.[55]

Like most other Lisps, Clojure's syntax is built on S-expressions that are first parsed into data structures by a reader before being compiled.[56][15] Clojure's reader supports literal syntax for maps, sets and vectors in addition to lists, and these are compiled to the mentioned structures directly.[56] Clojure is a Lisp-1 and is not intended to be code-compatible with other dialects of Lisp, since it uses its own set of data structures incompatible with other Lisps.[19]

As a Lisp dialect, Clojure supports functions as first-class objects, a read–eval–print loop (REPL), and a macro system.[6] Clojure's Lisp macro system is very similar to that of Common Lisp with the exception that Clojure's version of the backquote (termed "syntax quote") qualifies symbols with their namespace. This helps prevent unintended name capture, as binding to namespace-qualified names is forbidden. It is possible to force a capturing macro expansion, but it must be done explicitly. Clojure does not allow user-defined reader macros, but the reader supports a more constrained form of syntactic extension.[57] Clojure supports multimethods[58] and for interface-like abstractions has a protocol[59] based polymorphism and data type system using records,[60] providing high-performance and dynamic polymorphism designed to avoid the expression problem.

Clojure has support for lazy sequences and encourages the principle of immutability and persistent data structures. As a functional language, emphasis is placed on recursion and higher-order functions instead of side-effect-based looping. Automatic tail call optimization is not supported as the JVM does not support it natively;[61][62][63] it is possible to do so explicitly by using the recur keyword.[64] For parallel and concurrent programming Clojure provides software transactional memory,[65] a reactive agent system,[1] and channel-based concurrent programming.[66]

Clojure 1.7 introduced reader conditionals by allowing the embedding of Clojure and ClojureScript code in the same namespace.[45][56] Transducers were added as a method for composing transformations. Transducers enable higher-order functions such as map and fold to generalize over any source of input data. While traditionally these functions operate on sequences, transducers allow them to work on channels and let the user define their own models for transduction.

## Versioning

Clojure has 1 Major version with no plans for a second. 

Current Version: 1.11.1

