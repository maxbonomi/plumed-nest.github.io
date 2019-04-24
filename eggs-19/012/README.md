**Project ID:** [plumID:19.012]({{ '/' | absolute_url }}eggs-19/012/)  
**Name:**  Martini-Beads multi-scale SAXS  
**Archive:** [ https://github.com/carlocamilloni/papers-data/raw/master/zip-for-nest/2019/paissoni19iucr.zip](https://github.com/carlocamilloni/papers-data/raw/master/zip-for-nest/2019/paissoni19iucr.zip)  
**Category:**  methods  
**Keywords:**  metainference, SAXS, martini, structure refinement, nucleic-acids, protein complex  
**PLUMED version:**  2.5  
**Contributor:**  Carlo Camilloni  
**Submitted on:** 17 Apr 2019  
**Publication:** [C. Paissoni, A. Jussupow, C. Camilloni, Martini bead form factors for nucleic acids and their application in the refinement of protein–nucleic acid complexes against SAXS data, Journal of Applied Crystallography 52, 394–402 (2019).](http://dx.doi.org/10.1107/S1600576719002450)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat](./data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.plumed_master.stderr) |  
| [paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat](./data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.md) |  [![tested on v2.5](https://img.shields.io/badge/v2.5-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.plumed_master.stderr) |  
  
**Project description and instructions**  
this is a metainference calculation using SAXS for structure refinement. In particular instead than  calculting SAXS using all the atoms we first maps them on martini beads using CENTER and then we  employ the structure factors parameterised in the paper to efficiently calculate SAXS. The same structure factors can be directly used on Martini simulations

  
**Submission history**  
**[v1]** 17 Apr 2019: original submission  
