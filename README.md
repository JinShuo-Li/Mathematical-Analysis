# Information

**Author:** Li Jinshuo (Shanghai Jiao Tong University)  
**Date:** 2026.1.3

## 📖 Overview

This project is a set of LaTeX notes. It provides a framework for Mathematical Analysis, transitioning from the axiomatic foundations of number systems to advanced calculus concepts.

## 📑 Table of Contents

The document is structured into the following key sections:

* **Chapter 0: Basic Knowledge and Notations**
    * Foundations of the number system.
    * Axiomatic construction of Natural Numbers, Integers, Rational Numbers, and Real Numbers via Dedekind Cuts.
    * Introduction to Complex Numbers.
* **Section 1: Sequence Limit and The Properties of Real Numbers**
    * Formal definition of limits.
    * The Completeness of the Real Number System.
    * Monotone Convergence Theorem and Cauchy Convergence Criterion.
    * Stolz Theorem.
* **Section 2: Derivatives and Related Theorems**
    * Differentiation, Uniform Continuity, and the Chain Rule.
    * Mean Value Theorems (Rolle, Lagrange, Cauchy).
    * L'Hôpital's Rule.
    * Taylor Expansion and Maclaurin Series.
* **Section 3: Integration**
    * Indefinite Integration (Substitution, By Parts, Partial Fractions).
    * Definite Integration (Riemann Sums, Darboux Sums).
    * The Fundamental Theorem of Calculus (Newton-Leibniz).
    * Improper Integrals (Type I & II, Convergence Tests).

## 🛠️ Technical Details

This document uses the `article` class (modified from a `book` structure) and relies on several standard LaTeX packages for mathematical formatting and visualization.

### Prerequisites

To compile this document, you need a TeX distribution (like TeX Live, MiKTeX, or MacTeX) with the following packages installed:

* **Math:** `amsmath`, `amssymb`, `amsthm`
* **Graphics:** `tikz`, `float`, `caption`
* **Code/Listing:** `listings`, `xcolor`
* **Layout:** `geometry`, `parskip`, `booktabs`, `epigraph`

### Compilation

You can compile the `main.tex` file using `pdflatex`.

**Using Terminal:**
```bash
pdflatex main.tex
pdflatex main.tex  # Run twice to ensure TOC and references are correct
