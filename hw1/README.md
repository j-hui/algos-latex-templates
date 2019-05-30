Algorithms Homework 1 Template
==============================

There are two ways to use this template. The first is to simply copy it to
Overleaf, and the second is to compile the document locally.

Overleaf
--------

First, you will need an [Overleaf][overleaf] account, which you can sign up for
for free.

To use this template in overleaf, simply copy the contexts of
[`hw1-submit.tex`][hw1-tex] to a new Overleaf project.

[overleaf]: https://www.overleaf.com/
[hw1-tex]: ./hw1-submit.tex


Local compilation
-----------------

To compile this `.tex` file locally, you will need to have `pdflatex` installed
and available in your path. You will also need `make` and `git` installed.

First, `git clone` this repo to your machine. You may make local commits of any
files you modify to keep track of your own work.

**Do not fork this repo.** You are responsible for keeping your work private.
If you would like push your work to your own GitHub repo, please create a
_private_ repo, add that as a remote, and push your work there.

To compile the `.tex` document, simply navigate to the appropriate working
directory (e.g. `hw1/`), and run `make`. This will generate a PDF from your
`.tex` file (e.g. `hw1-submit.pdf`).
