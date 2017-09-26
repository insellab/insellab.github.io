---
layout: default
---

## Counts files for performing Differential Expression (DE) analysis. 

These files contain organized counts data, calculated as RSEM estimated counts via the [TOIL](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net) pipeline. The original, 'raw' processed counts data are hosted at the [Xena](xena.ucsc.edu) portal.

Files are organized with headers (usually the top 2-3 rows) containing information about tumor type and subtype, for TCGA samples, whether the sample is a primary tumor or normal matched tissue and sample IDs. The first column contains Ensembl gene IDs. These counts files contain data for both TCGA tumors and their corresponding 'normal' parent tissue. 

All counts values are linear, i.e. NOT log transformed. 

These are the input files used for all DE analysis in our study via EdgeR, hence will allow replication of presented values for DE of GPCRs (and other genes) as well as estimation of expression in CPM. These files should also work for other DE analysis software (e.g. DEseq2), however please note that for DEseq, all counts values must be rounded to integers.


**If using any of these Counts files for DE analysis, please cite the TOIL paper, TCGA and GTEX as detailed on our [home](https://insellab.github.io/) page.**


[Adrenocortical Cancer](https://drive.google.com/open?id=0ByccgsfmD86PU1pXejNqeDlYUU0) 

[Bladder Cancer](https://drive.google.com/open?id=0ByccgsfmD86PNTlhTXplOHU5R2c) 

[Breast Cancer (IDC)](https://drive.google.com/open?id=0ByccgsfmD86PVVRkcUpRQWRaZE0) 

[Breast Cancer (ILC)](https://drive.google.com/open?id=0ByccgsfmD86PejF6UWloVW5vS0E) 

[Cervical Cancer](https://drive.google.com/open?id=0ByccgsfmD86PaEE1d0ltQVVhR0U) 

[Colon Cancer](https://drive.google.com/open?id=0ByccgsfmD86Pci04MG5xODdYYjA) 

[Esophageal Cancer](https://drive.google.com/open?id=0ByccgsfmD86POXB4a015X1g3Vkk)

[Kidney Chromophobe](https://drive.google.com/open?id=0ByccgsfmD86PNWRjeEs1SnFwRmc)

[Kidney Clear Cell Carcinoma](https://drive.google.com/open?id=0ByccgsfmD86PTklHQ2RtamwtOFk)

[Kidney Papillary Cell Carcinoma](https://drive.google.com/open?id=0ByccgsfmD86PQ1NvSk5Cbk5pX2s)

[Liver Hepatocellular Carcinoma](https://drive.google.com/open?id=0ByccgsfmD86PYWQwcGt6TnQ1M00)

[Lung Adenocarcinoma](https://drive.google.com/open?id=0ByccgsfmD86PdHlaRWVXOEpaaW8)

[Lung Squamous Cell Carcinoma](https://drive.google.com/open?id=0ByccgsfmD86PWm5LTXlnMkpHWDQ)

[Skin Cutaneous Melanoma](https://drive.google.com/open?id=0ByccgsfmD86PdEE0eTNfWFowOGM)

[Ovarian Cancer](https://drive.google.com/open?id=0ByccgsfmD86PTXZOVjd2U2twWVk)

[Pancreatic Ductal Adenocarcinoma](https://drive.google.com/open?id=0ByccgsfmD86PN0htU09kOWRfMHM)

[Prostate Adenocarcinoma](https://drive.google.com/open?id=0ByccgsfmD86PTm9nM2FfekliQ0k)

[Stomach Adenocarcinoma](https://drive.google.com/open?id=0ByccgsfmD86Pdm14RnZ4UzEwZlE)

[Testicular Cancer](https://drive.google.com/open?id=0ByccgsfmD86PYjR2NWI5Ujc5ODg)

[Thyroid Cancer](https://drive.google.com/open?id=0ByccgsfmD86POHJDM0Z0cmUyMUU)

[Uterine Carcinosarcoma](https://drive.google.com/open?id=0ByccgsfmD86Pdk1EZW9OUEdkVDg)




