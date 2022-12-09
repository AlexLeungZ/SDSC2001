# SDSC2001 Python for Data Science

## Setting up running environment (with conda)

### Install Conda or mamba (mini-conda)

### Set up for conda-forge

```bash
conda config --add channels conda-forge
```

### Set up conda environment

```bash
conda create -n 2001
conda activate 2001
```

### Install package (mamba is recommended)

```bash
conda install -c conda-forge Jupyter ipykernel
conda install -c conda-forge pandas numpy seaborn matplotlib scikit-learn
```
