# Differential Abundance Analysis

A pipeline that encompasses the steps for differential abundance analysis of the pecan phyllosphere for 2021 and 2022. Samples were obtained from the E.V. Smith research facility, located in Tallassee, AL. Samples were decontaminated, subset to only include kingdom Fungi, as well as filtering out samples with less than 5000 reads. The [rds](https://github.com/Beatrice-Severance/Differential_Abundance/blob/main/21-22-fungi-phyloseq-clean.rds) file is used to kick start the analysis process.

## ANCOM-BC2

ANCOM-BC2 was used to perform differential abundance analysis for the provided data set. ANCOMBC has low false discovery rates at low n, which makes it useful when dealing with a small number of samples. Read more about ANCOMBC [here](https://github.com/FrederickHuangLin/ANCOMBC).

## DESeq2

DeSeq 2 was also used to perform differential abundance analysis. This method has a low false discovery rate as long as p-value corrections are incorporated. Read more about DESeq2 [here](https://www.bioconductor.org/packages/devel/bioc/vignettes/DESeq2/inst/doc/DESeq2.html#data-transformations-and-visualization).