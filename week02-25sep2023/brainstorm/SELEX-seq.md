## SELEX-seq (Systematic Evolution of Ligands by Exponential Enrichment - sequencing)

SELEX-seq is an experimental and computational method that can be used to determine the relative DNA-sequence binding affinities for a specific target molecule (e.g. here: transcription factor complex) using a library of randomised oligonucleotides and successive rounds of DNA binding and selection (selection can be done under specific conditions depending on the use case at hand). Relative affinities are then calculated by comparing the identity of the library in these rounds to the original. 

Oligonucleotides with randomised binding regions flanked by primer docking sites interact with transcription factor complexes, bound DNA complexes are then separated form unbound DNA using EMSA or immunopurfication-based assays, and then amplified by PCR for subsequent rounds of DNA binding and selection.

Its key application has been in morphogenesis research, where it has been used to investigate the transcription factor-mediated activity of the HOX genes that play a fundamental role in axial patterning within vertebrates during embryogenesis.

![image](https://media.springernature.com/m685/springer-static/image/art%3A10.1203%2F00006450-199710000-00001/MediaObjects/41390_1997_Article_BFpr19972506_Fig1_HTML.jpg)

| Technology | Applications | Statistics |
| ----- | ----- | ------ |
| SELEX-seq | Morphogenesis, cell differentiation | Markov models, coarse-grained Kullback Leibler divergence, local LOESS regression | 

### Links
[Paper introducing SELEX-seq](https://www.sciencedirect.com/science/article/pii/S0092867411013705) \
[Another Paper introducing SELEX-seq](https://pubmed.ncbi.nlm.nih.gov/25151169/) \
[Schematic diagram of SELEX-seq process](https://www.semanticscholar.org/paper/Probing-the-SELEX-Process-with-Next-Generation-Schütze-Wilhelm/a116f639d6abd70101afa9e1d9de57ee63e5202f/figure/0) \
[Protocol overview](https://star-protocols.cell.com/protocols/1750) \
[Nature Review Article about HOX genes](https://www.nature.com/articles/pr19972506)

### GitHub Names
molbioeng

katjaschumacher

cdeancos
