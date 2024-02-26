# project-4
Project 4
# Overview
* In this project we use the healthcare database to determine how each of the factors relate to each other, such as age, pre-existing conditions, charge, costs, county, number of people per age group, count, and gender. We then use machine learning to train an algorithm to predict the total charge.
# Process
* After cleaning the dataset, we populate the database using pyspark.sql. This falicitates the identification of patient and hospital factors.
* We then create visualisations of how each factor affects the total charge. According to the scatter plot, there is a slight positive linear correlation between total charges and total costs. There is also another positive correlation between age group and total charges, with the difference being those under 17 years of age. This could be explained by the youth being prone to injury especially in the very early stages of infancy and childhood. From ages 18-49, females are the majority of the count, with pregnancy being a possible explanation. The other age groups feature more men, with, as mentioned previously, more injuries being a possible factor. The Top 3 pre-existing conditions by charge are Respiratorytory Distress Syndrome, Bacterial Infections, and leukemias, since any respiratory illness can be fatal and trigger an emergency visit to the hospital. Erie County had the most amount of charges for "Liveborn".
# Machine Learning
* We then see what model best predicts our total charge results.
