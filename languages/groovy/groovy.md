# Groovy

Apache Groovy is a Java-syntax-compatible object-oriented programming language for the Java platform. It is both a static and dynamic language with features similar to those of Python, Ruby, and Smalltalk. It can be used as both a programming language and a scripting language for the Java Platform, is compiled to Java virtual machine (JVM) bytecode, and interoperates seamlessly with other Java code and libraries. Groovy uses a curly-bracket syntax similar to Java's. Groovy supports closures, multiline strings, and expressions embedded in strings. Much of Groovy's power lies in its AST transformations, triggered through annotations.

**Creator**: James Strachan

**First appeard**: 2003; 19 years ago

**License**: Apache License 2.0

**Type**: Implementation (Can also compile to the java platform)

## History

James Strachan first talked about the development of Groovy on his blog in August 2003.[7] In March 2004, Groovy was submitted to the JCP as JSR 241[8] and accepted by ballot. Several versions were released between 2004 and 2006. After the Java Community Process (JCP) standardization effort began, the version numbering changed, and a version called "1.0" was released on January 2, 2007. After various betas and release candidates numbered 1.1, on December 7, 2007, Groovy 1.1 Final was released and immediately renumbered as Groovy 1.5 to reflect the many changes made.
In 2007, Groovy won the first prize at JAX 2007 innovation award.[9] In 2008, Grails, a Groovy web framework, won the second prize at JAX 2008 innovation award.[10]
In November 2008, SpringSource acquired the Groovy and Grails company (G2One).[11] In August 2009 VMware acquired SpringSource.[12]
In April 2012, after eight years of inactivity, the Spec Lead changed the status of JSR 241 to dormant.[8]
Strachan had left the project silently a year before the Groovy 1.0 release in 2007.[citation needed] In Oct 2016, Strachan stated "I still love groovy (jenkins pipelines are so groovy!), java, go, typescript and kotlin".[13]
On July 2, 2012, Groovy 2.0 was released, which, among other new features, added static compiling and static type checking.
When the Pivotal Software joint venture was spun-off by EMC Corporation (EMC) and VMware in April 2013, Groovy and Grails formed part of its product portfolio. Pivotal ceased sponsoring Groovy and Grails from April 2015.[5] That same month, Groovy changed its governance structure from a Codehaus repository to a Project Management Committee (PMC) in the Apache Software Foundation via its incubator.[6] Groovy graduated from Apache's incubator and became a top-level project in November 2015


## Overview

Most valid Java files are also valid Groovy files. Although the two languages are similar, Groovy code can be more compact, because it does not need all the elements that Java needs.[15] This makes it possible for Java programmers to learn Groovy gradually by starting with familiar Java syntax before acquiring more Groovy programming idioms.[16]
Groovy features not available in Java include both static and dynamic typing (with the keyword def), operator overloading, native syntax for lists and associative arrays (maps), native support for regular expressions, polymorphic iteration, string interpolation, added helper methods, and the safe navigation operator ?. to check automatically for null pointers (for example, variable?.method(), or variable?.field).[17]
Since version 2 Groovy also supports modularity (being able to ship only the needed jars according to the project needs, thus reducing the size of Groovy's library), type checking, static compiling, Project Coin syntax enhancements, multicatch blocks and ongoing performance enhancements using the invokedynamic instruction introduced in Java 7.[18]
Groovy provides native support for various markup languages such as XML and HTML, accomplished via an inline Document Object Model (DOM) syntax. This feature enables the definition and manipulation of many types of heterogeneous data assets with a uniform and concise syntax and programming methodology.[citation needed]
Unlike Java, a Groovy source code file can be executed as an (uncompiled) script, if it contains code outside any class definition, if it is a class with a main method, or if it is a Runnable or GroovyTestCase. A Groovy script is fully parsed, compiled, and generated before executing (similar to Python and Ruby). This occurs under the hood, and the compiled version is not saved as an artifact of the process

## Versions

**Latest Version**: 4.0.0