# nosql-challenge
![image](https://github.com/AnaTipps/nosql-challenge/assets/131827518/6847a31d-368d-47b2-b2cb-193b824e5e11)


# Eat Safe, Love
## Background 

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. In this project I've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Database and Jupyter Notebook Set Up

The data provided was imported  in the `establishments.json` file from the Terminal. The name of the  database is `uk_food` and the collection `establishments`.

Within this markdown cell below , a copy of text  used to import the data from the Terminal. This way, future analysts will be able to repeat the process.

Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

## Updated Database

A new halal restaurant opened in Greenwich was added to the Database.

All establishments that has Dover as their Local Authority were dropped  from the database.

The data type of latitude, longitude and RatingValue was changed.

## Exploratory Analysis

The following questions to explore the database

1. Which establishments have a hygiene score equal to 20?
   
     
2. Which establishments in London have a RatingValue greater than or equal to 4?

    
3. What are the top 5 establishments with a RatingValue rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

     
4. How many establishments in each Local Authority area have a hygiene score of 0?
