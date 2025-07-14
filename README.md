# The Effect of Chile’s Neoliberal Reforms in the 1970s

**Author**: Christopher Hynes  
**Institution**: University of South Carolina Honors College  
**Date**: May 2022

## Overview

This repository contains the final version of my undergraduate honors thesis, which investigates the long-term economic impact of Chile's neoliberal reforms under Augusto Pinochet in the 1970s. The study uses the synthetic control method to estimate how Chile’s GDP per capita would have evolved in the absence of Pinochet’s structural reforms.

The analysis concludes that the reforms had a significant and lasting positive effect on Chile’s economic trajectory. Various robustness checks confirm the credibility of the results.

## Contents

- `The Effect of Chile’s Neoliberal Reforms in the 1970s.pdf` — The full written thesis  
- `Thesis Code.Rmd` — The R Markdown file with code used for data analysis and visualizations  
- `README.md` — This file

## Methods

The study uses the **synthetic control method** as proposed by Abadie and Gardeazabal (2003), employing a cross-country panel dataset from the World Bank (1960–2019).  
Key packages and tools used:  
- `Synth` (R package)  
- World Bank World Development Indicators  
- RMarkdown for code and report integration

## Key Findings

- Pinochet’s reforms correspond to a **76% higher GDP per capita** in 2019 compared to the synthetic counterfactual.
- The growth effect appears **starting in the early 1990s**, following Chile’s transition to democracy.
- Robustness checks across donor pools, predictors, and placebo studies support the validity of the findings.

## Citation

If referencing this work, please use:

> Hynes, Christopher. _The Effect of Chile’s Neoliberal Reforms in the 1970s_. University of South Carolina Honors College, 2022.

## License

This repository is provided for academic and educational use. Please contact me if you'd like to use the data or methods for your own research.
