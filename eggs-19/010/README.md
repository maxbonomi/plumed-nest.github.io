**Project ID:** [plumID:19.010]({{ '/' | absolute_url }}eggs-19/010/)  
**Name:**  Multi-domain protein dynamics  
**Archive:** [ https://github.com/carlocamilloni/papers-data/raw/master/zip-for-nest/2018/weber2018_LC.zip](https://github.com/carlocamilloni/papers-data/raw/master/zip-for-nest/2018/weber2018_LC.zip)  
**Category:**  bio  
**Keywords:**  metainference, NMR, protein dynamics  
**PLUMED version:**  2.4  
**Contributor:**  Carlo Camilloni  
**Submitted on:** 16 Apr 2019  
**Publication:** [B. Weber et al., The Antibody Light-Chain Linker Regulates Domain Orientation and Amyloidogenicity, Journal of Molecular Biology 430, 4925–4940 (2018).](http://dx.doi.org/10.1016/j.jmb.2018.10.024)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [r108a/plumed-mm.dat](./data/r108a/plumed-mm.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/r108a/plumed-mm.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/r108a/plumed-mm.dat.plumed_master.stderr) |  
| [r108a/plumed-orient.dat](./data/r108a/plumed-orient.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/r108a/plumed-orient.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/r108a/plumed-orient.dat.plumed_master.stderr) |  
| [wt/plumed-mm.dat](./data/wt/plumed-mm.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/wt/plumed-mm.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/wt/plumed-mm.dat.plumed_master.stderr) |  
| [wt/plumed-orient.dat](./data/wt/plumed-orient.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/wt/plumed-orient.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/wt/plumed-orient.dat.plumed_master.stderr) |  
  
**Project description and instructions**  
this is a metadynamic metainference calculation using residual dipolar coupling to infere the interdomain dynamics of a two domain proteins. There are two proteins (wt and a mutant). the protoctol is in two step, first with plumed-orient.dat ones generate a good starting condition for the replicas such as that the agreement with RDCs is ok, then the proper sampling begins.

  
**Submission history**  
**[v1]** 16 Apr 2019: original submission  
