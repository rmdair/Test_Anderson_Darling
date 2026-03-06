<h1 align="center">Test d'Anderson-Darling</h1>
<h2 align="center">Analyse théorique et implémentation pratique</h2>     

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/License-MIT-darkgreen?style=flat-square" alt="License">
</p>

<p align="center">
  <img src="assets/banner.webp" alt="Banner" width="60%">
</p>

Ce projet présente une étude structurée du test d'Anderson-Darling, 
un test de conformité statistique permettant d’évaluer si un échantillon 
suit une loi de probabilité donnée.

L’analyse s’appuie sur les articles fondateurs de T.W. Anderson et D.A. Darling et explore la construction du test, ses propriétés asymptotiques ainsi que ses applications.

En complément, une implémentation pratique en Python illustre ses mécanismes et sa sensibilité aux écarts de distribution.

---

## Ressources

### Analyse théorique 

Le document présente :

- Historique et évolution depuis 1954  
- Construction mathématique du statisticien  
- Comparaison avec d'autres tests de conformité  
- Avantages et limites

Accès aux documents :

- [Analyse théorique – Version française (PDF)](./docs/Test-Anderson-Darling-Etude.pdf)
- [Theoretical analysis – English version (PDF)](./docs/Anderson-Darling-Test-Study.pdf) 

### Implémentation pratique

Implémentation pédagogique en Python incluant :

- Construction du statisticien à partir de la forme intégrale  
- Formulation via les statistiques d’ordre  
- Analyse de la pondération des queues  
- Comparaison avec le test de Kolmogorov–Smirnov  

Accès au code source :

- [Notebook (ipynb)](./src/anderson_darling_practical.ipynb)

## Installation et utilisation

Pour explorer ce projet localement :

```bash
# Cloner le dépôt
git clone https://github.com/rmdair/Anderson-Darling-Goodness-of-Fit.git

# Accéder au dossier du projet
cd Anderson-Darling-Goodness-of-Fit
```


## Références  

- Anderson, T. W., & Darling, D. A. (1952). *Asymptotic theory of certain ''goodness of fit'' criteria based on stochastic processes*. Annals of Mathematical Statistics, 23, 193-212.  
- Anderson, T. W., & Darling, D. A. (1954). *A Test of Goodness of Fit*. Journal of the American Statistical Association, 49(268), 765-769.  
- Stephens, M. A. (1979). *The Anderson-Darling Statistic*. [Technical Report](https://apps.dtic.mil/sti/pdfs/ADA079807.pdf).  