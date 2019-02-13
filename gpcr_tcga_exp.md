---
layout: default
---

### This page provides expression of GPCRs in TCGA tumors in TPMs (Calculated via [TOIL](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net)) and CPMs. TOIL data were queried via the [Xena visualization tool](https://xenabrowser.net/heatmap/).

GPCR expression in TPM are gene-level estimates calculated via RSEM (Li and Dewey, 2011), whereas CPM values were calculated via EdgeR (Robinson et al, 2010).
Input for EdgeR were curated files, containing gene-level RSEM estimated counts, downloaded from Xena [here](https://xenabrowser.net/datapages/?dataset=tcga_gene_expected_count&host=https://toil.xenahubs.net).

The 'raw' download file linked above contains counts for all TCGA samples and genes together. We have provided curated files for each tumor type at [here](https://insellab.github.io/counts_files).

  
<br/><br/>

**GPCR expression in TPM**

Each file contains expression in TPM for all endo-GPCRs in the respective tumor types, further divided into subtypes as applicable. For example, the esophageal cancer file provides expression for squamous cell carcinomas and adenocarcinomas as distinct groups. For each GPCR, expression is shown as median for the tumor subtype, as well as expression in each individual tumor sample.

Certain samples highlighted in yellow were not included for other analyses (such as DE analysis) due to issues such as unclear metadata or classification into subtypes with very few (<10) replicates. These highlighted samples will therefore not appear in the accompanying files with GPCR expression in CPM.


[Adrenocortical Cancer (ACC)]()

[Bladder Cancer (BLCA)]()

[Breast Cancer (BRCA)]()

[Cervical Cancer (CESC)]()

[Colon Cancer (COAD)]()

[Esophageal Cancer (ESCA)]()

[Kidney Chromophobe (KICH)]()












