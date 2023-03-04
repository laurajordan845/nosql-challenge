# nosql-challenge
Module 12 Challenge for Laura Jordan

## Description
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. In this exercise, I'm pretending that I've been contracted by the editors of a food magazine, *Eat Safe, Love*, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

This assignment consisted of 3 parts:
* Database and Jupyter Notebook Set Up
* Update the Database
* Exploratory Analysis

## Part 1: Database and Jupyter Notebook Set Up
In this portion of the challenge, I imported data from a json file, named the database and collection, imported the libraries needed, created an instance of Mongo Client, confirmed everything loaded properly and assigned the collection to a variable to use throughout the rest of the assignment. 

## Part 2: Update the Database
In this portion of the challenge, I made some modifications to the database so that I could do queiries and analyses for them. I added a new halal restaurant named Penang Flavours, found the Business Type ID for the Restaurant/Cafe/Canteen category, updated Penang Flavours' business listing with the Business Type ID, removed all establishments that were located in the Dover Local Authority and updated the longitude/latitude variables to be stored as numbers instead of strings.

## Part 3: Exploratory Analysis
In this portion of the challenge, I looked at 4 business questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a Rating Value greater than or equal to 4?
3. What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new restaurant Penang Flavours (searching within 0.01 degree on either side of the latitude and longitude)?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Support
I attended class, reviewed my notes, and utilized the AskBCS Learning Assistants for the support needed for this challenge assignment.

## Submission Includes
* NoSQL_setup - LauraJordan
* NoSQL_analysis - LauraJordan
* Resources folder with the establishments.json used for analysis
