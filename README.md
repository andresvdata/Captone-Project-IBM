# Winning Space Race with Data Science (SpaceX) - Captonew Project IBM
This is a captone project part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) on Coursera.  

#### -- Project Status: [Completed]

## Project Intro/Objective

*  Commercial travels to Space is being more affordable.
*  Space X has best pricing ($62 million vs. $165 million USD)
*  The reason space travel is so expensive is because the materials used are not reusable.
Space Y aims to compete with Space X by finding ways to make space travel more
affordable through reusing the stage 1.

![](https://media1.giphy.com/media/3ohs4gSs3V0Q7qOtKU/giphy.gif)


### Technologies
* Data Science
* Methodology
* Deep Learning
* Machine Learning
* Github
* Python Programming
* Big Data
* Jupyter notebooks
* Data Mining
* Rstudio
* SQL

## Project Description
As a Data Scientist, I will be employed by a startup with the goal of competing with SpaceX, and in the process, the Data Science methodology will be followed, which includes data collection, data wrangling, exploratory data analysis, data visualization, model development, model evaluation, and reporting of results to stakeholders.
### Problem
*  Space Y aims to develop the capability to predict whether or not the first stage of a
rocket can be successfully recovered.

## Methodology
![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Falcon9_rocket_family.svg/1200px-Falcon9_rocket_family.svg.png)
Executive Summary
* Data collection methodology:
    * Data was collected from two sources : SpaceX public API and Wikipedia.
* Perform data wrangling
    * Data wrangling by landing success.
* Perform exploratory data analysis (EDA) using visualization and SQL
* Perform interactive visual analytics using Folium and Plotly Dash
* Perform predictive analysis using classification models
    * The object of model was created, then the hyperparameters were evaluated and selected based on r2 score and result was compared to other ML models.

## Featured Notebooks/Analysis/Deliverables
There are the following steps to review the project:

* [Data collection](/Data%20Collection)
* [data Wrangling](/Data%20Wrangling)
* [EDA with SQL](/EDA%20with%20SQL)
* [EDA with Seaborn](/EDA%20with%20Seaborn)
* [EDA with Data Visualization](/EDA%20with%20Data%20Visualization)
* [Predictive Analysis](/Predictive%20analysis%20(Classification))
* [Iteractive Visual Analytics with Folium](/Interactive%20Visual%20Analytics%20with%20Folium%20lab)

## Contact
* Feel free to contact me for any questions!










# Winning Space Race with Data Science (SpaceX) - Captonew Project IBM


## Executive Summary
For this project, the data was collected from the public SpaceX API and the SpaceX Wikipedia page. Then, a column called 'class' was added to classify successful landings. To analyze the data, SQL, visualizations, folium maps, and dashboards were used. The relevant columns as features for further analysis were selected.

Next, the categorical variables were transformed into binary using a technique called one-hot encoding. The data was standardized, and GridSearchCV was used to find the best parameters for the machine learning models. Finally, the accuracy scores of all the models were visualized.

Four machine learning models were considered: Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors. Surprisingly, all the models produced similar results, with an accuracy rate of around 83.33%. However, it's important to note that all the models tended to over-predict successful landings.

## Introduction

### Problem
*  Space Y aims to develop the capability to predict whether or not the first stage of a
rocket can be successfully recovered.


