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

2022    109
2019    104
2017    102
2015     93
2013     87
2011     89
2009     72
2007     59
2005     66
2003     66
2001     64
2000     51
1999     45
1998     21

**3rd Question-** Who were the top 10 fighters with the most wins?
**Answer:** 

Alexandre Ribeiro     30
Marcelo Garcia        27
Saulo Ribeiro         22
Andre Galvao          22
Leonardo Vieira       21
Fabricio Werdum       20
Gordon Ryan           20
Roberto Abreu         20
Vinicius Magalhaes    19
Pablo Popovitch       19

**4th Question-** Who were the top 10 fighters with the most losses?
**Answer:** 

Alexandre Ribeiro     13
Rafael Lovato Jr      12
Baret Yoshida         11
Vinicius Magalhaes    10
Gary Tonon            10
Leonardo Vieira        9
Ricco Rodriguez        9
Roberto Abreu          9
Dean Lister            9
A. Cacareco            8

**5th Question-** What are the win types?
**Answer:** 'DECISION', 'SUBMISSION', 'POINTS', 'INJURY', 'DISQUALIFICATION'

**6th Question-** What is the number of matches by sex?
**Answer:**

M 	986
F 	42

**7th Question-** When the first female match took place and who were the fighters?
**Answer:**

Year: 2011  Winner: Gabrielle Garcia  Loser: Penny Thomas

## 2- Data Visualization:

**1st Graph-** Number of Occurrences of Each Win Type
