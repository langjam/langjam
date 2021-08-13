# Resources

Would like to participate in the Lang Jam and need a few resources on creating a programming language? This page has you covered.

## Tutorials

* [The super tiny compiler](https://github.com/thejameskyle/the-super-tiny-compiler/blob/master/the-super-tiny-compiler.js)
* [Introduction to Pest in Rust](https://www.youtube.com/watch?v=VYBi9an29Hw) and [Using Pest to make a language](https://www.youtube.com/watch?v=COwHHUshkN0)
* [How to Write a Lisp Interpreter in Python](https://norvig.com/lispy.html) ([Advanced / Part 2](http://norvig.com/lispy2.html))
* [Parsing with OCamllex and Menhir](https://dev.realworldocaml.org/parsing-with-ocamllex-and-menhir.html)
* [How to make your papers run](https://www.tweag.io/blog/2019-11-28-PCF-makam-spec/) - tutorial on using using Makam to define prototype evaluators
* [Creating Languages in Racket](https://cacm.acm.org/magazines/2012/1/144809-creating-languages-in-racket/fulltext) by Matthew Flatt Communications of the ACM, January 2012 [code](https://github.com/spdegabrielle/flatt-languages)
* [7 lines of code, 3 minutes: Implement a programming language from scratch](https://matt.might.net/articles/implementing-a-programming-language/)
* [5 Tips For Making a Programming Language from JT](https://youtu.be/XHn7kQJ_V24)
* [Building a programming language in an hour from JT](https://www.youtube.com/watch?v=Zkd3mZYOOvw)

## Overviews

* [Parsing in Python](https://tomassetti.me/parsing-in-python/)

## Tools

* [Pest](https://github.com/pest-parser/pest), [Nom](https://github.com/Geal/nom), [lalrpop](https://github.com/lalrpop/lalrpop) - libraries for helping you write a parser in Rust
* [List of langdev libraries for Rust](https://github.com/Kixiron/rust-langdev/)
* [Nanopass](https://nanopass.org/) - embedded DSL for Scheme and Racket for defining multipass compilers
* [Makam](https://github.com/astampoulis/makam) - metalanguage useful for prototyping languages
* [Template for a Racket language in Racket](https://github.com/racket-templates/lang) - A working example of a #lang language you can use as a starting point for creating your own #lang language. (Template based on `xlang` A language of combinators and numeric constants, implemented in Racket.)
* [Sham: A DSL for runtime code generation in Racket](https://github.com/rjnw/sham) - use this to target WASM or LLVM
* [RLMeta](http://rickardlindberg.me/projects/rlmeta/) - RLMeta is a programming language in which you write grammars. Grammars have rules that specify how to match objects from an input stream and specify what should happen when objects are matched. It can be used to write lexers, parsers, tree transformers, code generators, and similar tools. The RLMeta compiler is implemented in RLMeta itself which makes it a metacompiler. (There are multiple versions of RLMeta that all live in blog posts and the theory behind them is quite well documented.)
* [Online Intel 8086 emulator](https://yjdoc2.github.io/8086-emulator-web/compile) - a web-based assembler IDE with live debugging

## Books

* [Compiler course notes for creating a Python compiler](resources/Python_compiler.pdf) - Freely available, and goes over many steps for building up your own Python compiler
* [Crafting Interpeters](http://craftinginterpreters.com/introduction.html) - Newly released and available for free online
* [Practical Foundations for Programming Languages](https://www.cs.cmu.edu/~rwh/pfpl/) - "a comprehensive framework for formulating and analyzing a broad range of ideas in programming languages", one of the best modern introductions to programming language design. Abbreviated online edition available for free.
* [Programming Language Pragmatics](https://www.elsevier.com/books/programming-language-pragmatics/scott/978-0-12-410409-9) - A textbook that goes into some of the thinking behind different styles of programming languages
* [The Dragon book](https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools) - A classic, though also quite the tome
* [Flex and Bison](https://web.iitd.ac.in/~sumeet/flex__bison.pdf) - A book explaining use of flex and bison from the very basics to create parsers.
* [Build Your Own Lisp](http://www.buildyourownlisp.com/) - Learn C and build your own programming language in 1000 lines of code. Freely available online.
* [Beautiful Racket: an introduction to language-oriented programming using Racket](https://beautifulracket.com) by Matthew Butterick
* [Programming Languages: Application and Interpretation](https://www.plai.org) by [Shriram Krishnamurthi](https://cs.brown.edu/~sk/). Freely available online.

## Other
* [Write you a programming language](https://github.com/stereobooster/write-you-a-programming-language) - huge collection of small programming languages that you can implement in a relatively small amount of time for educational purposes as well as other useful resources
* [PL resources](https://bernsteinbear.com/pl-resources/) - a collection of compiler, runtime, and runtime optimization resources
