# Zomato_Dataset_Analysis
Zomato Data Exploration and Analysis with SQL (SQL SERVER)

Zomato is a leading Indian multinational restaurant discovery and food delivery platform. This project analyzes the Zomato dataset to understand restaurant distribution, customer services, pricing, and ratings across different cities and countries. The objective is to explore how Zomato’s business operates using structured data analysis in SQL.

The dataset contains over 9,000+ restaurant records with fields such as Restaurant ID, Restaurant Name, City, Location, Cuisines, Ratings, Votes, Cost for Two, and Delivery Options.

## Data Preparation & Cleaning (SQL)

Before analysis, the dataset was cleaned and structured using SQL:

Inspected table structure, column names, data types, and constraints

Checked and removed duplicate values in the RestaurantID column

Removed irrelevant and unused columns

Merged two tables using CountryCode as the primary key to add Country_Name

Identified and corrected misspelled city names

Used window functions to calculate rolling and moving counts

Calculated minimum, maximum, and average values for votes, ratings, and currency

Created a rating category column to classify restaurants

## Data Analysis & Key Insights

90.67% of restaurants in the dataset are located in India, followed by the USA (4.45%)

Out of 15 countries, only India and UAE offer online delivery services

28.01% of Indian restaurants and 46.67% of UAE restaurants provide online delivery

Connaught Place (New Delhi) has the highest number of listed restaurants (122)

The most popular cuisine in Connaught Place is North Indian

Only 54 out of 122 restaurants in Connaught Place offer table booking

Restaurants with table booking have a higher average rating (3.9) than those without (3.7)

The best moderately priced Indian restaurant (cost < ₹1000, rating > 4, votes > 4, with online delivery and table booking) is
“India Restaurant” (Restaurant ID: 20747), Kolkata

## Tools & Technologies

SQL

Joins, Window Functions, Aggregations

Data Cleaning & Transformation

##  What This Project Demonstrates

Real-world SQL data cleaning

Multi-table joins and data integration

Business-focused data analysis

Insight generation from large datasets

##  Conclusion

This project demonstrates how SQL can be used to convert raw business data into meaningful insights. The analysis helps understand restaurant performance, customer services, and regional trends, supporting data-driven decision making.
