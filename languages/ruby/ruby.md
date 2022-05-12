# Ruby

Ruby is an interpreted, high-level, general-purpose programming language which supports multiple programming paradigms. It was designed with an emphasis on programming productivity and simplicity. In Ruby, everything is an object, including primitive data types. It was developed in the mid-1990s by Yukihiro "Matz" Matsumoto in Japan.

**Creator**: Yukihiro "Matz" Matsumoto

**First Appeard**: 1995; 23 years ago

**License**: Ruby License

**Type**: Implementation (Also has a spec)

## History

Matsumoto has said that Ruby was conceived in 1993. In a 1999 post to the ruby-talk mailing list, he describes some of his early ideas about the language:

- I was talking with my colleague about the possibility of an object-oriented scripting language. I knew Perl (Perl4, not Perl5), but I didn't like it really, because it had the smell of a toy language (it still has). The object-oriented language seemed very promising. I knew Python then. But I didn't like it, because I didn't think it was a true object-oriented language – OO features appeared to be add-on to the language. As a language maniac and OO fan for 15 years, I really wanted a genuine object-oriented, easy-to-use scripting language. I looked for but couldn't find one. So I decided to make it.

Matsumoto describes the design of Ruby as being like a simple Lisp language at its core, with an object system like that of Smalltalk, blocks inspired by higher-order functions, and practical utility like that of Perl.
The name "Ruby" originated during an online chat session between Matsumoto and Keiju Ishitsuka on February 24, 1993, before any code had been written for the language. Initially two names were proposed: "Coral" and "Ruby". Matsumoto chose the latter in a later e-mail to Ishitsuka. Matsumoto later noted a factor in choosing the name "Ruby" – it was the birthstone of one of his colleagues.

## Overview

Matsumoto has said that Ruby is designed for programmer productivity and fun, following the principles of good user interface design. At a Google Tech Talk in 2008 Matsumoto further stated, "I hope to see Ruby help every programmer in the world to be productive, and to enjoy programming, and to be happy. That is the primary purpose of Ruby language."

Ruby is object-oriented: every value is an object, including classes and instances of types that many other languages designate as primitives (such as integers, booleans, and "null"). Variables always hold references to objects. Every function is a method and methods are always called on an object. Methods defined at the top level scope become methods of the Object class. Since this class is an ancestor of every other class, such methods can be called on any object. They are also visible in all scopes, effectively serving as "global" procedures. Ruby supports inheritance with dynamic dispatch, mixins and singleton methods (belonging to, and defined for, a single instance rather than being defined on the class). Though Ruby does not support multiple inheritance, classes can import modules as mixins.

## Versioning

Like Python ruby has 3 major version. No note yet on a fourth

**Latest Version**: 3.1.2