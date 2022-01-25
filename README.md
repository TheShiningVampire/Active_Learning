# Active Learning for Image Classification

## Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Usage](#usage)

## About <a name = "about"></a>
Active learning is the name used for the process of prioritizing the data which needs to be labelled in order to have the highest impact to training a supervised model. Active learning can be used in situations where the amount of data is too large to be labelled and some priority needs to be made to label the data in a smart way. This notebook contains the code written as a part of the project for GNR638 on Active Learning for Image Classification.


### Prerequisites

To install the submodlib library included in this repository, run the following command:

```
pip install -i https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ submodlib
```

All the required libraries are included in the requirements.txt file. Install them using pip.

```
pip install -r requirements.txt
```

## Usage <a name = "usage"></a>

All the necessary code is included in the DISTIL_MNIST.ipynb file. Run the notebook to get started. To obtain the plots for accuracy comparison, run the cells from notebook "Plots for MNIST.ipynb".