<h1 align="center">Linear Discriminant Analysis With Python Blog</h1>

![img](img/kajori4.png)

##  Linear Discriminant Analysis

### Main Idea:

* Linear Discriminant Analysis is a linear classification machine learning algorithm.

The algorithm involves developing a probabilistic model per class based on the specific distribution of observations for each input variable. A new example is then classified by calculating the conditional probability of it belonging to each class and selecting the class with the highest probability.

As such, it is a relatively simple probabilistic classification model that makes strong assumptions about the distribution of each input variable, although it can make effective predictions even when these expectations are violated (e.g. it fails gracefully).

* Basically,Linear Discriminant Analysis (LDA) is a dimensionality reduction technique. As the name implies dimensionality reduction techniques reduce the number of dimensions (i.e. variables) in a dataset while retaining as much information as possible. For instance, suppose that we plotted the relationship between two variables where each color represent a different class.

### Code:

Let’s see how we could go about implementing Linear Discriminant Analysis from scratch using Python. To start, import the following libraries.
```
 from sklearn.datasets import load_wine
 import pandas as pd
 import numpy as np
 np.set_printoptions(precision=4)
 from matplotlib import pyplot as plt
 import seaborn as sns
 sns.set()
 from sklearn.preprocessing import LabelEncoder
 from sklearn.tree import DecisionTreeClassifier
 from sklearn.model_selection import train_test_split
 from sklearn.metrics import confusion_matrix
```
### For eg,we’ll be working with the wine dataset which can be obtained from the UCI machine learning repository. Fortunately, the scitkit-learn library provides a wrapper function for downloading and
```
 wine = load_wine()X = pd.DataFrame(wine.data, columns=wine.feature_names)
 y = pd.Categorical.from_codes(wine.target, wine.target_names)
```
### The dataset contains 178 rows of 13 columns each.
```
 X.shape
```



### The features are composed of various characteristics such as the magnesium and alcohol content of the wine.
```
 X.head() 
```





