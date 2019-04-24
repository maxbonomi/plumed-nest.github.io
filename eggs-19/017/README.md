**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs-19/017/)  
**Name:**  Ligand binding pathways exploration  
**Archive:** [ https://github.com/riccardocapelli/papers_data/raw/master/pathway_search2019/input_data.zip](https://github.com/riccardocapelli/papers_data/raw/master/pathway_search2019/input_data.zip)  
**Category:**  bio  
**Keywords:**  metadynamics, ligand binding  
**PLUMED version:**  2.5  
**Contributor:**  Riccardo Capelli  
**Submitted on:** 23 Apr 2019  
**Last revised:** 24 Apr 2019  
**Publication:** unpublished  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed_metad/metad_20ang.dat](./data/plumed_metad/metad_20ang.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_metad/metad_20ang.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad/metad_20ang.dat.plumed_master.stderr) |  
| [plumed_metad/metad_22ang.dat](./data/plumed_metad/metad_22ang.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_metad/metad_22ang.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad/metad_22ang.dat.plumed_master.stderr) |  
| [plumed_metad/metad_24ang.dat](./data/plumed_metad/metad_24ang.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_metad/metad_24ang.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad/metad_24ang.dat.plumed_master.stderr) |  
| [plumed_metad/metad_26ang.dat](./data/plumed_metad/metad_26ang.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_metad/metad_26ang.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad/metad_26ang.dat.plumed_master.stderr) |  
| [plumed_metad/metad_28ang.dat](./data/plumed_metad/metad_28ang.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_metad/metad_28ang.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad/metad_28ang.dat.plumed_master.stderr) |  
| [plumed_reweight/reweight_rho_c.dat](./data/plumed_reweight/reweight_rho_c.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/plumed_reweight/reweight_rho_c.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_reweight/reweight_rho_c.dat.plumed_master.stderr) |  
  
**Project description and instructions**  
The data are in three different folders: * input, which contains the GROMACS (2016.5) input files (gro, top, itp, and mdp) to run the MD simulation. * plumed_metad, which contains the PLUMED input file to perform volume-based metadynamics with different restraining potential size * plumed_reweight, which contains the PLUMED reweighing input file.

  
**Submission history**  
**[v1]** 23 Apr 2019: original submission  
**[v2]** 24 Apr 2019: corrected paths for input files (ndx, pdb, dat), example data files added for the reweighting procedure  
