# Dart

Dart is a programming language designed for client development, such as for the web and mobile apps. It is developed by Google and can also be used to build server and desktop applications.
It is an object-oriented, class-based, garbage-collected language with C-style syntax. It can compile to either native code or JavaScript, and supports interfaces, mixins, abstract classes, reified generics and type inference.

**Creator**: Lars Bak and Kasper Lund

**First Appeard**: October 10, 2011; 10 years ago

**License**: BSD

**Type**: Implementation (Also has a spec)

## History

Dart was unveiled at the GOTO conference in Aarhus, Denmark, October 10–12, 2011. The project was founded by Lars Bak and Kasper Lund. Dart 1.0 was released on November 14, 2013.
Dart initially had a mixed reception and the Dart initiative has been criticized by some for fragmenting the web, due to the original plans to include a Dart VM in Chrome. Those plans were dropped in 2015 with the 1.9 release of Dart to focus instead on compiling Dart to JavaScript.

## Overview

There are four ways to run Dart code:

**Web**:

To run in mainstream web browsers, Dart relies on a source-to-source compiler to JavaScript. According to the project site, Dart was "designed to be easy to write development tools for, well-suited to modern app development, and capable of high-performance implementations." In a web browser, the code is precompiled into JavaScript using the dart2js compiler, making it compatible with all major browsers with no need for browsers to adopt it. By optimizing the compiled JavaScript output to avoid expensive checks and operations, code written in Dart can, in some cases, run faster than equivalent code handwritten in JavaScript idioms.

**Stand-alone**:

The Dart software development kit (SDK) ships with a stand-alone Dart VM, allowing Dart code to run in a command-line interface environment. As the language tools included in the SDK are written mostly in Dart, the Dart VM is a critical part of it. These tools include the dart2js compiler and a package manager called pub. Dart ships with a complete standard library allowing users to write fully working system apps, such as custom web servers.

**Ahead-of-time compiled**

Dart code can be AOT-compiled into machine code (native instruction sets). Apps built with Flutter, a mobile app SDK built with Dart, are deployed to app stores as AOT-compiled Dart code.

**Native**

Dart 2.6 includes the dart2native compiler to compile to self-contained, native executable code. Before Dart 2.6, this feature exposed this capability only on iOS and Android mobile devices via Flutter

## Versioning

**Latest Version**: 2.16.2