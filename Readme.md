# Disk Population Synthesis Data

## Part 1

Part 1 of the [notebook](https://github.com/birnstiel/dpopsynth_results/blob/master/get_results.ipynb) takes the simulation results (e.g. dust surface densities, ...) and for one exemplary simulation calculates the emission profiles and the effective radii and fluxes at different wavelength points.

## Part 2

Part 2 of the [notebook](https://github.com/birnstiel/dpopsynth_results/blob/master/get_results.ipynb) reads in the effective radii and fluxes that have been pre-calculated and are stored in [`results_table.dat`](https://github.com/birnstiel/dpopsynth_results/blob/master/results_table.dat). It then shows how to access/process the data.

## Requirements

You need

- the contents of this repository
- `twopoppy`
- the big (~700 MB) data file `v3_stick.pbz2` (download it from [here](https://dl.dropboxusercontent.com/s/cysai0ynwvhtz69/v3_stick.pbz2))


To install `twopoppy`, run this (in the folder where you want to store the code):

    git clone https://github.com/birnstiel/two-pop-py
    cd two-pop-py
    pip install -e .
