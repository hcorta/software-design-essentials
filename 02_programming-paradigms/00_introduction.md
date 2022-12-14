# Introduction

## What is a Programming Paradigm?

**Paradigms are ways of programming**, _relatively unrelated to languages_. A
paradigm tells you which programming structures to use, and when to use them.
Each paradigm consists of certain structures, features, and opinions about how
common programming problems should be tackled.

The question of why are there many different programming paradigms is similar to
why are there many programming languages. Certain paradigms are better suited
for certain types of problems, so it makes sense to use different paradigms for
different kinds of projects.

## Why should I care?

As a software craftsman, it is important to understand the differences between
each mainstream programming paradigm, what each uniquely brings to the table,
and when to use them.

## Programming Paradigms

All programming paradigms have the same thing in common: they deal with
sequence, selection, iteration, and indirection — just in different ways. By
building correct conceptual models around structured, object-oriented, and
functional programming, we make less big mistakes and learn discover that we can
use the best techniques from each, regardless of the paradigm we decide on.

To date, there are several programming paradigms. Among these:

- **Structured**: Programming with clean, goto-free, nested control structures.
- **Functional**: Programming with function calls that avoid any global state.
- **Object-Oriented**: Programming by defining objects that send messages to
  each other. Objects have their own internal (encapsulated) state and public
  interfaces. Object orientation can be:
- **Imperative**: Programming with an explicit sequence of commands that update
  state.
- **Declarative**: Programming by specifying the result you want, not how to get
  it.
- **Procedural**: Imperative programming with procedure calls.
- **...**

For the sake of brevity. The three paradigms included in this overview chapter
are structured programming, object-orient programming, and functional
programming.

It is important to understand that we don't usually program under a single
programming paradigm, but a combination of some of them. In Uncle Bob’s book,
`Clean Architecture`, he brings attention to the fact that:

- Object-Oriented Programming is the tool best suited for defining how we cross
  architectural boundaries with polymorphism and plugins.
- Functional programming is the tool we use to impose discipline on the location
  of and access to data.
- Structured programming is the algorithmic foundation of our modules.

This implies that robust software uses a hybrid all 3 programming paradigms
styles at different times. While you could take a strictly functional or
strictly object-oriented approach to write code in a project, understanding
where each excels will improve the quality of your designs.

## Programming Languages and Paradigms

One of the characteristics of a language is its support for particular
programming paradigms. For example, Smalltalk has direct support for programming
in the object-oriented way, so it might be called an object-oriented language.
OCaml, Lisp, Scheme, and JavaScript programs tend to make heavy use of passing
functions around so they are called “functional languages” despite having
variables and many imperative constructs.

There are two very important observations here:

- Very few languages implement a paradigm 100%. When they do, they are pure. It
  is incredibly rare to have a “pure OOP” language or a “pure functional”
  language.
- A lot of languages will facilitate programming in one or more paradigms. In
  Scala you can do imperative, object-oriented, and functional programming quite
  easily.

## Conclusion

Whether we use one paradigm or another doesn't matter. All that matters is that
we build using the paradigm in the way it was intended to be used and we
understand the implications of stepping outside of the box.

## References

- Clean Architecture: A Craftsman's Guide to Software Structure and Design -
  Robert C. Martin
- SOLID: The Software Design and Architecture Handbook - Khalil Stemmler
- Programming paradigm - Wikipedia
