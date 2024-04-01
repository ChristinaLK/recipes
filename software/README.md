# [software](/software/)

If you are new to building your own software in CHTC, we recommend that you 
first read through our [Software Overivew]() guide. Then choose from the list 
below to see recipes for how to build your own software environment. 

In general, we recommend: 

- for the HTC system (job submission with HTCondor)
  - apptainer
  - docker
  - sometimes local installs
- for the HPC system (job submission with SLURM)
  - apptainer
  - local installs
  - spack installs

| Software Name | Apptainer | Docker | Local Install | HPC Spack | 
| :--- | :---: | :---: | :---: | :---: |
| [Alphafold](AlphaFold) | X | - | - | - | 
| [GROMACS](Gromacs) | X | - | X | X |
| [OpenFoam](OpenFOAM) | - | - | - | X | 
| [R, with packages](R) | X | - | - | - | 
| [SUMO](SUMO) | X | X | - | - | 

## Related Guides

- software overview
- HTC containers
- HPC containers
- spack, etc.
