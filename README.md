# Feature Engineering for Machine Learning
This repository contains my lecture notes from the course 'Feature Engineering for Machine Learning', provided by Dr. Soledad Galli and which can be accessed through the following
link: [Feature Engineering for Machine Learning - official homepage](https://www.trainindata.com/p/feature-engineering-for-machine-learning). Furthermore, the course contains an official repository on github which can be accessed through the following link: [Official Repository](https://github.com/solegalli/feature-engineering-for-machine-learning). 

## Brief Description
Feature Engineering is an extremely important task in data science and machine learning. It not only consists of the primary tasks of knowing how to deal with data cleaning and preparation with regard to missing data, different types of variables, different cardinalities, value imputation techniques, normalization, discretization, etc., but also how we can build intelligent variables from the data in order to improve the performance of our machine learning models. The course aims to cover a wide range of topics and they can be found in the notebooks in the [notebooks](notebook link) folder. My goal was not to produce anything new but to reproduce the notes present in the original repository in order to learn the concepts taught in the course.

## Table of Contents

1. [**Introduction: Variable Types**](https://github.com/joaolucasmiqueleto/courses/tree/main/feature-engineering-for-machine-learning/section-03-types-of-variables)
	1. [Numerical Variables: Discrete and continuous](https://github.com/joaolucasmiqueleto/courses/blob/main/feature-engineering-for-machine-learning/section-03-types-of-variables/01__numerical_variables.ipynb)
	2. [Categorical Variables: Nominal and Ordinal](https://github.com/joaolucasmiqueleto/courses/blob/main/feature-engineering-for-machine-learning/section-03-types-of-variables/02__categorical_variables.ipynb)
	3. [Datetime variables](https://github.com/joaolucasmiqueleto/courses/blob/main/feature-engineering-for-machine-learning/section-03-types-of-variables/03__date_time_variables.ipynb)
	4. [Mixed variables: strings and numbers](https://github.com/joaolucasmiqueleto/courses/blob/main/feature-engineering-for-machine-learning/section-03-types-of-variables/04__mixed_variables.ipynb)

2. **Variable Characteristics**
	1. Missing Data 
	2. Cardinality
	3. Category Frequency
	4. Distributions
	5. Outliers
	6. Magnitude

3. **Missing Data Imputation**
	1. Mean and Median Imputation
	2. Arbitrary value imputation
	3. End of Tail Imputation
	4. Frequent category imputation
	5. Adding string missing
	6. Random Sample Imputation
	7. Adding a missing indicator
	8. Imputation with Scikit-learn
	9. Imputation with Feature-engine

4. **Multivariate Imputation**
	1. MICE
	2. KNN imputation

5. **Categorical Variable Encoding**
	1. One hot encoding: simple and of frequent categories
	2. Ordinal encoding: arbitrary and ordered
	3. Target mean encoding
	4. Weight of evidence
	6. Rare Label encoding
	7. Encoding with Scikit-learn
	8. Encoding with Feature-engine
	9. Encoding with category encoders

6. **Variable Transformation**
	1. Log, power and reciprocal
	2. Box-Cox
	3. Yeo-Johnson
	4. Transformation with Scikit-learn
	5. Transformation with Feature-engine

7. **Discretisation**
	1. Arbitrary
	2. Equal-frequency discretisation
	3. Equal-width discretisation
	4. K-means discretisation
	5. Discretisation with trees
	6. Discretisation with Scikit-learn
	7. Discretisation with Feature-engine

8. **Outliers**
	1. Capping
	2. Trimming

9. **Datetime**
	1. Extracting day, month, week, etc
	2. Extracting hr, min, sec, etc
	3. Capturing elapsed time
	4. Working with timezones
	
10. **Mixed variables**
	1. Creating new variables from strings and numbers

11. **Feature creation**
	1. Sum, prod, count, mean, std, etc
	2. Div, sub
	3. Polynomial expansion
	4. Splines
	
12. **Feature Scaling**
	1. Standardisation
	2. MinMaxScaling
	3. MaxAbsoluteScaling
	4. RobustScaling

13. **Pipelines**
	1. Classification Pipeline
	2. Regression Pipeline
	3. Pipeline with cross-validation
