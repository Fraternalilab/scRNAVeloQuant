# Quantifying composite summary of RNA velocity between cell clusters in single-cell RNAseq data

This repository contains the code used to quantify and summarise individual RNA streams (computed using, e.g. [velocyto](http://velocyto.org/)) into a composite score that quantifies transition between two clusters. This is used in the following piece of work to evaluate the transition between different B cell subsets in a single-cell RNAseq dataset of peripheral B cells ('Pure' dataset).

The R markdown file contains all necessary functions to calculate and plot these estimates. Necessary input files for the 'Pure' dataset can be downloaded from ArrayExpress from [here]().

The associated publication is now on published in [Frontiers In Immunology](https://dx.doi.org/10.3389/fimmu.2021.602539) (previous version in [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.09.03.281527v1)). If you use it please cite:

Stewart AT, Ng J, Wallis G, Tsioligka V, Fraternali F & Dunn-Walters DK. (2021). Single-cell transcriptomic analyses define distinct peripheral B cell subsets and discrete development pathways. *Frontiers In Immunology* 12:743. doi: 10.3389/fimmu.2021.602539 

Or as a BibTex format entry:
```
@ARTICLE{10.3389/fimmu.2021.602539,
AUTHOR={Stewart, Alexander and Ng, Joseph Chi-Fung and Wallis, Gillian and Tsioligka, Vasiliki and Fraternali, Franca and Dunn-Walters, Deborah K.},   	 
TITLE={Single-Cell Transcriptomic Analyses Define Distinct Peripheral B Cell Subsets and Discrete Development Pathways},     
JOURNAL={Frontiers in Immunology},      
VOLUME={12},      
PAGES={743},     
YEAR={2021},      
URL={https://www.frontiersin.org/article/10.3389/fimmu.2021.602539},       
DOI={10.3389/fimmu.2021.602539},      
ISSN={1664-3224},   
}
```
