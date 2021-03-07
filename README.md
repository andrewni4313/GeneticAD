# FUNCTIONAL GENETIC BIOMARKERS OF ALZHEIMER’S DISEASE AND GENE EXPRESSION FROM PERIPHERAL BLOOD

### ABSTRACT

Detecting Alzheimer’s Disease (AD) at the earliest possible stage is key in advancing AD prevention and treatment but is challenged by normal aging processes in addition to other confounding neurodegenerative diseases. Recent genome-wide association studies (GWAS) have identified associated alleles, but it has been difficult to transition from non-coding genetic variants to underlying mechanisms of AD. Here, we sought to reveal functional genetic variants and diagnostic biomarkers underlying AD using machine learning techniques. We first developed a Random Forest (RF) classifier using microarray gene expression data sampled from the peripheral blood of 744 participants in the Alzheimer’s Disease Neuroimaging Initiative (ADNI) cohort. After initial feature selection, 5-fold cross-validation of the 100-gene RF classifier achieved an accuracy of 99.04%. The high accuracy of the RF classifier supports the possibility of a powerful and minimally invasive tool for screening of AD. Next, unsupervised clustering was used to validate and identify relationships among differentially expressed genes (DEGs) the RF selected revealing 3 distinct AD clusters. Results suggest downregulation of global sulfatase and oxidoreductase activities in AD through mutations in SUMF1 and SMOX respectively. Then, we used Greedy Fast Causal Inference (GFCI) to find potential causes of AD within DEGs. In the causal graph, HLA-DPB1 and CYP4A11 emerge as hub genes, furthering the discussion of the immune system’s role in AD. Finally, we used Gene Set Enrichment Analysis (GSEA) to determine the biological pathways and processes underlying the DEGs that were highly correlated with AD. Cell activation in the immune system, glycosaminoglycan (GAG) binding, vascular dysfunction, oxidative stress, and the neuronal apoptotic process were revealed to be significantly enriched in AD. This study further advances the possibility of low-cost and noninvasive genetic screening for AD while also providing potential gene targets for further experimentation.

The python notebooks in this repository are for the unsupervised clustering, random forest classification, data processing, and analysis. Tetrad Causal Analysis files are also included. Periperal blood gene expression data can be acquired by appling to the Alzheimer's Disease Neuroimaging Initiative (ADNI) database at http://adni.loni.usc.edu/

All the files are distributed under the MIT license.
