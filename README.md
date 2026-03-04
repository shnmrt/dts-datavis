# dts-datavis

This repository contains data visualisations of the data-acquisition frequency from geothermal doublets and the temperature change over time from DTS measurements.

# managing the dependencies

## with conda

```bash
conda create -n dts-heatmap python=3.11 # will create a virtual environment
conda activate dts-heatmap # will activate the virtual environment
conda install -c conda-forge pyecharts duckdb jupyter
```

## with python venv

```bash
python -m venv heatmap
# for windows
heatmap\Scripts\activate
# for linux/macos
source heatmap/bin/activate
# install the dependencies
pip install pyecharts duckdb jupyter
```

Following managing the environment, spin up your favourite IDE and run the cells in the notebook.
