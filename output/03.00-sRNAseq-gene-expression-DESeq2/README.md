`project-clam-oa/output/03.00-sRNAseq-gene-expression-DESeq2`


Output directory for [`03.00-sRNAseq-gene-expression-DESeq2.Rmd`](../../code/03.00-sRNAseq-gene-expression-DESeq2.Rmd).

---

- [`DE-miRNAs.fdr-0.05.lfc-0.tab`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/DE-miRNAs.fdr-0.05.lfc-0.tab): Tab-delimited list of differentially expressed miRNA "clusters" from the ShortStack `Results.txt` file.

- [`DE-sRNAs.fdr-0.05.lfc-0.tab`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/DE-sRNAs.fdr-0.05.lfc-0.tab): Tab-delimited list of differentially expressed sRNA "clusters" from the ShortStack `Results.txt` file. Since this is any sRNA, results may also include miRNAs identified by ShortStack.

-   [`DESeq2-coldata.tab`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/DESeq2-coldata.tab): Two column table with sample ID and treatment. Needed as input to DEseq2.

- [`deseq2.miRNAs.fdr-0.05.lfc-0.table.csv`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/deseq2.miRNAs.fdr-0.05.lfc-0.table.csv): DEseq2 miRNA output table of results with adjusted p-value <= 0.05 and a log<sub>2</sub> fold change value = 0.

- [`deseq2.miRNAs.table.csv`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/deseq2.miRNAs.table.csv): Unfiltered DEseq2 miRNA output table containing all results with mean expression, fold change in expression, and adjusted p-values for all input samples.

- [`deseq2.sRNAs.fdr-0.05.lfc-0.table.csv`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/deseq2.sRNAs.fdr-0.05.lfc-0.table.csv): DEseq2 sRNA output table of results with adjusted p-value <= 0.05 and a log<sub>2</sub> fold change value = 0.

- [`deseq2.sRNAs.table.csv`](https://github.com/RobertsLab/project-clam-oa/blob/3a9131cc5af82e756990d735b1ad56aecc32008c/output/03.00-sRNAseq-gene-expression-DESeq2/deseq2.sRNAs.table.csv): Unfiltered DEseq2 sRNA output table containing all results with mean expression, fold change in expression, and adjusted p-values for all input samples.