---
layout: default
---

## Counts files for performing Differential Expression (DE) analysis. 

These files contain organized counts data, calculated as RSEM estimated counts via the [TOIL](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net) pipeline. The original, 'raw' processed counts data are hosted at the [Xena](xena.ucsc.edu) portal.

Files are organized with headers (usually the top 2-3 rows) containing information about tumor type and subtype, for TCGA samples, whether the sample is a primary tumor or normal matched tissue and sample IDs. The first column contains Ensembl gene IDs. 

All counts values are linear, i.e. NOT log transformed. 

These are the input files used for all DE analysis in our study via EdgeR, hence will allow replication of presented values for DE of GPCRs (and other genes) as well as estimation of expression in CPM. These files should also work for other DE analysis software (e.g. DEseq2), however please note that for DEseq, all counts values must be rounded to integers.


**If using any of these Counts files for DE analysis, please cite the TOIL paper, TCGA and GTEX as detailed on our [home](https://insellab.github.io/) page.**
