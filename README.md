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

![Top 10 Winners](https://github.com/user-attachments/assets/6a18f665-78aa-4ccd-8bd2-3ccf0a93e7e8)

**4th Question-** Who were the top 10 fighters with the most losses?
**Answer:** 

![Top 10 Losers](https://github.com/user-attachments/assets/30e6bec4-97f7-4310-a4ee-5a512be661c4)

**5th Question-** What are the win types?
**Answer:** 'DECISION', 'SUBMISSION', 'POINTS', 'INJURY', 'DISQUALIFICATION'

**6th Question-** What is the number of matches by sex?
**Answer:**

![Matches by Sex](https://github.com/user-attachments/assets/8bf0bc8a-410b-4d3d-aa50-26da28874da6)

**7th Question-** When the first female match took place and who were the fighters?
**Answer:**

Year: 2011,  Winner: Gabrielle Garcia,  Loser: Penny Thomas

## 2- Data Visualization:

**1st Graph-** Number of Occurrences of Each Win Type

