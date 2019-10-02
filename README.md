# Master Thesis, September 2019
Source code and PDF of my master's thesis.

## Compiling Source

In bash, using **pdfTeX 3.14159265-2.6-1.40.19 (TeX Live 2018)** and **BibTeX 0.99d (TeX Live 2018)** execute
```bash
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```
to get the thesis in main.pdf