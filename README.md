Algorithms Homework Template
============================

This repo contains some LaTeX templates written for CSOR W4231: Analysis of
Algorithms, taught at Columbia University.

There are two ways to use these templates. The first is to simply copy them to
Overleaf, and the second is to compile these documents locally.

Overleaf
--------

First, you will need an [Overleaf][overleaf] account, which you can sign up for
for free.

To use a template in Overleaf (e.g. for HW1), simply copy its contents (e.g.
[`hw1-submit.tex`][hw1-tex]) to a new Overleaf project.

[overleaf]: https://www.overleaf.com/
[hw1-tex]: hw1/hw1-submit.tex


Local compilation
-----------------

To compile a `.tex` file locally, you will need to have `pdflatex` installed
and available in your path. You will also need `make` and `git` installed.

First, `git clone` this repo to your machine. You may make local commits of any
files you modify to keep track of your own work.

**You are responsible for keeping your work private.** If you would like to push
your work to your own GitHub repo, please do not create a fork of this repo
(because it will be public).  Instead, create a _private_ repo, add that as a
remote, and push your work there.

To compile the `.tex` document, simply navigate to the appropriate working
directory (e.g. `hw1/`), and run `make`. This will generate a PDF from your
`.tex` file (e.g. `hw1-submit.pdf`).

--------

Writing LaTeX
-------------

The [base template][base-tex] for this repo also contains some handy LaTeX
examples that you might find useful for doing algorithms assignments. Compile
the `.tex` document to see what some of the commands end up looking like in the
resulting PDF.

If you have any other useful examples you'd like to suggest, issue a PR!

[base-tex]: base-tutorial/base-tutorial.tex
