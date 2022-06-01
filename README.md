# sspbc
Single-Sample Predictors for Breast Cancer

Single-Sample Predictors for Breast Cancer (sspbc) include functions and models to assign classes to breast cancer samples. It works on raw gene expression data.

The included single-sample predictor (SSP) models were developed using gene expression data from RNAseq generated using HiSat/StringTie. Detailed description on training and validation of the provided SSP models is available in the manuscript by Staaf J. et al. medRxiv 2021.12.03.21267116 (https://doi.org/10.1101/2021.12.03.21267116). Training was performed using the previously described AIMS method from Paquet and Hallett (2014) J Natl Cancer Inst 107(1):357 using scripts available from the AIMS GitHub repository (https://github.com/meoyo/AIMS).

Description on how to use sspbc with examples and testdata is provided with the R package. 

For citation use Staaf J. et al. medRxiv 2021.12.03.21267116 (https://doi.org/10.1101/2021.12.03.21267116).

# Installation Instructions

**sspbc** depends on R packages **e1071**, **methods**, **stats**, and **grid**. Make sure to install these dependencies before installing **sspbc**.

To use the sspbc R package download and install from the provided <a href="https://github.com/StaafLab/sspbc/blob/main/package/sspbc_1.0.tar.gz">source package</a>.

### Install from terminal prompt

<code>R CMD INSTALL sspbc_1.0.tar.gz</code>

### Install from local source file from R prompt

<code>install.packages("~/Downloads/sspbc_1.0.tar.gz", repos = NULL, type="source")</code>

### Install from the R app menu

Go to 'Packages and Data' and select 'Package Installer'.

Under Packages Repository select 'Local Source Package' and click 'Install...' then browse to find the downloaded source package file.
