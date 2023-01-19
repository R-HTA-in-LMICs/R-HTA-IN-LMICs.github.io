---
title: "Resources"
permalink: /resources/
layout: single
author_profile: false
logo: /assets/images/avatar.png
toc: true
toc_label: "Resources"
toc_icon: "chalkboard-teacher"
---
## R Programming
**Note:** this page is continuously updated as more learning resources are developed.
{: .notice--info}

### Basic
An important process of decision modelling is the multiplication of matrices and other numeric objects. To get to grips with basic R syntax and object manipulation, we have developed several documents for this purpose, to help you develop the basic skills needed to master R-based health economic decision models. 

The [I2R](https://github.com/R-HTA-in-LMICs/June-Workshop/blob/main/R/Intro2R.R) script provides code to freely run and explore on your own. The aim is to help you get started on the basics of R input and output and to learn how to effectively manipulate [objects](https://rstudio-education.github.io/hopr/r-objects.html) in the R language. Go ahead and use it at your leisure! Tinkering is the best way to learn, especially when learning something like the R language which, initially, may seem daunting.

Our [introductory 2022 tutorial](https://github.com/R-HTA-in-LMICs/June-Workshop) has additional documents and exercises for you to go through. Check it out!

### Intermediate
An intermediate, and important, skill in health economic decision modelling is the development of time-dependent models. Our intermediate resources guide you through this important concept, and to apply within R. The following sections below provide a breakdown of the primary documents and guidance on how to use them for your own personal training. The tutorial is based on the open-source DARTH group materials.

-   Alarid-Escudero F, Krijkamp EM, Enns EA, Yang A, Hunink MGM, Pechlivanoglou P, Jalal H. [A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example](https://arxiv.org/abs/2108.13552). arXiv:2108.13552v2. 2022:1-37.

The [`analysis`](https://github.com/R-HTA-in-LMICs/September-Workshop/tree/main/analysis) folder includes the scripts with all the code, description and comments to reproduce the CEA, probabilistic sensitivity analysis (PSA) and generation of epidemiological measures of the manuscript:

-   [`cSTM_time_dep_simulation.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/analysis/cSTM_time_dep_simulation.R): Code to replicate all simulation-time dependent cSTMs analyses of the manuscript.
-   [`cSTM_time_dep_state_residence.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/analysis/Extra%20material%20-%20cSTM_time_dep_state_residence/cSTM_time_dep_state_residence.R): Code to replicate all state-residence time dependent cSTMs analyses of the manuscript.
-   [`cSTM_torn_diag.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/analysis/cSTM_torn_diag.R): Code to implement a tornado diagram analysis for Deterministic Sensitivity Analysis.

The R scripts require loading functions that synthesize cSTMs outputs and conduct several sensitivity analyses included in the [`R`](https://github.com/R-HTA-in-LMICs/September-Workshop/tree/main/R) folder:

-   [`Funtions.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/R/Functions.R): Functions to generate epidemiological measures from time-dependent cSTMs.
-   [`Functions_cSTM_time_dep_simulation.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/R/Functions_cSTM_time_dep_simulation.R): These functions wrap the simulation-time dependent cSTMs, compute CEA and epidemiological measures, and generate probabilistic sensitivity analysis (PSA) input datasets.
-   [`Functions_cSTM_time_dep_state_residence.R`](https://github.com/R-HTA-in-LMICs/September-Workshop/blob/main/R/Functions_cSTM_time_dep_state_residence.R): These functions wrap the state-residence time dependent cSTMs, compute CEA and epidemiological measures, and generate probabilistic sensitivity analysis (PSA) input datasets.

### Advanced
Communication of our findings is an essential part of the decision modelling process in health economics. Although advanced, developing interactive models can help decision makers understand how your model works while also having fun - without the finickiness of code!

Our [advanced 2022 tutorial](https://github.com/R-HTA-in-LMICs/Advanced-Tutorial-2022) provides a basic script to deploy and use a five-state Markov model, developed to assess the comparative cost-effectiveness of anti-retrovirals for HIV/AIDS. The code is time-dependent and probabilistic ready. So, go ahead, explore, and have some fun with it!

See an example of the Shiny app [here](https://r-htalmics.shinyapps.io/hiv_model/).

## R-HTA Workshops
{% include video id="FiWrOK4CFlE" provider="youtube" %}