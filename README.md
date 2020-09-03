# Quantifying composite summary of RNA velocity between cell clusters in single-cell RNAseq data

This repository contains the code used to quantify and summarise individual RNA streams (computed using, e.g. [velocyto](http://velocyto.org/)) into a composite score that quantifies transition between two clusters. This is used in the following piece of work to evaluate the transition between different B cell subsets in a single-cell RNAseq dataset of peripheral B cells ('Pure' dataset).

The R markdown file contains all necessary functions to calculate and plot these estimates. Necessary input files for the 'Pure' dataset can be downloaded from ArrayExpress from [here]().

The associated publication is now in bioRxiv [here](). If you use it please cite:

Stewart AT, Ng J, Wallis G, Tsioligka V, Fraternali F & Dunn-Walters DK. (2020). Single-cell transcriptomic analyses define distinct peripheral B cell subsets and discrete development pathways. *Submitted*

Or as a BibTex format entry:
```
@ARTICLE {,
    author  = "Alexander T. Stewart and Joseph Ng and Gill Wallis and Vasiliki Tsioligka and Franca Fraternali and Deborah K. Dunn-Walters",
    title   = "Single-cell transcriptomic analyses define distinct peripheral B cell subsets and discrete development pathways",
    journal = "Submitted",
    year    = "2020"
}
```
