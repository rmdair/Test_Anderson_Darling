<h1 align="center">Anderson-Darling Test</h1>
<h2 align="center">Theoretical Analysis and Practical Implementation</h2>     

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python" alt="Python (illustrative)">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter" alt="Illustrative Notebook">
  <img src="https://img.shields.io/badge/License-MIT-darkgreen?style=flat-square" alt="License">
</p>

<p align="center">
  <img src="../assets/banner.webp" alt="Banner" width="60%">
</p>

This project provides a structured study of the Anderson-Darling test, 
a statistical goodness-of-fit test used to assess whether a sample 
follows a specified probability distribution.

The analysis is based on the seminal papers by T.W. Anderson and D.A. Darling, 
and explores the test’s construction, asymptotic properties, and applications.

Additionally, a practical Python implementation illustrates its mechanics 
and sensitivity to distributional deviations.

---

## Resources

### Theoretical Analysis

The document covers:

- Historical background and development since 1954  
- Mathematical construction of the statistic  
- Comparison with other goodness-of-fit tests  
- Advantages and limitations

Access the documents:

- [Theoretical Analysis – English version (PDF)](../docs/Anderson-Darling-Test-Study.pdf)
- [Theoretical Analysis – French version (PDF)](../docs/Test-Anderson-Darling-Etude.pdf)

### Practical Implementation

A pedagogical Python implementation including:

- Construction of the statistic from its integral form  
- Formulation using order statistics  
- Tail weighting analysis  
- Comparison with the Kolmogorov–Smirnov test  

Access the source code:

- [Notebook (ipynb)](../src/anderson_darling_practical.ipynb)

## Installation and Usage

To explore this project locally:

```bash
# Clone the repository
git clone https://github.com/rmdair/Anderson-Darling-Goodness-of-Fit.git

# Navigate to the project folder
cd Anderson-Darling-Goodness-of-Fit
```

## References  

- Anderson, T. W., & Darling, D. A. (1952). *Asymptotic theory of certain ''goodness of fit'' criteria based on stochastic processes*. Annals of Mathematical Statistics, 23, 193-212.  
- Anderson, T. W., & Darling, D. A. (1954). *A Test of Goodness of Fit*. Journal of the American Statistical Association, 49(268), 765-769.  
- Stephens, M. A. (1979). *The Anderson-Darling Statistic*. [Technical Report](https://apps.dtic.mil/sti/pdfs/ADA079807.pdf).  