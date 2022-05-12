# Php

PHP is a general-purpose scripting language geared toward web development. It was originally created by Danish-Canadian programmer Rasmus Lerdorf in 1994. The PHP reference implementation is now produced by The PHP Group. PHP originally stood for Personal Home Page, but it now stands for the recursive initialism PHP: Hypertext Preprocessor.

**Creator**: Rasmus Lerdorf

**First appeard**: June 8 1995, 26 years ago

**License**: PHP License

**Type**: Implementation

## History

PHP development began in 1994 when Rasmus Lerdorf wrote several Common Gateway Interface (CGI) programs in C, which he used to maintain his personal homepage. He extended them to work with web forms and to communicate with databases, and called this implementation "Personal Home Page/Forms Interpreter" or PHP/FI.
PHP/FI could be used to build simple, dynamic web applications. To accelerate bug reporting and improve the code, Lerdorf initially announced the release of PHP/FI as "Personal Home Page Tools (PHP Tools) version 1.0" on the Usenet discussion group comp.infosystems.www.authoring.cgi on June 8, 1995.[1][18] This release already had the basic functionality that PHP has today. This included Perl-like variables, form handling, and the ability to embed HTML. The syntax resembled that of Perl, but was simpler, more limited and less consistent.

## Overview
 
The PHP interpreter only executes PHP code within its delimiters. Anything outside of its delimiters is not processed by PHP, although non-PHP text is still subject to control structures described in PHP code. The most common delimiters are <?php to open and ?> to close PHP sections. The shortened form <? also exists. This short delimiter makes script files less portable, since support for them can be disabled in the local PHP configuration and it is therefore discouraged. Conversely, there is no recommendation against the echo short tag <?=. Prior to PHP 5.4.0, this short syntax for echo only works with the short_open_tag configuration setting enabled, while for PHP 5.4.0 and later it is always available. The purpose of all these delimiters is to separate PHP code from non-PHP content, such as JavaScript code or HTML markup.

## Versioning

Beginning on 28 June 2011, the PHP Development Team implemented a timeline for the release of new versions of PHP. Under this system, at least one release should occur every month. Once per year, a minor release should occur which may include new features. Every minor release should at least be supported for two years with security and bug fixes, followed by at least one year of only security fixes, for a total of a three-year release process for every minor release. No new features, unless small and self-contained, are to be introduced into a minor release during the three-year release process.

**Latest version**: 8.1.5
