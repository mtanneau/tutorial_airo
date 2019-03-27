# Workflow and implementation tips

This repository contains material that was presented at the [Third AIROYoung workshop and PhD school](https://workshop.airoyoung.org/#workshop).

Slides are in the `slides/` folder.

Notebooks are in the `notebooks/` folder.
For each notebook, the `.ipynb` file is provided, as well as the corresponding `.html` export.
See instructions for running the notebooks below.


## Instructions for notebooks

TO run the notebooks, you need Jupyter installed on your machine.

### `version_control.ipynb`

An introduction to version control and git.

* Requires Git to be installed, and the Bash kernel available in Jupyter
* Before running the notebook, be sure that there is no folder named `tmp/` in the current directory.
* This notebook will modify the current directory. It should only be run exactly once, in the order of the cells.
* Use the `.html` file to see the output without having to install/run anything.

### `unit_test.ipynb`

A quick introduction to unit testing, illustrated in Julia.

* Requires Julia installed, and the Julia kernel for Jupyter (through the IJulia package)
* No additional package is required
