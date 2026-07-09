# Air Pollution and the Serum Metabolome in PD

This repository hosts the code and methodology used for conducting the statistical analyses presented in our research paper, published in npj Parkinson's Disease, 2026.

## Overview

The purpose of this repository is to provide transparency and reproducibility for the computational analyses carried out in our study of long-term ambient air pollution exposures (PM2.5, CO, and NO2) and the untargeted serum LC-HRMS metabolome in Parkinson's disease patients and population-based controls.

## Contents

- Metabolome-Wide Association Study (MWAS): R code for fitting LIMMA models across exposures, modes, and PD status, and for flagging signals replicated across study waves (PEG1, PEG2).
- PD vs. Control Comparison: Code to categorize features by significance in cases and controls and to estimate stratified correlations of effect sizes.
- Pathway Enrichment: Code to combine *Mummichog* output across exposures and filter to significant pathways.
- Metabolite Annotation: Code for in-house library matching, *Mummichog* matched-compound annotation with KEGG name lookup, and *xMSannotator* multilevel annotation.

## Citation

Kwon, D., Paul, K.C., Lin, Y. et al. Untargeted serum metabolomics and air pollution in Parkinson’s disease. npj Parkinsons Dis. (2026). https://doi.org/10.1038/s41531-026-01451-3
