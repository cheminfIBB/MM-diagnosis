# 1. Data preprocessing and exploratory analysis
- [ ] deal with [missing values](http://scikit-learn.org/stable/modules/preprocessing.html#imputation-of-missing-values) and [categorical variables](http://pandas.pydata.org/pandas-docs/stable/categorical.html) (use [one-hot encoding](http://scikit-learn.org/stable/modules/preprocessing.html#encoding-categorical-features))
- [ ] check for correlated variables
- [ ] analyse distributions of attributes
- [ ] visualise the data using two or three [principal components](http://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)

# 2. Logistic Regression model

# 3. More advanced models

## 3.1 Random Forest

## 3.2. Support Vector Machine

## 3.3. Feed Forward Neural Network

---

For each model:
* [standarize](http://scikit-learn.org/stable/modules/preprocessing.html#standardization-or-mean-removal-and-variance-scaling) the dataset
* use the same [cross-validation](http://scikit-learn.org/stable/modules/cross_validation.html) scheme
* inspect feature importance
* evaluate model with logloss, ROC-AUC and F1 [classification metrics](http://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics)

---

# Resources

* [dataset](https://archive.ics.uci.edu/ml/datasets/Mesothelioma%C3%A2%E2%82%AC%E2%84%A2s+disease+data+set+#)
* [paper](http://www.sciencedirect.com/science/article/pii/S0045790611001261)
* [Python Machine Learning](https://sebastianraschka.com/books.html#python-machine-learning) by Sebastian Raschka
* interesting talks:
    * [Machine Learning 101](https://www.youtube.com/watch?v=r-1XJBHot58) by Kyle Kastner (+ GitHub [repo](https://github.com/kastnerkyle/PyCon2015))
    * [Classification using Pandas and Scikit-Learn](https://www.youtube.com/watch?v=7gAZoK6kGhM) by Skipper Seabold (+ GitHub [repo](https://github.com/jseabold/depy))
    * [Machine Learning with Scikit-Learn](https://www.youtube.com/watch?v=L7R4HUQ-eQ0) by Jake VanderPlas (+ GitHub [repo](https://github.com/jakevdp/sklearn_pycon2015))
    * [Neural Nets for Newbies](https://www.youtube.com/watch?v=g-BJSl4zV_g) by Melanie Warrick (+ GitHub [repo](https://github.com/nyghtowl/Neural_Net_Newbies))


### Keywords:
* dimensionality reduction
* cross-validation
* supervised vs unsupervised learning
* regression vs classification
* confidence intervals and p-values


---

# Tools
* [conda](http://conda.pydata.org/docs/)
* [jupyter notebook](http://jupyter.org/)
* [pandas](http://pandas.pydata.org)
* [sklearn](http://scikit-learn.org/)
* [seaborn](http://seaborn.pydata.org/)
