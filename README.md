# Quantifying composite summary of RNA velocity between cell clusters in single-cell RNAseq data

This repository contains the code used to quantify and summarise individual RNA streams (computed using, e.g. [velocyto](http://velocyto.org/)) into a composite score that quantifies transition between two clusters. This is used in the following piece of work to evaluate the transition between different B cell subsets in a single-cell RNAseq dataset of peripheral B cells ('Pure' dataset).

The R markdown file contains all necessary functions to calculate and plot these estimates. Necessary input files for the 'Pure' dataset can be downloaded from ArrayExpress from [here]().

The associated publication is now son [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.09.03.281527v1). If you use it please cite:

Stewart AT, Ng J, Wallis G, Tsioligka V, Fraternali F & Dunn-Walters DK. (2020). Single-cell transcriptomic analyses define distinct peripheral B cell subsets and discrete development pathways. *bioRxiv* doi: 10.1101/2020.09.03.281527 

Or as a BibTex format entry:
```
@article {Stewart2020.09.03.281527,
	author = {Stewart, Alexander and Ng, Joseph and Wallis, Gillian and Tsioligka, Vasiliki and Fraternali, Franca and Dunn-Walters, Deborah},
	title = {Single-cell transcriptomic analyses define distinct peripheral B cell subsets and discrete development pathways},
	year = {2020},
	doi = {10.1101/2020.09.03.281527},
	journal = {bioRxiv}
}```
