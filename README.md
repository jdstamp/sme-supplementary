# Supplementary Data for "TITLE PLACEHOLDER"

This repository provides the source code of SME as well as the full list of 
summary statistics for the genome-wide interaction analysis using SME to study 
UK Biobank traits.

1. **sme_1.0.0.tar.gz** - source code
2. **SME_HCT.CSV** - summary statistics for the trait hematocrit (HCT)
3. **SME_MCH.CSV** - summary statistics for the trait mean corpuscular 
   hemoglobin (MCH)
4. **SME_MCHC.CSV** - summary statistics for the trait mean corpuscular 
   hemoglobin concentration (MCHC) 
5. **SME_MCV.CSV** - summary statistics for the trait mean corpuscular volume 
   (MCV)

The source code can be installed with `R CMD INSTALL sme_1.0.0.tar.gz`. The 
package is maintained by the authors of the paper and is available on GitHub
at https://github.com/lcrawlab/mmer/. Refer to the repo for an up-to-date 
version.

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