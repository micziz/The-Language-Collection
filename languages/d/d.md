# D

D, also known as dlang, is a multi-paradigm system programming language created by Walter Bright at Digital Mars and released in 2001. Andrei Alexandrescu joined the design and development effort in 2007. Though it originated as a re-engineering of C++, D is a profoundly different language —features of D can be considered streamlined and expanded-upon ideas from C++, however D also draws inspiration from other high-level programming languages, notably Java, Python, Ruby, C#, and Eiffel.

**Creator**: Walter Bright

**First appeared**: 2001; 20 years ago

**License**: Boost Software 

**Type**: Implementation

## History

Walter Bright started working on a new language in 1999. D was first released in December 2001[1] and reached version 1.0 in January 2007. The first version of the language (D1) concentrated on the imperative, object oriented and metaprogramming paradigms, similar to C++.

Some members of the D community dissatisfied with Phobos, D's official runtime and standard library, created an alternative runtime and standard library named Tango. The first public Tango announcement came within days of D 1.0's release. Tango adopted a different programming style, embracing OOP and high modularity. Being a community-led project, Tango was more open to contributions, which allowed it to progress faster than the official standard library. At that time, Tango and Phobos were incompatible due to different runtime support APIs (the garbage collector, threading support, etc.). This made it impossible to use both libraries in the same project. The existence of two libraries, both widely in use, has led to significant dispute due to some packages using Phobos and others using Tango.

## Overview

D combines the performance and safety of compiled languages with the expressive power of modern dynamic and functional programming languages. Idiomatic D code is commonly as fast as equivalent C++ code, while also being shorter. The language as a whole is not memory-safe but includes optional attributes designed to guarantee memory safety of either subsets of or the whole program.

Type inference, automatic memory management and syntactic sugar for common types allow faster development, while bounds checking, design by contract find bugs earlier at runtime and a concurrency-aware type system catches bugs at compile time.

## Versioning

In June 2007, the first version of D2 was released. The beginning of D2's development signaled D1's stabilization. The first version of the language has been placed in maintenance, only receiving corrections and implementation bugfixes. D2 introduced breaking changes to the language, beginning with its first experimental const system. D2 later added numerous other language features, such as closures, purity, and support for the functional and concurrent programming paradigms. D2 also solved standard library problems by separating the runtime from the standard library. The completion of a D2 Tango port was announced in February 2012.

In December 2011, Andrei Alexandrescu announced that D1, the first version of the language, would be discontinued on 31 December 2012. The final D1 release, D v1.076, was on 31 December 2012.

The release of Andrei Alexandrescu's book The D Programming Language on 12 June 2010, marked the stabilization of D2, which today is commonly referred to as just "D".

**Current version**: D 2.099.1