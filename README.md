# FH CAMPUS02 - LaTeX Template

[![Build Status](https://img.shields.io/travis/fladi/CAMPUS02-LaTeX/master.svg?style=flat-square)](https://travis-ci.org/fladi/CAMPUS02-LaTeX)
[![Downloads](https://img.shields.io/github/downloads/fladi/CAMPUS02-LaTeX/total.svg?style=flat-square)](https://github.com/fladi/CAMPUS02-LaTeX/releases)
[![Latest Tag](https://img.shields.io/github/tag/fladi/CAMPUS02-LaTeX.svg?style=flat-square)](https://github.com/fladi/CAMPUS02-LaTeX/releases/tag/v1.3.1)
[![MIT License](https://img.shields.io/github/license/fladi/CAMPUS02-LaTeX.svg?style=flat-square)](https://opensource.org/licenses/MIT)

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

    latexmk masterthesis

This will create the document in `masterthesis.pdf`.

## Presentation Usage

This is optional. For those who wish to use LaTeX to also create an accompanying
presentation to the masterthesis document, `presentation.tex` is the place where
slides can be created.

The final presentation will also be in the PDF format and can be created with
[latexmk](http://users.phys.psu.edu/~collins/software/latexmk-jcc/):

    latexmk presentation

This will create the document in `presentation.pdf`.
