# Supplementary Data for "Sparse modeling of interactions enables fast detection of genome-wide epistasis in biobank-scale studies"

This repository provides the source code of the sparse marginal epistasis test (SME) as well as the full list of summary statistics for the genome-wide interaction analysis using SME to study 
UK Biobank traits.

1. **sme_1.0.0.tar.gz** - source code
2. **table_S4_MCH.csv** - summary statistics for the trait mean corpuscular
   hemoglobin (MCH) with DHS mask
3. **table_S5_MCHC.csv** - summary statistics for the trait mean corpuscular 
   hemoglobin concentration (MCHC) with DHS mask
4. **table_S6_MCV.csv** - summary statistics for the trait mean corpuscular 
   volume 
   (MCV) with DHS mask
5. **table_S7_HCT.csv** - summary statistics for the trait hematocrit (HCT) with DHS mask
6. **table_S8_HEIGHT.csv** - summary statistics for the trait body height (HEIGHT) with GWAS mask
7. **table_S9_MCH.csv** - summary statistics for the trait mean corpuscular hemoglobin (MCH) with GWAS mask
8. **table_S10_URATE.csv** - summary statistics for the trait uric acid (URATE) with GWAS mask
9. **table_S11_VITD.csv** - summary statistics for the trait vitamin D levels (VITD) with GWAS mask

## Install the Source Code

The source code can be installed with `R CMD INSTALL sme_1.0.0.tar.gz`. The 
package is maintained by the authors of the paper and is available on GitHub
at https://github.com/lcrawlab/sme/. Refer to the repo for an up-to-date 
version.

## CSV File Description

Each CSV file contains the following columns:

1.	**id** - The identifier of the genetic variant.
2.	**chromosome** - The chromosome on which the genetic variant is located.
3.	**position** - The position of the genetic variant on the chromosome.
4.	**p** - The p-value for the marginal epistasis association.
5.	**pve** - The proportion of variance explained by the genetic variant that 
      is attributed to epistasis.
6.	**trait** - The trait being analyzed in the genome-wide interaction study.
7.	**external_data** - External data type used to induce sparsity in the 
      SME model.

# Archived FAME sources

The file FAME-cfdd03f.zip contains the source code of FAME used in this study.
