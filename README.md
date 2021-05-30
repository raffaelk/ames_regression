# House Price Prediction with Scikit-Learn and Spark

The goal of this project is to predict house prices from a set of features describing each home. This task is a famous kaggle competition and often used to try different ML techniques. More information can be found on the [competition page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Main Technologies Used
- Language: Python 
- ML Pipeline: scikit-learn, PySpark

## Model
In the notebook [ames_sklearn.ipynb](ames_sklearn.ipynb) (or [open with nbviewer](https://nbviewer.jupyter.org/github/raffaelk/ames_regression/blob/main/ames_sklearn.ipynb)) a machine learning pipeline is set up using scikit-learn. As the used data set is rather small, this would be the preferred way. In the notebook [ames_pyspark.ipynb](ames_pyspark.ipynb) (or [open with nbviewer](https://nbviewer.jupyter.org/github/raffaelk/ames_regression/blob/main/ames_pyspark.ipynb)) the big data framework Apache Spark is used to create a machine learning pipeline. For the size of the data set this is less efficient than using scikit-learn, but it scales a lot better to bigger data sets, which would probably rather be used in a real-world scenario.
