# PARS-Seq

- **PARS** or **P**arallel **A**nalysis of **R**NA **S**tructure is a method to elucidate the secondary RNA structure of the whole genome by linking the digestion pattern of ds/ss-specific RNAses with high-throughput sequencing of cDNA [1, 2]. 
- The output reads of the high-thoughput sequencing are merged into a so-called PARS score (log of number of reads sliced by the ds-specific RNAse V1 divided by number of reads by the ss-specific RNAse S1) which can be introduced into SeqFold (structure prediction program) [3] to predict precise secondary RNA structures. 
- The main statistical analysis of this method relies on hypergeometric tests and structure sampling from Boltzmann-weighted ensemble performed in **SeqFold** [3]. 



| Technology | Application  | Statistics  |
|-----|------|---|
|   PARS-Seq  |  Prediction of RNA secondary structure    |   **SeqFold**: hypergeometric tests , Boltzmann-weighted ensemble  |

## Resources

- [1]: Wan, Y., Qu, K., Ouyang, Z., & Chang, H. Y. (2013). Genome-wide mapping of RNA structure using nuclease digestion and high-throughput sequencing. Nature protocols, 8(5), 849–869. https://doi.org/10.1038/nprot.2013.045
- [2]: [Illumina PARS seq method website](https://www.illumina.com/science/sequencing-method-explorer/kits-and-arrays/pars-dsrna-seq.html)
- [3]: Ouyang, Z., Snyder, M. P., & Chang, H. Y. (2013). SeqFold: genome-scale reconstruction of RNA secondary structure integrating high-throughput sequencing data. Genome research, 23(2), 377–387. https://doi.org/10.1101/gr.138545.112

## Team participants 
- michelta00
- marieindilewitsch
- GonzaloCardenalAl