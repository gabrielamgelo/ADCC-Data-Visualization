# ADCC-data-visualization

As a jiu-jitsu fighter and because it's my favorite sport and one of my biggest interests lately, the goal of this project is to explore, analyze, and visualize data from a dataset with historical data of the Abu Dhabi Combat Championship (ADCC), from which I’m really excited to gain some insights into the competition. The dataset is available [here](https://www.kaggle.com/datasets/bjagrelli/adcc-historical-dataset). 

The main insights: 

- The year with the most fights was 2022, with 109 fights.
- The top 5 fighters with the most wins are: Alexandre Ribeiro, Marcelo Garcia, Saulo Ribeiro, André Galvão, and Leonardo Vieira.
- The majority of wins were decided by points, with 50% of the total wins, followed closely by submissions, with 39%. With only 9% being decisions, only 9 occurrences of injury and 1 disqualification.
- The most used submission is the Rea-Naked-Choke, followed by the Armbar, Guillotine, Hell Hook and Triangle.
- The weight classes with the most fights are: Absolute, 66kg, and 77kg, all in the male category. As for the female category, the weight clases are distributed between +60kg and 60kg.
- Winning by points and submission have had a steady increase over the years.
- Fights won by decision have had a great increase of occurences since the 2010's, with a possibility of increasing even more, as the experience level of fighters improves every year and the sport grows even bigger gaining more visibility and practioners, more and more matches could be more equally leveled, resulting in them being finished by decision.
___

### *Here you'll see a simplified overview and explanation of what was done, the full project is available in the accompanying Jupyter Notebook*.

## Technologies Used:


    Language: Python
    Python Libraries:
    Pandas: Used for data cleaning, manipulation and analysis
    Matplotlib & Seaborn: Used for visualizations.
    Jupyter Notebook: Used or interactive data exploration.

The repository contains:

• adcc_historical_data.csv: The dataset used.

• notebook.ipynb: A jupyter notebook containing the full analysis.

# OVERVIEW:

## 1- Exploratory Data Analysis:

First, the dataset was loaded and its format and descriptive statistics were checked. 

The win_type column had inconsistent values, such as 'DESQUALIFICATION', so it needed to be changed to 'DISQUALIFICATION'.

Missing values were found on the 'submission' and 'avd_pen' columns, due to not all fights being finished with submissions or having penalities, therefore, the missing values did not need to be treated.

### Insights/Questions to Answer:

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

**1st Graph-** Number of Occurrences of Each Win Type

With this graph we can see that the most wins are by points, with 50% of the total wins, followed closely by submissions, with 39%. Also, we can see that the other ways of winning are really not that frequent, with only 9% being decisions, only 9 occurrences of injury and 1 disqualification.

![Number of Occurrences of Each Win Type](https://github.com/user-attachments/assets/b0829454-e4d1-4efa-aa2f-0d23e60764d4)

![Captura de tela 2025-01-15 185927](https://github.com/user-attachments/assets/c2eca6a0-965a-49ca-8e9d-126441157cac)

**2nd Graph-** Spread of Points by Winner and Loser

Here we can see that the overall spread of points and max values for winners are way bigger than for losers, which should be expected.

![Spread of Points by Winner and Loser](https://github.com/user-attachments/assets/005c3a40-4714-43cd-9d5d-1249b5ef4697)


![Captura de tela 2025-01-15 185956](https://github.com/user-attachments/assets/42fcab51-f390-476b-9e07-b3929d7cad39)

**3rd Graph-** Submissions Used

Looking at this graph, we can notice that the most used submission is the Rea-Naked-Choke, followed by the Armbar, Guillotine, Hell Hook and Triangle. The Rear-Naked-Choke being the most used submission is not that surprising for it can be very tricky to defend againt, as your opponent has total advantage over you when he takes your back. Armbar being the second most used makes total sense, because it's literally one of the first moves everyone is taught when starting in jiu-jitsu, and because the arms can be very difficult to protect some times, even for high-level fighters! The one type of submission that is a bit surprising to be on the 4th spot is the Hell Hook, as it's kind of a 'new' addition to the sport, gaining a lot of popularity over more recent years with John Donaher's Death Squad.

As for the least used, it makes sense for them to be in the spots they're in. The twister, which is the least used submission, is very hard to accomplish specially against well trained opponents, but however rare and difficult (and amazing) it is to pull off, it still can happen.

![Submissions Used](https://github.com/user-attachments/assets/b85047d9-b597-4d47-aaa7-7978473376b5)

**4th Graph-** Number of Matches of Each Weight Class by Gender

Here we can see the weight classes with the most fights, the top 3 being Absolute, 66kg, and 77kg, all in the male category. As for the female category, the weight clases are distributed between +60kg and 60kg.

![Number of Matches of Each Weight Class by Gender](https://github.com/user-attachments/assets/907611ca-b3ee-4917-aaea-2d4315b05f25)

**5th Graph-** Number of Matches by Sex

This graph makes it obvious that the huge majority of matches are between males.

![Number of Matches by Sex](https://github.com/user-attachments/assets/483cc849-0d8b-4147-9ca3-8ee2f8d1f666)

**6th Graph-** Win Types Through the Years 

Here we can notice that winning by points and submission have had a steady increase over the years. With an interesting insight being that fights won by decision have had a great increase of occurences since the 2010's, with a possibility of increasing even more, as the experience level of fighters improves every year and the sport grows even bigger gaining more visibility and practioners, more and more matches  could be more equally leveled, resulting in them being finished by decision.

![Win Types Through the Years](https://github.com/user-attachments/assets/806a6bca-e442-4220-95f0-c73b3fdaa243)
