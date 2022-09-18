# ML Engineer training projects

## Context
These projects were made as part of my Machine Learning Engineer & Data Scientist training at OpenClassrooms & CentraleSupélec (an Engineering School part of Paris-Saclay University).

Therefore, **comments and Markdown cells are in French** (mandatory at OpenClassrooms). Don't hesitate to contact me if you have any question.

## The projects

All projects are made using Python and Jupyter Notebook.

### 01 - [Concevez une application au service de la santé publique](https://github.com/fauconnier-n/ML-Engineer-OpenClassrooms-projects/tree/main/01%20-%20Concevez%20une%20application%20au%20service%20de%20la%20sant%C3%A9%20publique)

**Exploratory Data Analysis of the Open Food Facts database**
This project contains Data Cleaning, Exploratory Data Analysis (uni and multivariate), and Dimensional Reduction (PCA).

### 02 - [Anticipez les besoins en consommation de bâtiments](https://github.com/fauconnier-n/ML-Engineer-OpenClassrooms-projects/tree/main/02%20-%20Anticipez%20les%20besoins%20en%20consommation%20de%20b%C3%A2timents)

**CO2 emissions & energy consumption prediction of Seattle's buildings**
This project is focused on using Machine Learning to predict yearly CO2 emissions and energy consumption of buildings given their characteristics.
It contains EDA, feature engineering & selection, training of the models, hyperparameter optimization (GridSearchCV) of the selected models (Ridge Regression and XGBoost), and model evaluation.

### 03 - [Segmentez des clients d'un site e-commerce](https://github.com/fauconnier-n/ML-Engineer-OpenClassrooms-projects/tree/main/03%20-%20Segmentez%20des%20clients%20d'un%20site%20e-commerce)

**Segmentation of an e-commerce platform's customer database**
The goal of this project is to use Unsupervised Machine Learning to segment customers in clusters usable/interpretable by a CRM team.
This project contains: EDA, Data Cleaning, feature selection, training of the models (KMeans, DBScan, agglomerative clustering, PCA), analysis of the clusters, and an attempt to estimate the best retraining frequency of the final model (KMeans).

### 04 - [Catégorisez automatiquement des questions](https://github.com/fauconnier-n/ML-Engineer-OpenClassrooms-projects/tree/main/04%20-%20Cat%C3%A9gorisez%20automatiquement%20des%20questions)

**A REST API that returns the predicted tags of a StackOverflow question**
API made with FastAPI and deployed on Heroku. It runs an NLP ML model to predict the tags and associated probabilities.
The notebooks contain: data cleaning, pre-processing, EDA, Dimentional Reduction, different feature extractions (TF-IDF, Word2Vec, BERT, Universal Sentence Encoder) supervised and unsupervised learning (Latent Dirichlet Allocation)

### 05 - [Classez des images à l'aide d'algorithmes de Deep Learning](https://github.com/fauconnier-n/ML-Engineer-OpenClassrooms-projects/tree/main/05%20-%20Classez%20des%20images%20%C3%A0%20l'aide%20d'algorithmes%20de%20Deep%20Learning)

**Classification of dog pictures using Deep Learning**
Focused on using Keras and DL, this project contains: Data Cleaning, pre-processing, Data Augmentation, training of multiple CNN models (with and without Tranfert Learning), Hyperparameter Optimization, and Fine Tuning
