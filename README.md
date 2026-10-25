# Microfluidic Engineering

**Dr. Francisco Tovar**

Tutorials and computational examples connecting fluid mechanics, microfluidic design, experiments, Python and OpenFOAM.

> **Understand the engineering problem first. Then choose the model or computational tool.**

## Getting started on Windows

Open **Miniforge Prompt**:

```bash
conda activate research
jupyter lab
```

First-time package installation:

```bash
conda activate research
conda install -c conda-forge jupyterlab notebook ipykernel numpy scipy pandas matplotlib
jupyter lab
```

To recreate the environment:

```bash
conda env create -f environment.yml
conda activate research
jupyter lab
```

## Structure

- `tutorials/` — Jupyter engineering tutorials
- `openfoam/` — reproducible CFD cases
- `python/` — analysis and post-processing tools
- `geometries/` — geometry examples
- `data/` — small example datasets
- `references/` — supporting literature

## Tutorials

### Tutorial 1: Flow Development Length
#### How much straight channel do I need?

### Tutorial 2: Flow Rate and Velocity
#### What does my syringe-pump flow rate mean inside the microchannel?

## Philosophy

**Physical problem → engineering question → simple model → calculation → parameter exploration → assumptions → limitations → more advanced model when required**
