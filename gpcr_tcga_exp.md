---
layout: default
---

### This page provides expression of GPCRs in TCGA tumors in TPMs (Calculated via [TOIL](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net)) and CPMs. TOIL data were queried via the [Xena visualization tool](https://xenabrowser.net/heatmap/).

GPCR expression in TPM are gene-level estimates calculated via RSEM (Li and Dewey, 2011), whereas CPM values were calculated via EdgeR (Robinson et al, 2010).
Input for EdgeR were curated files, containing gene-level RSEM estimated counts, downloaded from Xena [here](https://xenabrowser.net/datapages/?dataset=tcga_gene_expected_count&host=https://toil.xenahubs.net).

The 'raw' download file linked above contains counts for all TCGA samples and genes together. We have provided curated files for each tumor type at (_____).
