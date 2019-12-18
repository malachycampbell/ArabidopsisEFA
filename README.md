<h1 align="center">
  <img alt=" Examining the relationships between phenotypic plasticity and local environments with genomic structural equation models" width = "1711.846" height = "200" src = Title.svg>
</h1>

[Malachy Campbell](https://malachycampbell.github.io/), Haipeng Yu, Medhi Momen, [Gota Morota](http://morotalab.org/)

## Abstract
Environmental association analyses (EAA) seek to identify genetic variants associated with local adaptation by regressing local environmental conditions at collection sites on genome-wide polymorphisms. The rationale is that environmental conditions impose selective pressure on trait(s), and these traits are regulated in part by variation at a genomic level. Here, we present an alternative multivariate genomic approach that can be utilized when both phenotypic and environmental data are available for the population. This framework utilizes Bayesian networks (BN) to elucidate interdependancies between local environmental conditions and empirical phenotypes, and jointly estimates the direct and indirect genetic covariances between empirical phenotypes and environmental conditions using a mixed-effects structural equation model (SEM). Direct genomic covariance between empirical phenotypes and environmental conditions may provide insight into whether QTL that affect adaptation to an environmental gradient also affects the observed phenotype. To demonstrate the utility of this approach, we leveraged two existing datasets consisting of 55 climate variables for 1,130 Arabidopsis accessions and empirical phenotypes for fitness and phenology collected on 515 accessions in two common garden locations in Europe. BN showed that plasticity for fitness and phenology was highly dependant on local environmental conditions. Moreover, genomic SEM revealed relatively high positive genomic correlation between plasticity in fitness and environmental variables that describe the favorability of the local environment for plant growth, indicating the presence of common QTL or independent QTL that are tightly linked. We believe the frameworks presented in this manuscript can provide new insights into the genetic basis of local adaptation.

## Background
This repo contains all the code and data used for the manuscript: "Examining the relationships between phenotypic plasticity and local environments with genomic structural equation models". All phenotypic and genotypic data has been previously published.

## Table of Contents 
* **1. Factor analysis**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/EFA.CFA.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/EFA.CFA.Rmd)
  
* **2. Estimating plasticity**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/FW.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/FW.Rmd)
  
* **3. Predicting breeding values using MTM**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/MTM.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/MTM.Rmd)
  
* **4. Bayesian network**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/BayesianNetwork.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/BayesianNetwork.Rmd)
 
* **5. Recursive model**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/RecursiveModel.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/RecursiveModel.Rmd)
  
* **6. Supplemental data**
  - [html output](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/htmlMarkdown/SupplementalData.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/ArabidopsisEFA/tree/master/Rmarkdown/SupplementalData.Rmd)
 
  
 ## Funding
*Funding for this project was provided startup from from VT awarded to GM*

---
