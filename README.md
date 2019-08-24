# ml-hello-world
## Steps to a Machine Learning project
1. Define problem
2. Prepare data
3. Evaluate algorithms
4. Improve results
5. Present results

The best way to really come to terms with a new platform or tool is to work through a machine learning project end-to-end and cover the key steps. Namely, from loading data, summarizing data, evaluating algorithms and making some predictions.

## Setup Python and SciPy libraries
1. Download python using [Anaconda Distribution](https://www.anaconda.com/distribution/)
2. Below is a list of the Python SciPy libraries required for this tutorial:
   + scipy
   + numpy
   + matplotlib
   + pandas
   + sklearn

Above libraries should be available if you setup python using Anaconda distribution.

## [Iris flowers classification](/Iris-flowers/Iris_flowers_classification.ipynb)
### Problem statement
Classification of Iris flowers
### Dataset
[Iris Dataset](https://archive.ics.uci.edu/ml/datasets/Iris)  
This is a good project because it is so well understood.

Attributes are numeric so you have to figure out how to load and handle data.
+ It is a classification problem, allowing you to practice with perhaps an easier type of supervised learning algorithm.
+ It is a multi-class classification problem (multi-nominal) that may require some specialized handling.
+ It only has 4 attributes and 150 rows, meaning it is small and easily fits into memory (and a screen or A4 page).
+ All of the numeric attributes are in the same units and the same scale, not requiring any special scaling or transforms to get started.

## [Census income](/Census-income/Census_income_classification.ipynb)
### Problem statement
Classification of income of a person based on given features
### Dataset
[Census income dataset](https://archive.ics.uci.edu/ml/datasets/Adult)
