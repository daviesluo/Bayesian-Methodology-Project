# Bayesian Analysis of Cross Country Race Times

A comprehensive Bayesian analysis project examining race times in the North East Harrier League (NEHL) through multiple Bayesian modeling approaches: Non-conjugate Models, Normal Linear Regression, Interaction Models, and Hierarchical Models.

## Project Overview
- Bayesian statistical analysis of cross-country race performance data
- Investigation of multiple factors affecting race times
- Comparative analysis of different Bayesian modeling approaches
- In-depth study of age group, pack classification, and course effects

## Key Features
- Data preprocessing and exploratory analysis
- Implementation of multiple Bayesian models:
  - Non-conjugate Models
  - Normal Linear Regression Models
  - Interaction Models
  - Hierarchical Models with random effects
- MCMC diagnostics and convergence analysis
- Posterior distribution analysis
- Visual representations of model outputs

## Repository Contents
- Project reqirement with theoretical questions 
- Raw data
- Project report detailing methodology and findings
- R code for Bayesian analysis and visualisation
- Presentation slides
- Presentation video

## Technical Stack
### Core Technologies
- R Statistical Software (Version 4.x+)

### Key R Libraries
- `rjags`: For Bayesian modeling using JAGS
- `coda`: For MCMC diagnostics and analysis
- `tidyverse`: For data manipulation and visualization
- `ggplot2`: For creating statistical graphics
- `corrplot`: For correlation visualization
- `knitr`: For report generation

### Statistical Methods & Techniques
- Markov Chain Monte Carlo (MCMC) sampling
- Bayesian model diagnostics
  - Gelman-Rubin statistics
  - Effective sample size calculations
  - Trace plot analysis
- Posterior distribution analysis
- Hierarchical modeling with random effects
- Non-conjugate prior specifications

## Results & Findings
### Model Performance
- Hierarchical model demonstrated superior capability in capturing nested data structures
- Strong convergence achieved across all models (Gelman-Rubin statistics ≈ 1)
- High effective sample sizes indicating reliable posterior estimates

### Key Insights
- Significant age-related patterns in race performance
- Pack classification emerged as a crucial determinant of race times
- Course-specific effects identified through hierarchical modeling
- Environmental factors (temperature, wind) showed measurable impacts
- Interaction effects revealed complex relationships between variables
