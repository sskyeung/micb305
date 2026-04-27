# micb305 Team 8
## Low dietary vitamin C intake is associated with the presence of pro-inflammatory taxa and the enrichment of oxidative stress related functional pathways in Parkinson’s disease with no correlation to age of onset
This repository is created a microbiome research project for MICB 305: Data Science in Microbiology and Immunology Research 25WT2 (Department of Microbiology and Immunology, University of British Columbia, Vanoucver BC). It contains all codes, analyses and outputs ncessary to reproduce our research. 

**Authors/Contributors:** Denali Gordon, Riko Murata, James Nam, Jeremy Siu, Kyle Yeung

## Project Overview
Parkinson’s Disease (PD) is a progressive neurodegenerative disorder characterized by the loss of dopaminergic neurons and the accumulation of misfolded α-synuclein proteins. While dietary antioxidants like vitamin C can neutralize reactive oxygen species, clinical evidence of their neuroprotective efficacy remains inconsistent. This study explores the gut-brain axis as a potential mediator of these effects. PD is characterized by specific gut dysbiosis, and since vitamin C is known to modulate similar taxa, investigating the interaction between antioxidant intake and the PD microbiome may clarify how diet influence disease pathology and timing of age of onset. 

We aim to explore how dietary vitamin C influences the gut microbiome composition in patients with PD and whether these microbial shifts correlate with the age of disease onset. Using 16s rRNA sequencing data from a cohort of 197 PD patients, the study identifies specific bacterial taxa and functional metabolic pathways associated with antioxidant intake. 

## Research Question
Does dietary vitamin C modulate the gut microbiome in a way that significantly influences the age of onset in Parkinson's Disease patients?

## Dataset
Data was sourced from **Cristae et al. (2020)** study, comprising faecal 16s rRNA sequences and comprehensive dietary metadata from 197 PD patients. The metadata includes intake levels of eight primary antioxidants and cliical records of disease age of onset.

## Relevant Documents
Proposal:
https://ubcca-my.sharepoint.com/:w:/r/personal/dgordo05_student_ubc_ca/Documents/MICB_305_proposal.docx?d=w9e17d40f9a2545d48d65e9a237ae4ac4&csf=1&web=1&e=30xfP3

Presentation Slides:
https://ubcca-my.sharepoint.com/:p:/g/personal/rmurata_student_ubc_ca/IQAQyVowzAj7TJEQHWp4Q4cEAaxBaiYWOCawLBpLfkEuQBk?e=JhNsAe

Manuscript Draft:
https://ubcca-my.sharepoint.com/:w:/g/personal/rmurata_student_ubc_ca/IQDo9oW-kJ9lS5EAPJb-1mfHAUal7mWx9I_K3j_V22Q9fiw?e=NjXsCZ

## Directory Tree
The following gives an overall structure of the repository. 

```
micb305
|
|-- R_Scripts -- contains all R code used in the manuscript
|   |
|   |-- alpha_diversity -- contains all R code used for running alpha shannon diversity
|   |
|   |-- beta_diversity -- contains all R code used for running beta (bray-curtis) diversity
|   |
|   |-- correlation_matrix -- contains all R code used for running Spearman correlation matrix
|   |
|   |-- data_wrangling -- contains all R code used for wrangling data from QIIME2 output
|   |
|   |-- differential_abundance -- contains all R code used for running LinDa differential abundance 
|   |
|   |-- functional_analysis -- contains all R code used for functional analysis based on PICRSt2 output
|   |
|   |-- indicator_taxa_abundance -- contains all R code used for calculating relative abundance of indicator taxa 
|   |
|   |-- indicator_taxa_analysis -- contains all R code used for running Multipatt indicator taxa anlaysis
|   |
|   |-- random_forest -- contains all R code used for running Random Forest analysis 
|
|-- Results -- contains all outputs, figures and tables used in the manuscript
|   |
|   |-- Figures -- contains all figures used in the manuscript
|   |
|   |-- Table -- contains all tables used in the manuscript
|
|-- data -- Data used for analysis in R 
|   
|-- Meeting_notes -- meeting notes and agenda with MICB_305 teaching team
```


## Acknowledgement
A special thanks to Avril Metcalfe-Roach and Claire Sie for their guidance throughout the project. Additionally, the R function used to generate error bars for the differential abundance analysis of predicted pathways was provided by Avril Metcalfe-Roach. This code was essential for visualizing the LinDa output within this repository. Source code for this function is stored under R_Scripts/functional_analysis



