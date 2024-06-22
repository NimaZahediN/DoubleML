# DoubleML Analysis

This project provides an analysis using the Double Machine Learning (DoubleML) framework for causal inference in high-dimensional settings. The notebook demonstrates the implementation of the DoubleML approach using various datasets and machine learning models.

## Overview

The Jupyter notebook `DoubleML.ipynb` includes the following main components:

1. **Setup and Installation**: Installation of necessary packages and libraries.
2. **Data Preparation**: Fetching and preprocessing data for analysis.
3. **Model Implementation**: Applying the DoubleML framework using machine learning models.
4. **Results and Analysis**: Evaluating the models and interpreting the results.

## Features

- **DoubleML Implementation**: Demonstrates the usage of the DoubleML library for causal inference.
- **Data Preprocessing**: Techniques for handling and preparing data for analysis.
- **Machine Learning Models**: Implementation of various machine learning models to evaluate causal effects.
- **Results Visualization**: Tools and methods for visualizing the results of the analysis.

## Installation

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

### Required Libraries

The following Python libraries are required to run the notebook:
- doubleml==0.3.0
- sklearn
- statsmodels==0.10.1
- numpy
- pandas
- tqdm


## File Description

- `DoubleML.ipynb`: Main Jupyter notebook containing the analysis.
- `README.md`: Project documentation.

## Data Description

The dataset used in this project is fetched from the `fetch_20newsgroups` dataset, which is preprocessed to create tf-idf vectors for text analysis. The dataset includes various categories such as computers, sports, and politics, which are used to demonstrate the DoubleML approach.

## License

This project is licensed under the MIT License.
