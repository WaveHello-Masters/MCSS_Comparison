# Purpose

The purpose of this repo is to compare Oritz-Simo vs. Newton-Raphson substepping for stress integration.

To run these notebooks two other repositories are required:

1) [Incremental Driver with MCSS](https://github.com/CriticalSoilModels/MohrCoulomb_StrainSoft)
    * This repo contains the source .f90 files needed to generate the incremental driver - MCSS executable.
    * The recommened way to compile this repo is using the [fortran package manager](https://github.com/fortran-lang/fpm). 

2) [Pumat](https://github.com/CriticalSoilModels/pumat)
    * This is holds a series of python modules that are used to manage the incremental driver simulation. It generates the input files for incremental driver, runs the executable, and plots the results.

Acronyms:
* MCSS - Mohr-Coulomb Strain Softening  