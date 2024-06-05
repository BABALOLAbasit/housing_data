# Data Cleaning and Transformation in SQL

## Housing data cleaning project

## Table of Content
- [Introduction](#introduction)
- [Objectives](#objectives)
- [Key Queries and Processes](#key-queries-and-processes)
- [Conclusion](#conclusion)
- [Repository Contents](#repository-contents)

### Introduction

This project focuses on the process of cleaning and transforming a dataset using SQL. The dataset used in this project is from Nashville Housing and involves various tasks such as standardizing date formats, populating missing address data, splitting combined address fields into individual components, handling data inconsistencies, and removing duplicate records. The ultimate goal is to ensure the dataset is clean, accurate, and ready for analysis, which is crucial for making informed business decisions.

### Objectives

. Standardize Date Formats: Ensure all date values are in a consistent format.

. Populate Missing Data: Use existing data to fill in missing property addresses.

. Split Address Fields: Break down combined address fields into individual columns for better usability.

. Handle Data Inconsistencies: Standardize values in categorical fields, such as converting 'Y'/'N' to 'Yes'/'No'.

. Remove Duplicate Records: Identify and delete duplicate records to maintain data integrity.

. Drop Unused Columns: Clean up the schema by removing columns that are no longer needed.

### Key Queries and Processes

**1. Standardize Date Format:** Convert and store dates in a consistent format for accurate querying and reporting.

**2. Populate Property Address Data:** Use self-joins to fill in missing address information, ensuring no critical data is missing.

**3. Break Out Address into Individual Columns:** Split combined address fields into separate columns for street address, city, and state to improve data structure.

**4. Handle Owner Address Data:** Similarly, split owner address fields into individual components for better data management.

**5. Standardize 'Sold as Vacant' Field:** Convert 'Y'/'N' values to 'Yes'/'No' for better readability and consistency.

**6. Remove Duplicate Records:** Use CTEs (Common Table Expressions) and window functions to identify and remove duplicate entries.

**7. Delete Unused Columns:** Drop columns that are no longer necessary after the data cleaning and transformation process.

### Conclusion

By completing these data cleaning and transformation tasks, the dataset is now well-structured, consistent, and ready for deeper analysis. This process highlights the importance of data cleaning in any data-driven project, ensuring that subsequent analyses are based on accurate and reliable data. This project serves as a comprehensive example of how SQL can be used effectively to prepare data for business intelligence and analytics purposes.

### Repository Contents

SQL Scripts: Contain all the queries used for the data cleaning and transformation tasks.
Documentation: Detailed explanation of each step and its importance.
Sample Data: A subset of the dataset to demonstrate the transformations.
By following this project, you will gain a solid understanding of essential data cleaning techniques in SQL, which are critical for any data analysis and business intelligence tasks.
