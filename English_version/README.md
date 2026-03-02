<div align="center">
    <h1>The Anderson–Darling Test</h1>
    <h2>Theoretical Analysis and Practical Implementation</h2>
    &nbsp;

</div>      

## Overview

This project provides a detailed overview of the construction of the Anderson–Darling test, a goodness-of-fit test used to assess whether a sample follows a specified probability distribution.

The study is based on the foundational papers by T. W. Anderson and D. A. Darling, with an exploration of the test’s construction, its asymptotic properties, and its applications.

In addition to the theoretical analysis, the project also includes a practical implementation of the test to illustrate its underlying mechanisms and its sensitivity to distributional departures.

&nbsp;

## Project Content

### Theoretical Analysis  

The document covers:
- The **historical development** of the test since its introduction in 1954  
- Its **mathematical construction**  
- A **comparison with other goodness-of-fit tests**  
- The **advantages and limitations** of the Anderson–Darling test  

➡️ [Theoretical analysis of the Anderson–Darling test (PDF)](../docs/Study_Anderson_Darling.pdf)

### Practical Implementation  

A pedagogical implementation of the test in Python, including:
- Construction of the statistic from its integral form  
- Implementation via order statistics  
- Analysis of tail weighting  
- Comparison with Kolmogorov–Smirnov  

➡️ [Notebook (ipynb)](../src/anderson_darling_practical.ipynb)

&nbsp;

## References  

- Anderson, T. W., & Darling, D. A. (1952). *Asymptotic theory of certain ‘goodness of fit’ criteria based on stochastic processes*. Annals of Mathematical Statistics, 23, 193-212.  
- Anderson, T. W., & Darling, D. A. (1954). *A Test of Goodness of Fit*. Journal of the American Statistical Association, 49(268), 765-769.  
- Stephens, M. A. (1979). *The Anderson-Darling Statistic*. [Technical Report](https://apps.dtic.mil/sti/pdfs/ADA079807.pdf).  
