## Clojure

Clojure is a dynamic and functional dialect of the Lisp programming language on the Java platform. Like other Lisp dialects, Clojure treats code as data and has a Lisp macro system. The current development process is community-driven, overseen by Rich Hickey as its benevolent dictator for life.

**Creator**: Rich Hickey

**First appeard**: 2007; 15 years ago

**License**: Eclipse Public License

**Type**: Implementation

## History

Rich Hickey is the creator of the Clojure language. Before Clojure, he developed dotLisp, a similar project based on the .NET platform, and three earlier attempts to provide interoperability between Lisp and Java: a Java foreign language interface for Common Lisp (jfli), A Foreign Object Interface for Lisp (FOIL), and a Lisp-friendly interface to Java Servlets (Lisplets).

Hickey spent about 2½ years working on Clojure before releasing it publicly in October 2007, much of that time working exclusively on Clojure with no outside funding. At the end of this time, Hickey sent an email announcing the language to some friends in the Common Lisp community.

Clojure's name, according to Hickey, is a word play on the programming concept "closure" incorporating the letters C, L, and J for C#, Lisp, and Java respectively—three languages which had a major influence on Clojure's design.

## Overview

Clojure runs on the Java platform and as a result, integrates with Java and fully supports calling Java code from Clojure,[53][15] and Clojure code can be called from Java, too. The community uses tools like Leiningen for project automation, providing support for Maven integration. Leiningen handles project package management and dependencies and is configured using Clojure syntax.

Like most other Lisps, Clojure's syntax is built on S-expressions that are first parsed into data structures by a reader before being compiled. Clojure's reader supports literal syntax for maps, sets and vectors in addition to lists, and these are compiled to the mentioned structures directly. Clojure is a Lisp-1 and is not intended to be code-compatible with other dialects of Lisp, since it uses its own set of data structures incompatible with other Lisps.

As a Lisp dialect, Clojure supports functions as first-class objects, a read–eval–print loop (REPL), and a macro system. Clojure's Lisp macro system is very similar to that of Common Lisp with the exception that Clojure's version of the backquote (termed "syntax quote") qualifies symbols with their namespace. This helps prevent unintended name capture, as binding to namespace-qualified names is forbidden. It is possible to force a capturing macro expansion, but it must be done explicitly. Clojure does not allow user-defined reader macros, but the reader supports a more constrained form of syntactic extension. Clojure supports multimethods and for interface-like abstractions has a protocol based polymorphism and data type system using records, providing high-performance and dynamic polymorphism designed to avoid the expression problem.

Clojure has support for lazy sequences and encourages the principle of immutability and persistent data structures. As a functional language, emphasis is placed on recursion and higher-order functions instead of side-effect-based looping. Automatic tail call optimization is not supported as the JVM does not support it natively; it is possible to do so explicitly by using the recur keyword. For parallel and concurrent programming Clojure provides software transactional memory, a reactive agent system, and channel-based concurrent programming.


## Versioning

Clojure has 1 Major version with no plans for a second. 

**Current Version**: 1.11.1

