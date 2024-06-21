# EETSS
Code Repository for the EETSS Framework developed to create features for multivariate time series data

This repository contains the code for a feature generation framework specifically designed for multivariate time series data. The algorithm is described in detail in the accompanying journal paper (preprint edition), available below-
https://www.researchsquare.com/article/rs-4156209/v1

# Notebooks
This repository includes two Jupyter notebooks:

1. Eigen_Entropy_Based_Time_Series_Signature_Generation.ipynb
This notebook generates features from raw time series data using eigen entropy-based time series signature generation. It is the first step in the feature generation process.

2. Feature_Selection_Framework_Output.ipynb
After generating the signatures in the first notebook, this notebook is used for feature selection. It refines the generated features to identify the most relevant ones for your analysis.

# Dataset
You can use the Finger Movements (https://www.timeseriesclassification.com/description.php?Dataset=FingerMovements) dataset as a test for the functioning of the algorithm. Download the dataset and follow the instructions in the notebooks to preprocess and generate features.

