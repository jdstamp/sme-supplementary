# Supplementary Data for Stamp et al. - Sparse modeling of interactions enables fast detection of genome-wide epistasis in biobank-scale studies (2025)

This repository provides the source code of SME as well as the full list of 
summary statistics for the genome-wide interaction analysis using SME to study 
UK Biobank traits.

1. **sme_0.0.1.tar.gz** - source code version that produced below data
2. **table_S2_MCH.csv** - summary statistics for the trait mean corpuscular
   hemoglobin (MCH)
3. **table_S3_MCHC.csv** - summary statistics for the trait mean corpuscular 
   hemoglobin concentration (MCHC) 
4. **table_S4_MCV.csv** - summary statistics for the trait mean corpuscular 
   volume 
   (MCV)
5. **table_S5_HCT.csv** - summary statistics for the trait hematocrit (HCT)

## Install the Source Code

The source code the data can be installed with `R CMD INSTALL sme_0.0.1.tar.gz`. The 
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
