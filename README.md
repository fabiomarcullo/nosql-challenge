# Background

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Data Source

- [Contacts Data Source](https://github.com/fabiomarcullo/Crowdfunding_ETL/tree/main/Resources/contacts.xlsx)

## Jupyter Notebook

- [ETL_Mini_Project_FLima_JArambulo](https://github.com/fabiomarcullo/Crowdfunding_ETL/tree/main/ETL_Mini_Project_FLima_JArambulo.ipynb)


## Exploratory Analysis

#1. Which establishments have a hygiene score equal to 20?
   
   There are 41 establishments with a hygiene score of 20 from the `uk_food` dataset.
   
#2. Which establishments in London have a RatingValue greater than or equal to 4?

    There are 34 establishments in London that have a RatingValue greater than or equal to 4 from the `uk_food` dataset.

#3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

   The top 5 establishments with a RatingValue of '5' sorted by lowest hygiene score nearest to "Penang Flavours" are: 
   
       "Volunteer" 
       "Plumstead Manor Nursery"
       "Atlantic Fish Bar"
       "Iceland"
       "Howe and Co Fish and Chips - Van 17". 
   
#4. How many establishments in each Local Authority area have a hygiene score of 0? 

   Sort the results from highest to lowest, and print out the top ten local authority areas.
   
   There are 55 rows in the DataFrame. 
   
   This is the preview of the first 10 rows:
   

![.](Image/result.png)