# Winning Space Race with Data Science (SpaceX) - Captonew Project IBM
I will be a Data Scientist working for a startup intending to compete with SpaceX, and in the process follow the Data Science methodology involving data collection, data wrangling, exploratory data analysis, data visualization, model development, model evaluation, and reporting your results to stakeholders.  

![](https://media1.giphy.com/media/3ohs4gSs3V0Q7qOtKU/giphy.gif)



## Executive Summary
I collected data from the public SpaceX API and the SpaceX Wikipedia page. Then, I added a
column called 'class' to classify successful landings. To analyze the data, I used SQL,
visualizations, folium maps, and dashboards. I selected the relevant columns as features for
further analysis.
*  Next, I converted all the categorical variables into binary using a technique called one hot
encoding. I standardized the data and used GridSearchCV to find the best parameters for the
machine learning models. Finally, I visualized the accuracy scores of all the models.
*  I created four machine learning models: Logistic Regression, Support Vector Machine, Decision
Tree Classifier, and K Nearest Neighbors. Surprisingly, all the models produced similar results,
with an accuracy rate of around 83.33%. However, it's important to note that all the models
tended to over-predict successful landings.
*  To improve the model's accuracy and make more accurate predictions, we need to gather more
data

## Introduction
### Background
*  Commercial travels to Space is being more affordable.
*  Space X has best pricing ($62 million vs. $165 million USD)
*  The reason space travel is so expensive is because the materials used are not reusable.
Space Y aims to compete with Space X by finding ways to make space travel more
affordable through reusing the stage 1.
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