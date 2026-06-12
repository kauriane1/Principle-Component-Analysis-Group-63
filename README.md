# Principal Component Analysis (PCA) from Scratch

## Overview

This project implements Principal Component Analysis (PCA) from scratch using only NumPy and Matplotlib, as required for the Advanced Linear Algebra formative assignment. The objective is to reduce the dimensionality of an African dataset while preserving as much variance as possible.

## Features

* Handling of missing (NaN) values through imputation.
* Encoding of non-numeric categorical variables.
* Data standardization.
* Covariance matrix computation.
* Eigenvalue and eigenvector decomposition.
* Dynamic selection of principal components based on explained variance.
* Visualization of data before and after PCA.
* Performance benchmarking on larger datasets.

## Repository Contents

* `PCA_Assignment.ipynb` – Complete notebook implementation.
* `dataset.csv` – Dataset used for the analysis.
* `Contribution_Sheet.pdf` – Group contribution record.

## Technologies Used

* Python
* NumPy
* Matplotlib

## Key Findings

The selected principal components retain the majority of the dataset's variance while reducing dimensionality. This demonstrates how PCA can simplify complex datasets and reveal underlying patterns with minimal information loss.

## Authors

Prepared as part of the Advanced Linear Algebra course formative assignment.
