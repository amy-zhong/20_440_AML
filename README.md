Welcome to the GitHub repository for Kenneth and Amy's 20.440 Project "Modeling AML tumor responses to bone marrow microenvironment." 

*Overview*
This repo currently houses the initial exploratory code showing that there exists differential gene expression in childhood vs. adult Acute Myeloid Leukemia. Eventually, we seek to explore how RNAseq shows AML adapts to bone marrow microenvironmental factors at a transcriptome level. 

*Data*
RNAseq data from TARGET AML has been downloaded and stored in the TARGET-NCI-AML-RNAseq-data folder. The metadata accompanying this file is in TARGET_AML_mRNA-seq_metadata.txt. This is a subset of the publicly available data in the TARGET AML program created by The Cancer Genome Atlas (TCGA). 

*Folder Structure*
The RNAseq data is stored in the TARGET-NCI-AML-RNAseq-data folder, and everything else exists in the base folder. 

*Installation*
The analysis is performed using TARGET_NCI_RNAseq_code.r.

The code requires that the following packages be installed: BiocManager, GO.db, and DESeq2. If you are missing any of these packages, either install them into your environment or uncomment and run the first 4 lines of "TARGET_NCI_RNAseq_code.r" to install. 