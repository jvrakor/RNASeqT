# RNASeqT
R package for RNA-Seq data normalization and visualization


## INSTALLATION

### Install from GitHub:

Requires [devtools](https://cran.r-project.org/web/packages/devtools/README.html).

* `R`
* `library(devtools)`
* `install_github('jkokosar/RNASeqT')`


## USAGE

* `R`
* `library(RNASeqT)`
* `normalizeRNASeq(geneFPKMFile = 'genes.fpkm_table', name = 'test', groupString = 'Group1,Group2', outputFolder = './', useERCC = FALSE)`