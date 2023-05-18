# yuan-tcre

This repository produces the remaining carbon budget distribution figure in Yuan et al. (in review).

## reproduction

This workflow uses `anaconda` and `python`; this is a pre-requisite to reproducing the figure.

After cloning the repository to your local machine, run

```
cd yuan-tcre
conda env create -f environment.yml    # will set up conda environment, may take several minutes
conda activate yuan-tcre
jupyter notebook
```

In `jupyter`, navigate to `notebooks` and simply execute the notebook. All required data is provided.
