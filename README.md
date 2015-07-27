PancancerDataSurbhi
===================

PancancerDataSurbhi

12 Cancer Datasets were downloaded from TCGA. This contained the Level 3 Gene expression data calculated using HiSeq Rapid V2. The same 12 cancer dataset is also available on the UCSC Cancer Genomics Browser. 
The cancers included are:

1. Bladder Urothelial Carcinoma [BLCA]
2. Acute Myeloid Leukemia [LAML]
3. Breast Invasive Carcinoma [BRCA]
    Breast-Basal
    Breast-Her
    Breast-LumA
    Breast-LumB
    Breast-Normal
4. Colon Adenocarcinoma [COAD]
5. Uterine Corpus Endometrial Carcinoma [UCEC]
6. Glioblastoma multiforme [GBM]
7. Renal clear cell carcinoma [KIRC]
8. Lung adenocarcinoma [LUAD]
9. Lung squamous cell carcinoma [LUSC]
10. Head and Neck squamous cell carcinoma [HNSC]
11. Ovarian serous cystadenocarcinoma [OV]
12. Rectum adenocarcinoma [READ]

Compiled data was normalised across all cancer samples using formula:

New Expression Value = (Old Expression Value - Sample Mean)/ Sample Std. Deviation

-- 

Mean and Std. Dev was also calculated accross all Genes. 
The Coeffient of variation was used to sort the genes and select the top 5000 genes. 

Coeffient of variation = (Std. dev of Gene/ Mean of Gene)


