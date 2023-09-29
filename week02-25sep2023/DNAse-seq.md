# DNAse-seq
DNase-seq, short for DNase I hypersensitive sites sequencing, is a method used to identify regions of the genome (DNAse hypersensitivity sites, DHS) that are accessible to the protein DNase I. These accessible regions often correspond to regulatory elements, such as promoters, enhancers, and insulators, which play crucial roles in gene expression. By sequencing the DNA fragments that are cleaved by DNase I, researchers can create a genome-wide map of these regulatory elements, providing insights into the regulatory landscape of a cell. More information can be found in the paper [High-Resolution Mapping and Characterization of Open Chromatin across the Genome](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2669738/).

| Technology | Application | Statistics |
| ---------- | ----------- | ---------- |
| DNAse-seq | Map chromatin state, map regulatory elements, create regulatory networks, Motif Enrichment Analysis | Monte-Carlo methods|
| | Differential Accessibility Analysis | non-parametric statistical tests like Wilcoxon rank-sum test, DESeq2, edgeR |
| | Gene regulation and chromatin dynamics | Hidden Markov Models, Baysian Mixture Models, Sliding Window, Logistic regression|

**Differential Accessibility Analysis**: For experiments comparing different conditions or cell types, statistical methods are used to identify regions with differential chromatin accessibility.

**Motif Enrichment Analysis**: Once DHSs are identified, motif analysis can be performed to predict which transcription factors might be binding to these regions.

## Literature
You may find here some scientific literature about the DNAse-sequencing :

- A more introducing article, with detailed process is to find [on the website of the National Library of Medecine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3627383/)

- If you wish on the other hand to better understand what regulatory elements are, and what role they may play, you should read [this article published by the National Library of Medecine as well](https://pubmed.ncbi.nlm.nih.gov/26499213/#:~:text=Precisely%20identifying%20regulatory%20elements%20is,and%20the%20interactions%20between%20them)

- A analysis of different statistical and computational methods can be found in [this article published by Nature Methods](https://www.nature.com/articles/nmeth.3772)

-   For articles about specific statistical application we here have a article using [Bayseian mixture models](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4231734/) and [Hidden Markov Models](https://academic.oup.com/bioinformatics/article/30/22/3143/2390674)


### Authors

peterlundandersen

marie3003

juslecl

