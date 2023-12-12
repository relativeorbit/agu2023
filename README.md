# AGU 2023 Poster
"Practical cloud computing for InSAR" 

Authors: Scott Henderson, Eric Gagliano, Emma Marshall, George Brencher, David Shean

This repository contains the PDF for our 2023 AGU Poster from the session "Recent Advances in SAR and InSAR Processing, Big Data Analysis, and Earth Science". You will also find several Jupyter Notebooks with Python code written to generate the figures on the poster, which we created using the [ASF OpenSARLab JupyterHub](https://opensciencelab.asf.alaska.edu/).

[Poster PDF](./AGU_2023_Poster.pdf)


## Poster references

The poster links to some examples, URLs copied below for easy reference: 

- https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/relativeorbit/agu2023/main/catalog.json?.language=en
    - By creating a STAC catalog for ASF Hyp3 sentinel-1 burst products, the data are publically available (for two weeks) and the archive is easy to navigate for collaborators. The notebooks to re-run product generation, generate STAC catalog, and generate a first-pass time series from unwrapped interferograms are in this repository
    
- https://github.com/egagli/sar_snowmelt_timing
    - Repository of notebooks and tools to identify snowmelt timing using time series analysis of backscatter of Sentinel-1 C-band SAR using Microsoft Planetary Computer [Global RTC Product](https://planetarycomputer.microsoft.com/dataset/sentinel-1-rtc)

- https://geosmart.hackweek.io/tutorials/computing
    - Comparison of pre-configured cloud computing platforms for geoscientists

- https://github.com/scottyhq/opera 
    - OPERA spatial mosaics created with Python Xarray Library 

- https://guide.cloudnativegeo.org
    - A great starting place to learn more about data formats optimized for cloud computing!
    
- https://discourse.pangeo.io
    - A public community forum for topics related to open science, software integration, and scalable scientific analysis
    

### Other helpful links

-  https://github.com/ASFHyP3/hyp3-isce2 
    - Hyp3 ISCE2 Burst Processor
-  https://github.com/opera-adt 
    - OPERA github org
-  https://github.com/OPERA-Cal-Val/OPERA_Applications 
    - OPERA Example Notebooks
- https://github.com/opendatacube/odc-stac
    - Read STAC catalogs into Xarray data cubes