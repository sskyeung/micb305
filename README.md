# micb305 Team 8
This repository is created for MICB 305 25WT2 (Department of Microbiology and Immunology, University of British Columbia, Vanoucver BC), and contains all code ncessary to reproduce "Low dietary vitamin C intake is associated with the presence of pro-inflammatory taxa and the enrichment of oxidative stress related functional pathways in Parkinson’s disease with no correlation to age of onset". 

Authors/Contributors: Denali Gordon, Riko Murata, James Nam, Jeremy Siu, Kyle Yeung

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
|
|-- Results -- contains all outputs, figures and tables used in the manuscript
|   |
|   |-- Figures -- contains all figures used in the manuscript
|   |
|   |-- Table -- contains all tables used in the manuscript
|
|-- Meeting_notes -- meeting notes and agenda with MICB_305 teaching team
```


## Acknowledgement
A special thanks to Avrial Metcalfe-Roach and Claire Sie for their guidance throughout the project. 



