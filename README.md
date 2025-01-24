# Calculation of remaining carbon budget to 1.5°C and 2°C in Storelvmo et al. (2025)

This repository produces the remaining carbon budget calculation and distribution figure 6 in Storevlmo et al. (accepted), Environmental Research Letters. The remaining carbon budget calculation uses the methodology of [Matthews et al. (2021)](https://www.nature.com/articles/s43247-020-00064-9), using a large Monte Carlo ensemble of each component of this method, with the updated empirical TCRE distribution from Storelvmo et al. (accepted).

![Distribution of remaining carbon budget to 1.5°C and 2°C](figures/rcb.png?raw=true)

## reproduction

This workflow uses `anaconda` and `python`; this is a pre-requisite to reproducing the figure.

After cloning the repository to your local machine, run

```
cd storelvmo-2025
conda env create -f environment.yml    # will set up conda environment, may take several minutes
conda activate storelvmo-2025
jupyter notebook
```

In `jupyter`, navigate to `notebooks` and simply execute the notebook. All required data is provided.
