# GIS Segmentation with UNet++

This repository contains code and resources for training a UNet++ model to perform semantic segmentation on geospatial data. The model is trained on a combination of RGBNIR and SAR (VV, VH) imagery, using a total of 6 channels to predict 14 land use/land cover classes.

## Overview

The repository includes two main Jupyter notebooks:

1. `gis_segmentation.ipynb`: This notebook contains the complete code for training the UNet++ model, including data loading, preprocessing, model definition, training loop, and evaluation. It serves as a comprehensive example of the entire workflow.

2. `baseline_segmentation.ipynb`: This notebook provides a starting point for participants, with code for downloading the necessary data and some utility functions. Participants can use this notebook as a foundation to build and train their own models.
