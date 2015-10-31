# FH CAMPUS02 - LaTeX Template

[![Build Status](https://travis-ci.org/fladi/CAMPUS02-LaTeX.svg?branch=master)](https://travis-ci.org/fladi/CAMPUS02-LaTeX)

## Masterthesis Usage

To use this template, fork this repository, clone it to your local workspace and
customize at least the following files:

* `misc/settings.tex`
* `misc/Dank.tex`
* `misc/Zitat.tex`
* `misc/Kurzfassung.tex`

Once this is done, take a look at `misc/toc.tex` and at the files in `content/`.
Those will be the files where you are expected to put your own content.

To compile the document it is recommended to use
[latexmk](http://users.phys.psu.edu/~collins/software/latexmk-jcc/):

    latexmk masterhesis

This will create the document in `masterthesis.pdf`.

## Presentation Usage

This is optional. For those who wish to use LaTeX to also create an accompanying
presentation to the masterthesis document, `presentation.tex` is the place where
slides can be created.

The final presentation will also be in the PDF format and can be created with
[latexmk](http://users.phys.psu.edu/~collins/software/latexmk-jcc/):

    latexmk presentation

This will create the document in `presentation.pdf`.
