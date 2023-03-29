![Ciencias_Logo_Azul-01](https://user-images.githubusercontent.com/106987072/228209396-a8737601-f28f-486e-8566-918709663369.png)


# Machine Learning
This repository encompasses the projects developed for the Machine Learning course, which aimed to familiarize students with different Machine Learning models and data processing techniques.


#### Team:
- Alexandre Sobreira
- André Dias
- Tiago Rodrigues

#### Professors: 
- André Falcão
- Andreia Teixeira
- Nuno Garcia


## First Home Assignment - Decision Trees and Linear Regression
This home assignment focused on the utilization of basic machine learning models for classification and regression tasks and their full evaluation through the use of a test set and an independent validation set.

### Models used:
**Regression:** Linear Regression, Regularized Linear models (Ridge and Lasso regularization) and Decision Tree Regressors

**Classification:** Logistic Regression and Decision Tree Classifiers

### Data:
The data corresponds to the [Parkinsons Telemonitoring Data Set](https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring), which is composed of a range of biomedical voice measurements from 42 people with early-stage Parkinson's disease recruited to a six-month trial of a telemonitoring device for remote symptom progression monitoring. 

### Project Objectives:
- Producing the best regression model for 'motor UPDRS'
- Producing the best binary classification model assuming as positive all instances with values of total_UPRDS> 40 and as negatives all remaining cases


## Second Home Assignment - Data pre-processing and more complex classification models
This home assignment focused on pre-processing of the given data, through imputation and feature selection, the utilization of varied classification models (including ensemble models) and the optimization of their parameters.

### Models used for classification:
- Decision Trees
- Logistic Regression
- Naïve Bayes
- K-Nearest Neighbors
- Support Vector Machines
- Bagging
- Random Forests
- AdaBoost
- Gradient Boost
- Extreme Gradient Boost


### Data:
The data was provided by the Professors and was adaptaded from the [QSAR biodegradation Data Set](https://archive.ics.uci.edu/ml/datasets/QSAR+biodegradation), which focuses on the study of the relationships between chemical structure and biodegradation of molecules.

### Project Objectives:
- Data pre-processing (normalization, imputation, initial feature selection)
- In depth feature selection using correlation metrics and machine learning models (Decision Trees, Stepwise methods, Random Forests)
- Producing the best Classification model (parameter optimization included)


## Final Project - Time series prediction
This project focused on data pre-processing of a given dataset and the development of accurate prediction models.

### Models used for regression:
- Linear Regression
- Random Forests
- Extreme Gradient Boost


### Data:
The data corresponds to the "World Bank Data" from [Kaggle](https://www.kaggle.com/datasets/gemartin/world-bank-data-1960-to-2016?resource=download), which contains 3 datasets related to country population, fertility rate and life expectancy from 1960 up to 2016 for several countries.

### Project Objectives:
- Data pre-processing (feature encoding, creating a time series)
- Add additional information to make better models
- Make predictions for 2017 and 2018 and compare to the real results obtained from the [World Bank Data](https://www.worldbank.org/en/home)
