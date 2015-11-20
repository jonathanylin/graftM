# GraftM
GraftM is a tool for the analysis of ~omic sequence datasets.

Using modular gene packages, GraftM will search the provided sequences using hmmsearch (hmmer) and subsequently places the identified sequences within a pre-constructed phylogenetic
tree (pplacer). The provides fast, phylogenetically informed community profiles. GraftM provides tools to:
* Create and update custom gene packages to use with GraftM
* Decorate trees, and of course
* Analyse sequence datasets using these GraftM packages
Head over to the [GraftM page](http://geronimp.github.io/graftM/) for more general information.

### Installation
GraftM can be installed via pip:
```
pip install graftm
```
However, to use all features of GraftM a few extra binary applications are required:
* orfm v. >= 0.2.0 (https://github.com/wwood/OrfM)
* hmmer v. >= 3.1b1 (http://hmmer.janelia.org/)
* fxtract (https://github.com/ctSkennerton/fxtract)
* pplacer v. >= 2.6.32 (http://matsen.fhcrc.org/pplacer/)
* krona v. >= 2.4 (http://sourceforge.net/p/krona/home/krona/)
* mafft v. >= 7.22 (http://mafft.cbrc.jp/)

### Manual
A [manual](https://github.com/geronimp/graftM/wiki) is available in the form of the wiki here on GitHub.

### Contact
If you have any further comments, complaints or recomendations about GraftM, drop an email to the [SupportM](https://groups.google.com/forum/?hl=en#!forum/supportm) public help forum.
Software by [Joel A. Boyd](http://ecogenomic.org/users/joel-boyd) (@geronimp) and [Ben J. Woodcroft](http://www.ecogenomic.org/users/ben-woodcroft) (@wwood) at the [Australian Centre for Ecogenomics](http://ecogenomic.org)
Released under GPL3 - see LICENCE.txt for licencing details
