# Ice Speed Time-Series Toolbox

*** **CODE STILL IN DEVELOPMENT** *** not recommended for public use.

Python toolbox for the extraction, decomposition, and visualisation of time-series from SAR ice velocity datasets.


**Tool 1:** time_series_extraction.ipynb ---> Extract a time-series from a dataset of geotiff files.

**Tool 2:** time_series_decomposition.ipynb ---> Decompose a time-series into overall trend, seasonal variation, and residual signal.

**Tool 3:** glacier_mapping.ipynb ---> Visualise glacial flow with a velocity map of a user specified region.


## Installation

An environment with all dependencies installed is required for correct functioning of these tools. `MAD4SAR.yml` is my environment that can be cloned using:

    conda env create -f MAD4SAR.yml

Then activated with:

    conda activate MAD4SAR


`polar-stereo-lonlat-convert-py` is a adapted from https://github.com/nsidc/polarstereo-lonlat-convert-py

`polar_convert` package contains Python functions for converting polar stereographic coordinates. `polar_lonlat_to_xy()` function was adapted for the northern hemisphere with a central meridian of -45 degrees to create a new function `polar_lonlat_north_to_xy()`. The original software was developed by the NASA National Snow and Ice Data Center Distributed Active Archive Center, Chris Torrence, September 2019.

To install `polarstereo-lonlat-convert-py`, clone this repo and then run:

    pip install --editable /path/to/cloned/polarstereo-lonlat-convert-py

See the NSIDC github repositiory for more information.
