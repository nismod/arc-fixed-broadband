# Fixed Broadband Analysis for Arc scenarios

Estimate fixed broadband network rollout costs. Take [Urban Development
Model](https://github.com/geospatialncl/urban_development_model) outputs for high-resolution
population/built environment scenarios, based on zonal (Local Authority District) scenarios
from [`nismod/arc-scenarios`](https://github.com/nismod/arc-scenarios), and apply statistical
cost/coverage estimates.

## Setup and run

Create a [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/index.html) environment with all dependencies:

    conda env create -f environment.yml

Download the data folder (available on request).

Copy `config.template.json` to `config.json` and fill in the path to the data folder.

Run the notebooks:

    jupyter notebook
