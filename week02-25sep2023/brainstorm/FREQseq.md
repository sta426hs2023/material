## FREQ-Sequencing

The aim of FREQ-Sequencing is to quantify allele frequencies by counting DNA sequences using Illumina-based sequencing. It involves two rounds of PCR with sample-specific barcodes introduced by a bridging primer. Unlike other methods, it doesn't require individual long oligonucleotides or extra equipment. The resulting PCR products can be directly sequenced, producing an average of 147,000 reads per sample.          

An exemplary application: In the study of Chubiz et al. (2012) FREQ-Seq was used to determine beneficial alleles that arose in Methylobacteria. The validation from the utility of the FREQ-Seq was determined by the frequency from four beneficial mutations that arose during adaptation of an engineered Methylobacterium extorquens AM1 strain, examining  both the cellular ratios of each allele and the cryogenically stored population time-point samples. These allele frequency data allowed direct comparison of observed fitness increases to the rapid rise of these mutations. For simple alleles, calibration was unnecessary whereas correction via control ratios and simple model fit was conducted for more complex  allele types.

For the method validation, the potential bias that could be generated from PCR amplification was analyzed. Comparison between the observed allele frequencies and those expected  from the cell ratios demonstrated that there was  remarkably little bias throughout the procedure. Moreover, the FREQ-Seq method can produce allele frequency estimates consistently with low absolute errors. However, for very high and  very low allele frequency estimates (>99% or <1%) the relative error can become large because the frequency becomes equal or less than the frequency of the noise (sequencing errors). A model for the likelihood of sequencing error was therefore conducted to measure this phenomena, this model runs a sample that is entirely of one type and looks at how often the other type appears. For both alleles, and for all  sequencing dates, the observed error rate was very low and the median observed percentage of  the type not supposed to be present in the sample was 0.23%, indicating that this percentage is approximately equal to the range  in which signal and noise  become equally important to the allele frequency estimate. 

| Technology         | Applications     | Statistics |
|--------------|-----------|------------|
| FREQ-Sequencing  | Quantify allele frequencies | Estmation Bias, Absolute Error |
________

\
\
**Bibliography**:\
Chubiz, L. M., Lee, M.-C., Delaney, N. F., & Marx, C. J. (2012). FREQ-Seq: A Rapid, Cost-Effective, Sequencing-Based Method to Determine Allele Frequencies Directly from Mixed Populations. PLOS ONE, 7(10), e47959. https://doi.org/10.1371/journal.pone.0047959



_________________________
Github usernames: davidkronthaler-dk, pilarbc123, ppasto, jastab
