Welcome to episoft, SAS IML code for epidemiologic analysis by two-stage semi- or empirical-Bayes hierarchical modeling.

## Purpose
The purpose of this site is to distribute SAS IML code for epidemiologic analysis by two-stage semi- or empirical-Bayes hierarchical modeling.  This site complements the manuscript "Software for hierarchical modeling of epidemiolgic data" (Witte et al., Epidemiology 1998;9:563-566).  In particular, we expand on the paper's Appendix, providing SAS IML code corresponding to the diet and breast cancer application first presented in Witte et al. (Epidemiology 1994; 5:612-621).

## Use
To use this code, one inputs conventional coefficient and covariance-matrix estimates (e.g., from any logistic software package) and second-stage data (i.e., the second-stage design matrix Z, and, if semi-Bayes, pre-specified second-stage variance values).   As currently written, the code allows one to reproduce our diet and breast cancer hierarchical modeling analysis.  Hence, in addition to the code, we give the conventional logistic regression coefficients and corresponding covariance matrix, as well as the second-stage design matrix and second-stage variance (tau^2) values.

To undertake hierarchical modeling with this SAS code and data, download the repository files and run them in SAS.

## In this repository    
1. code "hm_sas2.txt"
1. first-stage coefficient estimates "bb.txt"
1. first-stage covariance matrix "bbcov.txt"
1. second-stage design matrix "zmatrix2.txt"
1. second-stage variance values "tau2.txt"
1. a vector of unit increases "s.txt".

