# spam-mail-detection
The objective of this data competition is to apply various predictive modeling techniques to accurately predict whether an email is spam or not.

**Data:**

The “train_data.csv” contains a dataset of 3320 emails that is used to train classification models. Each row is an identical email. There are 58 columns explained below.
* 54 Columns “word_freq_make” through “char_freq_#”: Relative frequency of words/characters in the email;
* “capital_run_length_average”: average length of uninterrupted sequences of capital letters;
* “capital_run_length_longest”: length of longest uninterrupted sequence of capital letters;
* “capital_run_length_total”: total number of capital letters in the e-mail;
* “class”: a number denotes whether the email is spam or not (1=spam, 0=not spam).

The “test_data.csv” contains a dataset of 1381 emails that is used to evaluate the performance of classification models. The test dataset has the same data structure as the training dataset.

**Task:**

Apply various predictive modeling techniques to build a classification model that performs very well for predicting if an email is a spam mail.
You can only use the training dataset to train the classification models without touching the test dataset. Using test dataset to as a validation set to refine your models is also not allowed. You can normalize/transform the variables in the test dataset, but any resampling applied to the test dataset is not allowed. The test dataset is only used to evaluate the performance of your model. Your models need to be evaluated by AUC score (**Area under the ROC curve, using the method sklearn.metrics.roc_auc_score() to calculate**).

**Prerequisites:**

* Install **jupyter notebook** and corresponding packages.

* Install Python 3.9.6 https://www.python.org/downloads/macos/

* Install Certificate 
```bash
$ pip3 install certifi 
````
* Install jupyter notebook
```bash
$ pip3 install --upgrade jupyter
````
* Install matplotlib seaborn numpy scipy pandas sklearn
```bash
$ pip3 install --upgrade matplotlib seaborn numpy scipy pandas sklearn
````
* Install patsy https://stackoverflow.com/questions/11788900/importerror-no-module-named-statsmodels
```bash
$ pip3 install --upgrade patsy
````
* Install statsmodels
```bash
$ pip3 install statsmodels
````
* To check what packages have been installed in the environment
```bash
$ pip3 freeze
````
* Install graphviz
```bash
$ brew install graphviz
````
* Install 
```bash
$ pip install pydotplus
````
* Run jupyter notebook Open your mac terminal
```bash 
$ cd /spam-mail-detection
$ jupyter notebook
````
