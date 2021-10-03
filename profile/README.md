## Hi there 👋

pyiron is an integrated development environment (IDE) for materials science. It consists of the following modules: 

* [pyiron](https://github.com/pyiron/pyiron) - A meta package which seamlessly loads all the pyiron plugins. 
* [pyiron_base](https://github.com/pyiron/pyiron_base) - A package for the core compotents e.g. the job management, data storage and resource management. 
* [pyiron_atomistics](https://github.com/pyiron/pyiron_atomistics) - A interface to atomistic simulation codes including but not limited to GPAW, LAMMPS, S/Phi/nX and VASP. 
* [pyiron_contrib](https://github.com/pyiron/pyiron_contrib) - A package to collect contributions from the pyiron community.
* [pyiron_gpl](https://github.com/pyiron/pyiron_gpl) - A package for all interfaces which require a GPL license in contrast to the BSD license used by all other pyiron packages. 
* [pyiron_continuum](https://github.com/pyiron/pyiron_continuum) - A package to extent pyiron to the contiuum scale. 
* [pyiron_experimental](https://github.com/pyiron/pyiron_experimental) - A package to apply pyiron for the post-processing of experimental measurements. 
* [pyiron_gui](https://github.com/pyiron/pyiron_gui) - A graphical user interface for pyiron based on ipywidgets. 

When using pyiron for scientific publications please cite: 
```
  @article{pyiron-paper,
    title = {pyiron: An integrated development environment for computational materials science},
    journal = {Computational Materials Science},
    volume = {163},
    pages = {24 - 36},
    year = {2019},
    issn = {0927-0256},
    doi = {https://doi.org/10.1016/j.commatsci.2018.07.043},
    url = {http://www.sciencedirect.com/science/article/pii/S0927025618304786},
    author = {Jan Janssen and Sudarsan Surendralal and Yury Lysogorskiy and Mira Todorova and Tilmann Hickel and Ralf Drautz and Jörg Neugebauer},
    keywords = {Modelling workflow, Integrated development environment, Complex simulation protocols},
  }
```
