# Master's thesis physics
Source code and PDF of my master's thesis, completed in September 2019.
## Abstract
We propose a method for learning a quantum probabilistic model of a perceptron. By considering a cross entropy between two density matrices, we can learn a model that takes noisy output labels into account while learning. A multitude of proposals already exist that aim to utilize the curious properties of quantum systems to build a quantum perceptron, but these proposals rely on a classical cost function for the optimization procedure. We demonstrate the usage of a quantum equivalent of the classical log-likelihood, which allows for a quantum model and training procedure. We show that this allows us to better capture noisiness in data compared to a classical perceptron. By considering entangled qubits we can learn nonlinear separation boundaries, such as XOR. We outline possible extensions of this model and consider the constraints of physical systems for learning. The work in this thesis is the culmination of one and a half year of research in the Biophysics group at Radboud University. The most important results are summarized in a *Physical Review A* paper \[[1](https://www.doi.org/10.1103/PhysRevA.100.020301)\].
## Compiling Source

In bash, using **pdfTeX 3.14159265-2.6-1.40.19 (TeX Live 2018)** and **BibTeX 0.99d (TeX Live 2018)** execute
```bash
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```
to get the thesis in `main.pdf`
