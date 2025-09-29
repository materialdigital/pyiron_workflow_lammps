# LAMMPS example (pyiron_workflow)
This repository demonstrates a minimal LAMMPS workflow using the `pyiron_workflow` framework.

You can fork this repository and populate it with your own data.

## Installation
Create and activate the conda environment from the provided `environment.yml`:

```bash
# Using mamba (recommended)
mamba env create -f environment.yml -n pyiron-workflow-lammps
conda activate pyiron-workflow-lammps

# Or using conda
conda env create -f environment.yml -n pyiron-workflow-lammps
conda activate pyiron-workflow-lammps

# To update an existing environment after changes to environment.yml
mamba env update -f environment.yml -n pyiron-workflow-lammps
# or
conda env update -f environment.yml -n pyiron-workflow-lammps
```

## Run the workflow
Open and execute the notebook `example.ipynb` in this directory:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `example.ipynb` and run all cells.