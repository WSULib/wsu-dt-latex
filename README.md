# Wayne State University Dissertation and Thesis LaTeX Template

This template builds on documents prepared in LaTeX by [Michael Catanzaro](https://faculty.sites.iastate.edu/mjcatanz/) and [Gabriel Angelini-Knoll](https://www.gangeliniknoll.com/), both formerly of the Wayne State University [Department of Mathematics](http://www.clas.wayne.edu/math/), with updates in 2019 by [Aaron Willcock](https://www.linkedin.com/in/aaronwillcock/) (ez9213@wayne.edu) for the updated WSU dissertation and thesis formatting guidelines.
This directory is maintained by [Clayton Hayes](https://library.wayne.edu/info/staff-directory/as6348) (clayton.hayes@wayne.edu), creator of the original template, on behalf of the WSU Library System.

## Compiling
The template can be compiled with pdflatex,
```sh
pdflatex main.tex
```
lualatex,
```sh
lualatex main.tex
```
or xelatex
```sh
xelatex main.tex
```

### Notes on Compiling
* If you are using BibTeX, recall that you must first run bibtex on main.tex before compiling the full document
```sh
bibtex main.tex
```
* In order for the Table of Contents to display correctly, you may need to compile main.tex twice.
* The PDF in this directory was compiled using xelatex on 28 September 2021.

## Original LaTeX
The unedited, accepted latex upon which the most recent thesis template revision was adapted can be found [on Github](https://github.com/aarontwillcock/wsu-ms-cs-tufc).

## Disclaimer
This not an official template, but does follow the guidelines laid out by [Wayne State University's Graduate School Manual](https://gradschool.wayne.edu/phd/complete_format_guidelines_6_2012.pdf).
