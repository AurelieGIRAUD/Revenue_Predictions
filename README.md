# Data Analyst Nanodegree with OpenClassRooms

At OpenClassrooms, the learning process is project-driven because that’s the fastest way to become proficient and to get some hands-on experiences. 
The Data Analyst degree include 9 projects to get through all the fundamentals of the Data Analyst Role.

<b> Read more on this degree here: https://openclassrooms.com/en/dashboard/paths </b>
  
This repository get through the key learnings related to the Project no.7.

## Project 7 - Revenue Prediction: Create a model to predict the revenues of potential customers using ANOVA and Linear Regression.

🎯 Goal: Create a model to predict the future revenue of children based on their location, the revenue of their parents and the gini index; in order to target future customers.


  1) Data Collection

Collect, Summarize and Discuss the relevance of the Data Collected for the Modeling.
Here is what we need to perform the modeling:

- World Income Distribution: This database is mainly composed of studies carried out at the national level for a good number of countries, and contains the income distributions of the populations concerned.
- Gini Index from the World Bank: https://data.worldbank.org/indicator/SI.POV.GINI
- Number of inhabitants of each country present in the data.

2) Features Engineering

Using the income generational mobility coefficient and the percentiles for each country, calculate the conditional probabilities between the class of parents and class of child. In other words, the probability of a child to be in a certain class of incomes depending in the class of income of his parents.

4) Data Preprocessing

Using the conditional proabilities, recreate a dataset representative of the incomes distribution per country. 

5) ANOVA and Linear Regression Model
