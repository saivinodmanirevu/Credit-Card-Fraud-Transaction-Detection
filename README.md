![Python 3.5](https://img.shields.io/badge/python-3.6-blue.svg)
# Credit-Card-Fraud-Transaction-Detection

Link to download the dataset - [Download](https://www.kaggle.com/mlg-ulb/creditcardfraud)

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Getting Started

The objective of this project is to create an efficient model which can detect credit card fraud detections despite
imbalanced data. The dataset used in this project is highly imbalanced (492 frauds out of 284,807 transactions).

### Prerequisites

As this Fraud detection model uses popular Python & it's libraries which are used to use build Machine Learning models.

```
Python 3
Numpy - For fast vectorized operations
Pandas - For better reading & working on datasets in CSV format
Matplotlib - For data visualization
seaborn - For creating eye catching plots & heatmaps
Sklearn - For accessing popular ML models, validation methods, & Evaluation metrics
```

### Installing

A step by step series of examples that tell you how to get a development env running

Install the Latest version of Python - [Download](https://www.python.org/downloads/)

**Instruction to install dependencies**
```
Numpy - pip install numpy
Pandas - pip install pandas
Matplotlib - pip install matplotlib
Seaborn  - pip install seaborn
```
you may use `pip3 install [name]` otherwise

**Test by typing in Python environment or Jupyter Notebook**
```
import sys
import numpy as np
import pandas as pd
import matplotlib
import seaborn as sb

print('Python : {}'.format(sys.version))
print('Numpy : {}'.format(np.__version__))
print('Matplotlib : {}'.format(matplotlib.__version__))
print('Seaborn : {}'.format(sb.__version__))
```
you'll get output similar to this
```
Python : 3.6.5 (v3.6.5:f59c0932b4, Mar 28 2018, 17:00:18) [MSC v.1900 64 bit (AMD64)]
Numpy : 1.15.1
Matplotlib : 2.2.2
Seaborn : 0.8.1
```

## Built With

* [Jupyter Notebook](http://jupyter.org/install) - Ipython notebook


## Authors

* **Sai Vinod Manirevu** - [linkedin - saivinodmanirevu](https://www.linkedin.com/in/saivinodmanirevu)
