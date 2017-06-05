[**Latest Release**](https://github.com/MMAP/MMAP-releases-issues-Q-and-A/releases/latest) &nbsp; &nbsp; [**Issues and Q&A**](https://github.com/MMAP/MMAP-releases-issues-Q-and-A/issues)

## MMAP: Mixed Model Analysis for Pedigrees and Populations

MMAP is an optimized and flexible mixed model analysis platform that incorporates a wide range of covariance structures such as additive, dominance, epistasis, maternal and imprinting using pedigree and/or genotype data and also allows users to define their own covariance structures. Likelihood calculations use multi-threaded optimized matrix libraries to handle multiple random effects. MMAP can import data from a variety of imputation programs to avoid data manipulation and IBS/IBD programs to build covariance structures.

MMAP uses a fast low-memory method to calculate additive and dominant genetic covariance structures using SNP data, which can be quite challenging for large data sets. For polygenic SNP analysis MMAP can store SNP-covariance products to reduce the complexity subsequent analyses with the same subjects to linear regression, independent of phenotype or covariates. 

### Installation

MMAP is compiled with the Intel Math Kernel library for the Unix/Linux environment and uses BLAS and LAPACK libraries. To ensure compatibility only a static executable is currently available. After download, be sure to make the file executable. [Click here to download MMAP](https://github.com/MMAP/MMAP-releases-issues-Q-and-A/releases/latest).

### MMAP website

Visit the [MMAP website](https://MMAP.github.io/) for the complete guide to using MMAP.
