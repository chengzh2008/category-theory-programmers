# Notes on Category Theory and Haskell

[A pdf of the notes can be found here](https://github.com/jwbuurlage/category-theory-programmers/raw/master/doc/categories_for_programmers.pdf).

This document contains notes, originally for a seminar on category theory in the context of (functional) programming, hosted at Centrum Wiskunde & Informatica, the national Dutch research centre for mathematics and computer science. The goal is to provide a way to gain familiarity with concepts of category theory (and other branches of mathematics) that apply (in a broad sense) to the field of functional programming.

Although the main focus is on the mathematics, examples are given in Haskell to illustrate how to apply the concepts. In some places, examples are given in other languages as well (such as Python and C++). The topics discussed include:

* Categories
* Types as a category
* Products
* Yoneda
* Closed Cartesian categories
* Adjunctions
* Monads
* F-algebras and recursion
* Comonads
* Lenses

## Generating the document

The notes are written in Markdown, and `pandoc` is used to generate the document. Running `make` inside the `doc` directory should result in an (updated) pdf, granted that `pandoc`, `pandoc-citeproc` and a LaTeX environment are installed.

## Contributing

GitHub can be used for any issues (typos, inaccuracies, ...). Pull requests with fixes or additional material are also very welcome.
