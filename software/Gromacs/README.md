# [GROMACS](/software/Gromacs)

Container definition files and local installation instructions for GROMACS. 

Program overview: https://www.gromacs.org/

Our recommendations for which recipe to use: 
- HTC system, CPU only: [gromacs-cpu.def]
- HTC system, GPUs: [gromacs-gpu.def]
- HPC system, multi-node: 
  - [gromacs-mpi.def]
  - [local-install]
  - [spack-install]

## [gromacs-cpu.def](gromacs-cpu.def)

| | | |
| ---: | :--- | :--- |
| *Type* | **Apptainer** | |
| *OS* | Ubuntu | |
| *Base image* | **Ubuntu** | *DockerHub* |
| *Updated* | 2024-02-23 | *Andrew Owen* |
| *Last tested on HTC* | - | - |
| *Last tested on HPC* | - | - |

## [gromacs-gpu.def](gromacs-gpu.def)

| | | |
| ---: | :--- | :--- |
| *Type* | **Apptainer** | |
| *OS* | Ubuntu | |
| *Base image* | **Nvidia** | *DockerHub* |
| *Updated* | 2024-02-23 | *Christina Koch* |
| *Last tested on HTC* | - | - |
| *Last tested on HPC* | - | - |

## [gromacs-mpi.def](gromacs-mpi.def)

| | | |
| ---: | :--- | :--- |
| *Type* | **Apptainer** | |
| *OS* | Ubuntu | |
| *Base image* | **condaforge/miniforge3:latest** | *DockerHub* |
| *Updated* | 2024-02-23 | *Andrew Owen* |
| *Last tested on HTC* | - | - |
| *Last tested on HPC* | - | - |

## [Local Install](local-install-README.md)

| | | |
| ---: | :--- | :--- |
| *Type* | **Local Install (best for HPC)** | |
| *Updated* | 2024-02-23 | *Spencer Ericksen* |
| *Last tested on HTC* | - | - |
| *Last tested on HPC* | 2024-04-01 | Christina Koch |

## [Spack Install](spack-install-README.md)

| | | |
| ---: | :--- | :--- |
| *Type* | **Spack Install (HPC only)** | |
| *Updated* | 2024-02-23 | *Andrew Owen* |
| *Last tested on HPC* | 2024-04-01| Christina Koch |

