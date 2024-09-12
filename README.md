# Credit Card Fraud Detection with Machine Learning Models

The two main files are `data_prep.ipynb` and `model_training.ipynb`. Please view those two files for a comprehensive view of the project workflow.

## Data Imbalance Machine Learning Project

The following project is a machine learning project dedicated to tackling classification problems on imbalanced datasets. The data used in the project is obtained from an online Kaggle dataset. 

The following are the objectives of this project:

- Explore and understand the dataset given the limited information we have about the PCA transformed features
- Formulate solutions to tackle the class imbalance problem
- Use various model types and evaluate which best fits our usecase
- Evaluate the models using appropriate evaluation metrics

## Table of contents
- [Contents and Usage](#contents-and-usage)
- [Required Packages](#required-software-and-packages)
- [Data Source](#data-source)


## Contents and Usage:
The following repository is composed of two notebooks detailing the project workflow and a folder containing the confusion matrices from model evaluation. 

The first notebook, `data_prep.ipynb`, explores and visualizes the data to make decisions on data preperation and sampling, and then using those insights, cleans and samples the data to be ready for model training. 

The next and final notebook, `model_training.ipynb`, is the machine learning part of the project, where the sampled data is loaded and trained on various model types. Then the models are evaluated on the test data, and evaluation visualizations such as confusion matrices and ROC curves are plotted and saved.

Since not all the confusion matrices could be displayed in the `model_training.ipynb` notebook, I have created a folder showing all the standard and normalized confusion matrices from the model evaluations.

1. `data_prep.ipynb` — Data Exploration, Visualization, Cleaning, and Sampling
2. `model_training.ipynb` — Model Training and Evaluation

## Required Packages
These are the required Python packages to run the notebook codeblocks:

- imblearn
- Matplotlib
- NumPy
- Pandas
- Seaborn
- Scikit-learn (Sklearn)

##### Anaconda Installation

```
conda install -c conda-forge imbalanced-learn matplotlib numpy pandas seaborn scikit-learn
```

##### pip Installation

```
pip install imbalanced-learn matplotlib numpy pandas seaborn scikit-learn
```

## Data Source

The dataset is from a public [Kaggle dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data). The following is a link to the [data license](https://opendatacommons.org/licenses/dbcl/1-0/). 