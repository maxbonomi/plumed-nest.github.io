**Project ID:** [plumID:19.008]({{ '/' | absolute_url }}eggs-19/008/)  
**Name:**  anncolvar  
**Archive:** [ https://github.com/spiwokv/plumed_nest_by_spiwokv/raw/master/anncolvar.zip](https://github.com/spiwokv/plumed_nest_by_spiwokv/raw/master/anncolvar.zip)  
**Category:**  methods  
**Keywords:**  neural network, dimensionality reduction  
**PLUMED version:**  2.5.0  
**Contributor:**  Vojtech Spiwok  
**Submitted on:** 16 Apr 2019  
**Last revised:** 18 Apr 2019  
**Publication:** [D. Trapl et al., Anncolvar: Approximation of Complex Collective Variables by Artificial Neural Networks for Analysis and Biasing of Molecular Simulations, Frontiers in Molecular Biosciences 6 (2019), doi:10.3389/fmolb.2019.00025.](http://dx.doi.org/10.3389/fmolb.2019.00025)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [c8/plumed.dat](./data/c8/plumed.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/c8/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/c8/plumed.dat.plumed_master.stderr) |  
| [trpcage/mtd/plumed.dat](./data/trpcage/mtd/plumed.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/trpcage/mtd/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/trpcage/mtd/plumed.dat.plumed_master.stderr) |  
| [trpcage/ptmd/plumed.dat](./data/trpcage/ptmd/plumed.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/trpcage/ptmd/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/trpcage/ptmd/plumed.dat.plumed_master.stderr) |  
| [trpcage/ptmtd/plumed.dat](./data/trpcage/ptmtd/plumed.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/trpcage/ptmtd/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/trpcage/ptmtd/plumed.dat.plumed_master.stderr) |  
  
**Project description and instructions**  
Neural networks were created by ancolvar (https://github.com/spiwokv/anncolvar) and used to approximate Isomap CVs for 5 ns metadynamics of cyclooctane derivative and to approximate molecular surface area for 0.5 ns metadynamics, 1 ns parallel tempering and 1 ns parallel tempering metadynamics of Trp-cage folding with molecular surface area and alpha-RMSD CVs. 

  
**Submission history**  
**[v1]** 16 Apr 2019: original submission  
**[v2]** 18 Apr 2019: updated DOI  
