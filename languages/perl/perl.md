# Perl

Perl is a family of two high-level, general-purpose, interpreted, dynamic programming languages. "Perl" refers to Perl 5, but from 2000 to 2019 it also referred to its redesigned "sister language", Perl 6, before the latter's name was officially changed to Raku in October 2019.
Though Perl is not officially an acronym, there are various backronyms in use, including "Practical Extraction and Reporting Language". Perl was developed by Larry Wall in 1987 as a general-purpose Unix scripting language to make report processing easier. Since then, it has undergone many changes and revisions. Raku, which began as a redesign of Perl 5 in 2000, eventually evolved into a separate language. Both languages continue to be developed independently by different development teams and liberally borrow ideas from each other.

**Creator**: Larry Wall

**First Appeard**: February 1, 1988; 34 years ago

**License**: Artistic License 1.0 or GNU GPL 1.0

**Type**: Implementation

## History

Larry Wall began work on Perl in 1987, while working as a programmer at Unisys, and version 1.0 was released to the comp.sources.unix newsgroup on February 1, 1988. The language expanded rapidly over the next few years.

## Overview

The overall structure of Perl derives broadly from C. Perl is procedural in nature, with variables, expressions, assignment statements, brace-delimited blocks, control structures, and subroutines.

Perl also takes features from shell programming. All variables are marked with leading sigils, which allow variables to be interpolated directly into strings. However, unlike the shell, Perl uses sigils on all accesses to variables, and unlike most other programming languages that use sigils, the sigil doesn't denote the type of the variable but the type of the expression. So for example, while an array is denoted by the sigil "@" (for example @arrayname), an individual member of the array is denoted by the scalar sigil "$" (for example $arrayname). Perl also has many built-in functions that provide tools often used in shell programming (although many of these tools are implemented by programs external to the shell) such as sorting, and calling operating system facilities.

Perl takes hashes ("associative arrays") from AWK and regular expressions from sed. These simplify many parsing, text-handling, and data-management tasks. Shared with Lisp is the implicit return of the last value in a block, and all statements are also expressions which can be used in larger expressions themselves.

Perl 5 added features that support complex data structures, first-class functions (that is, closures as values), and an object-oriented programming model. These include references, packages, class-based method dispatch, and lexically scoped variables, along with compiler directives (for example, the strict pragma). A major additional feature introduced with Perl 5 was the ability to package code as reusable modules. Wall later stated that "The whole intent of Perl 5's module system was to encourage the growth of Perl culture rather than the Perl core."
All versions of Perl do automatic data-typing and automatic memory management. The interpreter knows the type and storage requirements of every data object in the program; it allocates and frees storage for them as necessary using reference counting (so it cannot deallocate circular data structures without manual intervention). Legal type conversions — for example, conversions from number to string — are done automatically at run time; illegal type conversions are fatal errors

## Versioning

Perl 5, the language usually referred to as "Perl", continues to be actively developed. Perl 5.12.0 was released in April 2010 with some new features influenced by the design of Perl 6 followed by Perl 5.14.1 (released on June 17, 2011), Perl 5.16.1 (released on August 9, 2012.116]), and Perl 5.18.0 (released on May 18, 2013). Perl 5 development versions are released on a monthly basis, with major releases coming out once per year.

**Current Version**: 5.34