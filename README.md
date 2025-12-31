# Data Wrangling Hands on Practice Lab

## Overview
This project focuses on practical data wrangling techniques using Python and pandas.  
The lab addresses common data quality issues including missing values, incorrect data types, data standardization, normalization, and feature engineering.

The objective is to prepare a raw dataset for analysis by transforming it into a clean, structured, and machine ready format.

## Lab Objectives
- Identify and handle missing data
- Correct incorrect data types
- Standardize numerical features
- Normalize selected attributes
- Perform feature engineering
- Prepare the dataset for downstream analysis

## Dataset Description
The dataset contains laptop specifications and pricing information.  
Each row represents a laptop model with technical and pricing attributes.

Key attributes include:
- Manufacturer
- Category
- GPU
- Operating system
- CPU core count
- Screen size
- CPU frequency
- RAM size
- SSD storage
- Weight
- Price

The final dataset contains 238 rows and 15 columns.

## Data Wrangling Tasks Performed

### Handling Missing Data
- Identified missing values across multiple columns
- Replaced or removed missing entries based on context
- Ensured dataset completeness for analysis

### Data Type Correction
- Converted numeric fields stored as objects into proper numeric types
- Ensured consistency across all quantitative columns

### Standardization
- Standardized features such as CPU frequency
- Scaled values to a comparable range to support analysis

### Normalization
- Applied normalization to selected numeric attributes
- Improved comparability between features with different units

### Feature Engineering
- Created a binned price category feature
- Converted categorical screen attributes into dummy variables
- Expanded the dataset with machine learning friendly features

## Final Dataset Structure
The cleaned dataset includes:
- Original attributes
- Standardized and normalized numerical features
- Price bins for categorical analysis
- Dummy variables for screen type

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## How to Run
1. Open the notebook in Jupyter
2. Run cells sequentially
3. Inspect intermediate outputs to observe data transformations
4. Review the final cleaned DataFrame

## Results
The final output is a clean, structured DataFrame ready for:
- Exploratory data analysis
- Visualization
- Machine learning modeling

## Skills Demonstrated
- Data wrangling
- Handling missing data
- Data type correction
- Feature scaling
- Feature engineering
- Pandas DataFrame manipulation
- Jupyter Notebook workflows

## Certification
This lab was completed as part of an IBM Data Science learning module.

Copyright © 2023 IBM Corporation
