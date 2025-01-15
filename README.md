# ADCC-data-visualization

This project uses data from the Abu Dhabi Combat Championship (ADCC), sourced from a dataset available [here](https://www.kaggle.com/datasets/bjagrelli/adcc-historical-dataset). The goal of this project is to explore, analyze, and visualize the data provided.

The repository contains:

• adcc_historical_data.csv: The dataset used.

• notebook.ipynb: A jupyter notebook containing the analysis

# OVERVIEW:

## 1- Exploratory Data Analysis:

First, the dataset was loaded and its format and descriptive statistics were checked. 

The win_type column had inconsistent values, such as 'DESQUALIFICATION', so it needed to be changed to 'DISQUALIFICATION'.

Missing values were found on the 'submission' and 'avd_pen' columns, due to not all fights being finished with submissions or having penalities, therefore, the missing values did not need to be treated.

**1st Question-** How many fighters were cataloged in the dataset? 
**Answer:** 

614 fighters

**2nd Question-** Were there how many fights each year?
**Answer:** 
![Fights per Year](https://github.com/user-attachments/assets/50833578-f473-4df8-a90b-147fe5925b43)

**3rd Question-** Who were the top 10 fighters with the most wins?
**Answer:** 


**4th Question-** Who were the top 10 fighters with the most losses?
**Answer:** 


**5th Question-** What are the win types?
**Answer:** 'DECISION', 'SUBMISSION', 'POINTS', 'INJURY', 'DISQUALIFICATION'

**6th Question-** What is the number of matches by sex?
**Answer:**


**7th Question-** When the first female match took place and who were the fighters?
**Answer:**

Year: 2011,  Winner: Gabrielle Garcia,  Loser: Penny Thomas

## 2- Data Visualization:

**1st Graph-** Number of Occurrences of Each Win Type

