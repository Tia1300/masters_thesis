# Multivariate Limit Theorems and Algebraic Generating Functions
This repository contains code associated with the author's Master's Thesis, "Multivariate Limit Theorems and Algebraic Generating Functions".

The code in this repository is separated into three files. The first two files are related to Chapter 3 from the thesis and the third is associated to Chapter 4. All important functions from the files, as well as necessary background and examples is found in Chapter 5 of the thesis.

The first file, "Multivariate Limit Theorems - Companion Notebook", allows one to compute a Local Central Limit theorem for a rational function satisfying the conditions of Theorem 47 in the thesis. We also apply the code to the examples, and perform computations corresponding to sections of the proof given in the thesis.

The second file, "Package for Automatic LCLTs", gives code that takes a rational function and algorithmically checks whether its coefficients satisfy a Local Central Limit Theorem using Proposition 38 in the thesis. This notebook thus works in a more general setting, but the code takes longer as it must prove the existence of minimal critical points.

The final file, "Algebraic Generating Functions Examples", is a companion notebook for Chapter 4 of the thesis, modified from the upcoming paper, "Algebraic Generating Functions and Analytic Combinatorics in Several Variables", by Torin Greenwood, Stephen Melczer, Tiadora Ruza and Mark C. Wilson. This notebook provides functions to allow one to compute a embeddings of an algebraic generating function as the diagonal of a rational generating function using either Denef & Lipshitz embedding method or Safonov's algorithm. As well, this notebook provides code related to the examples found in Chapter 4 of the thesis.
