# Ice Speed Time-Series Toolbox

*** **CODE STILL IN DEVELOPMENT** *** not recommended for public use.

Python toolbox for the extraction, decomposition, and visualisation of time-series from SAR ice velocity datasets.


**Tool 1:** time_series_extraction.ipynb ---> Extract a time-series from a dataset of geotiff files.

**Tool 2:** time_series_decomposition.ipynb ---> Decompose a time-series into overall trend, seasonal variation, and residual signal.

**Tool 3:** glacier_mapping.ipynb ---> Visualise glacial flow with a velocity map of a user specified region.

An environment with all dependencies installed is required for correct functioning of these tools. MAD4SAR is my environment that can be actived using:

    conda env create -f environment.yml
