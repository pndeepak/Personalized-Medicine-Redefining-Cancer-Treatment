# Personalized Medicine: Redefining Cancer Treatment 
<img src='https://storage.googleapis.com/kaggle-competitions/kaggle/6841/media/79842_Web-hero-image_ALT-3.jpg'>

<a href="https://colab.research.google.com/drive/1z6F_HdNev7Fvowxzihjm9XXs239Edi3X#scrollTo=xCjRvTxKOQuR" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Problem Description

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 
Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

<b> Problem statement: </b>

Develop Machine Learning algorithm that, using gene knowledge base as a baseline, automatically classifies genetic variations.

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/overview

# Overview

This is a multiclass classification problem where we have to classify the given data into 9 various classes. This notebook will demonstrate several ML algorithms and their comparisons based on multi class log-loss.

# Notebook contents

- Problem Description
- Problem Overview
- Exploratory Data Analysis
- Data splitting and vectorization
- Machine Learning Models
- Comparison of all ML models

# Algorithms used

- Naive Bayes
- Logistic Regression
- Linear SVM
- Stacking classifier
- Majority Voting Classifier

# Tools and technologies used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=170>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://clay-atlas.com/wp-content/uploads/2019/08/python_nltk.png" width=180 height=100>](https://www.nltk.org/) [<img target="_blank" src="https://miro.medium.com/max/1400/1*7oukapIBInsovpHkQB3QZg.jpeg" width=200>](https://colab.research.google.com/) 
