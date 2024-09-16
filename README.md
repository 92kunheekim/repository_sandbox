# README

# Acute Myeloid Leukemia Heatmap Analysis

## Project Overview

This project analyzes RNA-seq data from acute myeloid leukemia (AML) model mice using the RefineBio dataset [2]. The goal is to create a clustering heatmap to visualize gene expression patterns across different AML subtypes and treatments.

## Software Requirements

To run this project, you'll need:

- R statistical computing environment
- RStudio IDE (optional but recommended)
- Various R packages including:
  - pheatmap
  - magrittr
  - readr
  - dplyr
  - tibble
  - sessioninfo

## Last Updated

This project was last updated on October 2021.

## Goals

The primary objectives of this analysis are:

1. To load and preprocess RNA-seq data from RefineBio for AML model mice.
2. To identify genes with high variability across samples.
3. To create an annotated clustering heatmap visualizing gene expression patterns.
4. To explore relationships between AML subtype mutations and gene expression profiles.

## Installation Instructions

1. Clone this repository to your local machine.
2. Open RStudio and navigate to the project directory.
3. Install required packages by running the following command in the R console:

```r
install.packages(c("pheatmap", "magrittr", "readr", "dplyr", "tibble", "sessioninfo"))
```

4. Run the R script to perform the analysis.

## Usage

1. Ensure you have the latest version of R installed.
2. Follow the installation instructions above.
3. Open the R script in RStudio and execute it cell by cell or all at once.

## Output

The script generates several outputs:

- A TSV file containing genes with high variability (`top_90_var_genes.tsv`)
- An annotated clustering heatmap saved as `aml_heatmap.png`
- Session information for reproducibility

## References

[2] Shih, A. H., et al. (2017). IDH mutation is sufficient to establish the glioma-cognitive continuum. Nature, 548(7666), 166-170. https://pubmed.ncbi.nlm.nih.gov/28193779/

Note: This README is based on the provided code snippet. You may need to add or modify sections depending on the full scope and complexity of your project.

Citations:
