# Changelog

## Siesta Mobile 0.2.0

It is a copy of Quantum Mobile v20.06.1a1 with the elimination of few codes


### Software summary

- OS: Ubuntu 18.04.4 LTS
- tools: atomistic (xcrysden, jmol, cif2cell, ase, pymatgen, seekpath, spglib, pycifrw), visualization (grace, gnuplot, matplotlib, bokeh, jupyter), simulation environment (slurm, OpenMPI, FFT/BLAS/LAPACK, gcc, gfortran, singularity)
- aiida-core                      1.6.1
  - aiida-abinit                    0.2.0a1
  - aiida-quantumespresso           3.4.2
  - aiida-siesta                    1.2.0
  - aiida-wannier90                 2.0.1
  - aiida-wannier90-workflows       1.0.1
- simulation codes:
  - siesta    Max-1.2.0
  - abinit    9.2.1
  - Wannier90 3.1.0

### Build process

- ansible 2.10.7
- Vagrant v2.2.16
  - vbguest v0.30.0
  - bento/ubuntu-18.04 v202005.21.0
- Virtualbox v6.1.22

### Known Issues

Docker build has not been reviewed so it can not be trusted!!!!!
Documentation has not been modified!

