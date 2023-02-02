# Bank Loan data analysis

In this project we are going to analyze the bank loan data set. 

## Overview
The main aim of this project is to analyze customers based on current loan, type of loan taken, credit scores, average monthly debts, bancruptcies which helps banks decide whether they can sanction the loan or not and analyze trends.

## Prerequisites
1. Created S3 bucket to store the dataset.
2. Created an EMR cluster and login to master node.
2. Loaded the data from S3 bucket to Hive table by creating an external table.
3. Loaded data available in Hive to Pyspark.
4. Stored the queries to MongoDB.

Directions or anything needed before running the project.

- AWS Account

## How to Run This Project

1. Create an EMR cluster on AWS. Select Spark while creation of the cluster
2. Pyspark installation - pip install pyspark
3. MongoDB installation - sudo yum install -y mongodb-org 
4. Install pymongo package - pip install pymongo

## Queries to analyze

1. Create a dataframe with the Customer IDs having top 5 current loan amounts  and save the result in MongoDB?

2. Create a dataframe with the Customer IDs having the lowest 5 current loan amounts  and save the result in MongoDB?

3. Create a dataframe of Customer IDs who have taken the Short Term Loan and include their total Current Loan Amount and save the result in MongoDB? 

4. Create a dataframe of Customer IDs who have taken the Long Term Loan and include their total Current Loan Amount and save the result in MongoDB? 

5. Count how many Bankruptcies are present?

6. Group the data based on Term and find the average monthly debt.

7. Create a dataframe of the customers who have 10 + years experience in their current job. Include their Annual Income.

8. Group the data based on Home ownership and Term. Find the aggregated sum of the total current loan.

9. Find the highest credit score for short term and long term customers.

10. Group the data based on years in current job and Home ownership and find the aggregated sum of credit score.

## Contact

Please feel free to contact me if you have any questions at: https://www.linkedin.com/in/narrasravani/
