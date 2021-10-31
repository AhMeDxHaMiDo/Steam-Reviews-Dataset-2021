# Homework 2 - Steam Reviews 2021

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstore.steampowered.com%2F%3Fl%3Ditalian&psig=AOvVaw0ClVTTIQnmDkAGjCFETx9G&ust=1635780703492000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCJj6xJD89PMCFQAAAAAdAAAAABAD)

The purpose of this project is to imagine that we have been hired as a data scientists from a top Game Development Company. Our team have to perform an analysis of the reviews received for around 300 different applications (games) in Steam during 2021 of around 21 million user.

The repository consists of the following files:

1. __Name_notebook__:
   > A Jupyter notebook which provides the solutions to all research questions:
   - [RQ1] After collecting information, the Data Scientists have to know what dataset they are dealing with, so let's start with an Exploratory Data Analysis (EDA). What can you say about our dataset? Please summarize its main characteristics with visual and tabular methods;
   - [RQ2] Let's explore the dataset by finding simple insights into the reviews;
   - [RQ3] Now it's important to understand the preferred time to do reviews;
   - [RQ4] As Steam is a worldwide platform, the reviews can be done in many languages. Let's extract some information about it;
   - [RQ5] The reviews' authors are users from the game that provide their opinion on it. Now you can check how often they make reviews;
   - [RQ6] It's time to get information from the updates that a user does to his reviews;
   - [RQ7] Of course, calculating probabilities is a job that any Data Scientist must know. Let's compute Some interesting figures;
   - [RQ8] Every decision you take in a data-based environment should be reinforced with charts, statistical tests and analysis methods to check if a hypothesis is correct or not.
  
   > and theoretical questions:
   - TQ1 and TQ2 about algorithm and computational cost;
   - TQ3 about the knapsack problem.


2. __cleaned_data_steam_reviews_2021.ipynb:__
  > A jupyter notebook which provides the cleaning part of the dataset, in thise notebook there is the process of creating the 3 dataset we use in the main notebook: the df_cleaned dataset which is the overall clean dataset; the df_author dataset which is the df_cleaned with only the author-related columns and the df_reviews dataset which is the df_cleaned with only the reviews-related columns
