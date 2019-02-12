# biomedical-relation-extraction-progress
This repository contains the information on biomedical relation extraction.

Relationship extraction is the task of extracting semantic relationships from a text. Biomedical relation extraction is useful for extracting relations between biomedical entities such as Genes, Proteins and Drugs from research publications and articles.

### PPI Corpora

The most widely studied corpus for biomedical relation extraction is a set of 5 corpuses (Aimed, Bioinfer, hprd50, iepa, lll) for protein-protein interactions. Although released by different groups, all these corpuses were studied and converted to a single format in [Pyysalo et al, 2008](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-S3-S6) and the conversion software is available at http://mars.cs.utu.fi/PPICorpora/.

Due to different pre-processing steps and evaluation strategies, it is often difficult to compare results reported by different systems. Nevertheless, following are some of the important papers which have reported performance on these datasets.


* [All-paths graph kernel for protein-protein interaction extraction with evaluation of cross-corpus learning](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-S11-S2)

* [A Comprehensive Benchmark of Kernel Methods to Extract Protein–Protein Interactions from Literature](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000837#s3)

* [PPInterFinder—a mining tool for extracting causal relations on human proteins from literature](https://academic.oup.com/database/article/doi/10.1093/database/bas052/327699#82412927)

* [Identifying Protein-protein Interactions in Biomedical Literature using
Recurrent Neural Networks with Long Short-Term Memory](http://www.aclweb.org/anthology/I17-2041)

* [Identifying Protein-Protein Interaction using TreeLSTM and Structured Attention](https://arxiv.org/pdf/1808.03227.pdf)


### BioCreative VI Chemprot Challenge

Chemprot dataset was released as part of the Biocreative VI chemical protein interaction track. It contains labelled data for chemical-protein interactions. 5 relation classes were used for evaluation purposes including agonist, antagonists, inhibitor, activator and substrate/product relations.

Biocreative VI Challenge Overview Paper: [Overview of the BioCreative VI chemical-protein interaction Track](https://pdfs.semanticscholar.org/eed7/81f498b563df5a9e8a241c67d63dd1d92ad5.pdf)

Important Papers:
[Chemical-protein relation extraction with ensembles of SVM, CNN, and RNN models](https://arxiv.org/abs/1802.01255)

[Chemical–gene relation extraction using recursive neural network](https://academic.oup.com/database/article/doi/10.1093/database/bay060/5042822)

[BioBERT: a pre-trained biomedical language representation model for biomedical text mining](https://arxiv.org/pdf/1901.08746.pdf)([code](https://github.com/dmis-lab/biobert))
