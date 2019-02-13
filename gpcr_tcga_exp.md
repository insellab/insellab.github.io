---
layout: default
---

### This page provides expression of GPCRs in TCGA tumors in TPMs (Calculated via [TOIL](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net)) and CPMs. TOIL data were queried via the [Xena visualization tool](https://xenabrowser.net/heatmap/).

GPCR expression in TPM are gene-level estimates calculated via RSEM (Li and Dewey, 2011), whereas CPM values were calculated via EdgeR (Robinson et al, 2010) using TMM normalization.
Input for EdgeR were curated files, containing gene-level RSEM estimated counts, downloaded from Xena [here](https://xenabrowser.net/datapages/?dataset=tcga_gene_expected_count&host=https://toil.xenahubs.net).

The 'raw' download file linked above contains counts for all TCGA samples and genes together. We have provided curated files for each tumor type at [here](https://insellab.github.io/counts_files).

### **How to use the data below**

Gene expression in TPM provides an estimate of the relevant abundance of *different genes within the same sample* or set of replicates. These data may be used for estimating which GPCR is highest expressed in a given tumor type/subtype and for ranking GPCRs based on magnitude of expression in an individual sample or a specific tumor type/subtype. 

Do not use expression in TPM for differential expression / fold change calculations and avoid using expression in TPM for any between-sample or between-group comparisons.

Gene expression in CPM will allow comparison of expression of the *same gene across different samples and groups*. Hence, if comparing expression between groups, performing survival analysis, cluster analysis etc., use the data in CPM. Do not use expression in CPM for ranking genes in terms of magnitude of expression. To estimate fold changes, use either the [fold-change calculations already provided](https://drive.google.com/open?id=1Fdps90G7j2A3vb24L3ikICADZ-7fIjiC) or re-analyze the data using the [raw counts](https://insellab.github.io/counts_files) via edgeR. 
  
<br/><br/>

### **GPCR expression in TPM**

Each file contains expression in TPM for all endo-GPCRs in the respective tumor types, further divided into subtypes as applicable. For example, the esophageal cancer file provides expression for squamous cell carcinomas and adenocarcinomas as distinct groups. For each GPCR, expression is shown as median for the tumor subtype, as well as expression in each individual tumor sample. Where applicable, data for (tumor-matched) normal samples are also shown. 

In addition, on the second sheet of each file is corresponding GPCR expression in GTEX 'normal' samples from corresponding normal tissue.

Certain samples highlighted in yellow were not included for other analyses (such as DE analysis) due to issues such as unclear metadata or classification into subtypes with very few (<10) replicates. These highlighted samples will therefore not appear in the accompanying files with GPCR expression in CPM.


[Adrenocortical Cancer (ACC)](https://drive.google.com/open?id=1YarKNkX09wuPNgrDaOfXkasnNQA0NI6v)

[Bladder Adenocarcinoma (BLCA)](https://drive.google.com/open?id=1ogCNNiBEabAk9A_ZNj-R2B2RZrpx1C9_)

[Breast Adenocarcinoma (BRCA)](https://drive.google.com/open?id=16KvS3Uch_esJWvKde_sE5mw8BONenRMb)

[Cervical Cancer (CESC)](https://drive.google.com/open?id=1HV32oUw2qyitW8eaBCxJsS_6G3esbTcU)

[Colon Adenocarcinoma (COAD)](https://drive.google.com/open?id=16lvg3lPb_0cz-927ElQKbq3ZUzam39Jb)

[Esophageal Cancer (ESCA)](https://drive.google.com/open?id=1M2NcSMDtX-xXq5WUeNlYI1IUl11imc47)

[Kidney Chromophobe (KICH)](https://drive.google.com/open?id=1c0gzYFKMaJ3A_DiCIVQg--7IpibPVV5s)

[Kidney Clear Cell Carcinoma (KIRC)](https://drive.google.com/open?id=1v9t1zKEP2g3gwjQV9X8SZCDEkD4vnU55)

[Kidney Renal Papillary Cell Carcinoma (KIRP)](https://drive.google.com/open?id=1TGSz0ZFUP2PHVGiSRZpZHvb-BSMQTaIO)

[Liver Hepatocellular Carcinoma (LIHC)](https://drive.google.com/open?id=14UY1q5tmWpN5eIWWcdxvUetBfW_EylJt)

[Lung Squamous Cell Carcinoma and Adenocarcinoma (LUSC and LUAD)](https://drive.google.com/open?id=1voBqIwmARxx7BS8DQUpfPtpvuKwScz7K)

[Ovarian Serous Cystadenocarcinoma (OV)](https://drive.google.com/open?id=1WJoqII00ksVFUJdrsi8OgxeJ2uxyGWmS)

[Pancreatic Adenocarcinoma (PAAD)](https://drive.google.com/open?id=1AeTht9_e4w3yH5w6IY5AwvobWcAy45gm)

[Prostate Adenocarcinoma (PRAD)](https://drive.google.com/open?id=1JQmbOpKDTJRokt0YI9eAIZv7cVj36Nia)

[Skin Cutaneous Melanoma (SKCM)](https://drive.google.com/open?id=1lxOOpHIOEPIY3tDzJrXl6I9ewUzqf3sn)

[Stomach Adenocarcinoma (STAD)](https://drive.google.com/open?id=1ySo-b_QwhCzRXGupY5QMm41jFvB2Vpzi)

[Testicular Cancer (TGCT)](https://drive.google.com/open?id=138-FBEU8nFP9PRDl22Zo-wEJFDezNXJ5)

[Thyroid Cancer (THCA)](https://drive.google.com/open?id=1foDzuL2I5K0KrVXIPAgS9P22tgwiv36Y)

[Uterine Carcinosarcoma (UCS)](https://drive.google.com/open?id=1YJwiOXCzYaXs_LgEff4AddBY1GRPNZtR)


<br/><br/>


### **GPCR expression in CPM**

Each file contains GPCR expression in CPM for every GPCR gene in every sample, grouped together based on tumor subtype or as normal samples. Median expression of GPCRs in tumor subtypes are also provided.


[Adrenocortical Cancer (ACC)]()

[Bladder Adenocarcinoma (BLCA)]()

[Breast Adenocarcinoma (BRCA)]()

[Cervical Cancer (CESC)]()

[Colon Adenocarcinoma (COAD)]()

[Esophageal Cancer (ESCA)]()

[Kidney Chromophobe (KICH)]()

[Kidney Clear Cell Carcinoma (KIRC)]()

[Kidney Renal Papillary Cell Carcinoma (KIRP)]()

[Liver Hepatocellular Carcinoma(LIHC)]()

[Lung Squamous Cell Carcinoma and Adenocarcinoma (LUSC and LUAD)]()

[Ovarian Serous Cystadenocarcinoma (OV)]()

[Pancreatic Adenocarcinoma (PAAD)]()

[Prostate Adenocarcinoma (PRAD)]()

[Skin Cutaneous Melanoma (SKCM)]()

[Stomach Adenocarcinoma (STAD)]()

[Testicular Cancer (TGCT)]()

[Thyroid Cancer (THCA)]()

[Uterine Carcinosarcoma (UCS)]()


















