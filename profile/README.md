# pyiron - Complex Workflows made easy 
From rapid prototyping to high performance computing in material science

|        Website :compass:         |                 Documentation :books:                  |                 Workshops :rocket:                 |
|:--------------------------------:|:------------------------------------------------------:|:--------------------------------------------------:|
| [pyiron.org](https://pyiron.org) | [pyiron.readthedocs.io](https://pyiron.readthedocs.io) | [workshop.pyiron.org](https://workshop.pyiron.org) |

## Stable Version :mountain_snow:
The stable `pyiron` version is developed based on the generic `job object` class to handle the execution and storage of calculations and post-processing of experimental data. A range of different modules are available:

| Repository                                                                   | Description                                                                                                                |                           Conda Package                           |
|------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------:|
| [pyiron](https://github.com/pyiron/pyiron)                                   | A meta package which seamlessly loads all the pyiron plugins installed on a given system.                                  |       [:package:](https://anaconda.org/conda-forge/pyiron)        |
| [pyiron_atomistics](https://github.com/pyiron/pyiron_atomistics)             | An interface to atomistic simulation codes including but not limited to GPAW, LAMMPS, S/Phi/nX and VASP.                   |  [:package:](https://anaconda.org/conda-forge/pyiron_atomistics)  |
| [pyiron_base](https://github.com/pyiron/pyiron_base)                         | A package for the core compotents e.g. the job management, data storage and resource management.                           |     [:package:](https://anaconda.org/conda-forge/pyiron_base)     |
| [pyiron_continuum](https://github.com/pyiron/pyiron_continuum)               | Modules for pyiron supporting continuum scale simulations and workflows.                                                   |  [:package:](https://anaconda.org/conda-forge/pyiron_continuum)   |
| [pyiron_contrib](https://github.com/pyiron/pyiron_contrib)                   | A package to collect contributions from the pyiron community.                                                              |   [:package:](https://anaconda.org/conda-forge/pyiron_contrib)    |
| [pyiron_dpd](https://github.com/pyiron/pyiron_dpd)                           | Automated Defect Phase Diagrams and Workflow Prototypes.                                                                   |                                                                   |
| [pyiron_experimental](https://github.com/pyiron/pyiron_experimental)         | Post processing workflows for experimental applications.                                                                   | [:package:](https://anaconda.org/conda-forge/pyiron_experimental) |
| [pyiron_electrochemistry](https://github.com/pyiron/pyiron_electrochemistry) | Workflows and analysis tools for computational electrochemistry using pyiron.                                              |                                                                   |
| [pyiron_gpl](https://github.com/pyiron/pyiron_gpl)                           | A package for all interfaces which require a GPL license in contrast to the BSD license used by all other pyiron packages. |     [:package:](https://anaconda.org/conda-forge/pyiron_gpl)      |
| [pyiron_potentialfit](https://github.com/pyiron/pyiron_potentialfit)         | Fit machine learning interatomic potentials using pyiron.                                                                  | [:package:](https://anaconda.org/conda-forge/pyiron_potentialfit) |

## Standalone Packages :truck:
To increase the maintainability of the `pyiron` project, there is a continuous release of spin-off packages which are used inside `pyiron`, but which can also be used as standalone packages:

| Repository                                                     | Description                                                                                                                                  |                 Documentation                  |                         Conda Package                          |
|----------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------:|:--------------------------------------------------------------:|
| [atomistics](https://github.com/pyiron/atomistics)             | Interfaces for atomistic simulation codes and workflows                                                                                      |  [:books:](https://atomistics.readthedocs.io)  |    [:package:](https://anaconda.org/conda-forge/atomistics)    |
| [pyfileindex](https://github.com/pyiron/pyfileindex)           | Pythonic file system index                                                                                                                   |                                                |   [:package:](https://anaconda.org/conda-forge/pyfileindex)    |
| [pyiron_lammps](https://github.com/pyiron/pyiron_lammps)       | Vector-oriented LAMMPS interface to rapidly iterate over series of atomistic structures or interatomic potentials.                           |                                                |  [:package:](https://anaconda.org/conda-forge/pyiron_lammps)   |
| [pylammpsmpi](https://github.com/pyiron/pylammpsmpi)           | Parallel Lammps Python interface - control a mpi4py parallel LAMMPS instance from a serial python process or a Jupyter notebook.             |                                                |   [:package:](https://anaconda.org/conda-forge/pylammpsmpi)    |
| [pympipool](https://github.com/pyiron/pympipool)               | Scale serial and MPI-parallel python functions over hundreds of compute nodes all from within a jupyter notebook or serial python process.   |  [:books:](https://pympipool.readthedocs.io)   |    [:package:](https://anaconda.org/conda-forge/pympipool)     |
| [pysqa](https://github.com/pyiron/pysqa)                       | Simple HPC queuing system adapter for Python on based jinja templates to automate the submission script creation.                            |    [:books:](https://pysqa.readthedocs.io)     |      [:package:](https://anaconda.org/conda-forge/pysqa)       |
| [structuretoolkit](https://github.com/pyiron/structuretoolkit) | Build, analyse and visualise atomistic structures for materials science.                                                                     |                                                | [:package:](https://anaconda.org/conda-forge/structuretoolkit) |

## Next Generation Developments :rocket:
Based on the experience with the stable pyiron version and the success of the standalone packages, the pyiron framework continuous to innovate in the field of workflows for materials science. At the current stage `pyiron_workflow` is planned to be the future replacement of `pyiron_base` towards a more functional approach to workflows:

| Repository                                                   | Description                                                             |                         Conda Package                         |
|--------------------------------------------------------------|-------------------------------------------------------------------------|:-------------------------------------------------------------:|
| [ironflow](https://github.com/pyiron/ironflow)               | Prototype of a graphical user interface for pyiron (unstable)           |    [:package:](https://anaconda.org/conda-forge/ironflow)     |            
| [pyiron_gui](https://github.com/pyiron/pyiron_gui)           | Extended graphical user interface (GUI) for the stable pyiron version   |   [:package:](https://anaconda.org/conda-forge/pyiron_gui)    |          
| [pyiron_ontology](https://github.com/pyiron/pyiron_ontology) | Combining pyiron and owlready2 for ontologically guided workflow design | [:package:](https://anaconda.org/conda-forge/pyiron_ontology) |
| [pyiron_workflow](https://github.com/pyiron/pyiron_workflow) | Graph-and-node based workflows                                          | [:package:](https://anaconda.org/conda-forge/pyiron_workflow) |
 

## Infrastructure :robot:
In addition to the `pyiron` software packages in this organisation, there are a couple of repositories to automate the maintainence of the pyiron project:

| Repository                                                                           | Description                                                                                                    |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| [actions](https://github.com/pyiron/actions)                                         | A centralized location for our GitHub actions                                                                  |
| [docker-stacks](https://github.com/pyiron/docker-stacks)                             | Ready-to-run Docker images containing pyiron applications                                                      |
| [pyiron-installer](https://github.com/pyiron/pyiron-installer)                       | pyiron installer based on conda constructor                                                                    |
| [pyiron_module_template](https://github.com/pyiron/pyiron_module_template)           | A template to generate a new pyiron module.                                                                    |
| [pyiron-publication-template](https://github.com/pyiron/pyiron-publication-template) | Template repository - how to publish your pyiron workflow                                                      |
| [pyiron-resources](https://github.com/pyiron/pyiron-resources)                       | Resource folder for pyiron - an integrated development environment (IDE) for computational materials science.  |

## Publication :books:
Example publication demonstrating how `pyiron` accelerates research and covers the whole simulation life cycle up to the publication of the results:

| Repository                                                                       | Title                                                                                                                                                 | Autors                                                                                                                                                        | Journal |
|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| [pyiron_meltingpoint](https://github.com/pyiron/pyiron_meltingpoint)             | [A fully automated approach to calculate the melting temperature of elemental crystals](https://www.sciencedirect.com/science/article/pii/S0927025620305565)                                                             | Li-Fang Zhu, Jan Janssen, Shoji Ishibashi, Fritz Körmann, Blazej Grabowski and Joerg Neugebauer                                                               | Computational Materials Science 187, 110065 |
| [pyiron_generalized_dipole](https://github.com/pyiron/pyiron_generalized_dipole) | [Generalized dipole correction for charged surfaces in the repeated-slab approach](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.045403) | Christoph Freysoldt, Arpit Mishra, Michael Ashton and Joerg Neugebauer                                                                                        | Physical Review B 102, 045403 |
| [pyiron_md_montecarlo](https://github.com/pyiron/pyiron_md_montecarlo)           | [Interplay of Chemistry and Faceting at Grain Boundaries in a Model Al Alloy](https://link.aps.org/doi/10.1103/PhysRevLett.124.106102)                | Huan Zhao, Liam Huber, Wenjun Lu, Nicolas J. Peter, Dayong An, Frédéric De Geuser, Gerhard Dehm, Dirk Ponge, Joerg Neugebauer, Baptiste Gault and Dierk Raabe | Physical Review Letters 124, 106102 | 