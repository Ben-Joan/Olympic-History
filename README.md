# Olympic-History
Exploratory Data Analysis on 120 years of olympic history data using SQL

During this project, some of the following SQL concepts were covered:
- Group BY aggregate function
- Windows function (Dense_rank, first_value)
- Common Table Expressions CTEs
- Table Joins

## Introduction
The modern Olympic games is a grand international sporting events featuring winter and summer sports competitions in which thousands of athletes and countries participate in variety of sports events. The event is held ever four years period and this exploratory analysis using SQL (structured Query Language),is to derive information about the Olympics games over the years.

The dataset contains information on the games from 1896 – 2016 and is comprised of two files: (a)athlete_events  (b)noc_regions.
Athlete_events being the major file used for the analysis is made up of 271,116 rows and 15 columns while the Noc_regions contains three columns of data.

<img src='https://github.com/Ben-Joan/Olympic-History/blob/main/Database%20diagram.png'/>

## Data Source & Tool
![SQLite](https://img.shields.io/badge/SQlite-1DA1F2?style=for-the-badge&logo=sqlite&logoColor=white)

Data Set :https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

## Questions Explored
1.How many olympics games have been held?

2.List down all Olympics games held so far.

3.How many teams participated in the olympics?

4.Mention the total no of nations who participated in each olympics game?

5.Which year saw the highest and lowest no of countries participating in olympics?

6.Which nation has participated in all of the olympic games?

7.Identify the sport which was played in all summer olympics.

8.Which Sports were just played only once in the olympics?

9.Fetch the total no of sports played in each olympic games.

10.Fetch details of the oldest athletes to win a gold medal.

11.Find the Ratio of male and female athletes participated in all olympic games.

12.Fetch the top 5 athletes who have won the most gold medals.

13.Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).

14.Fetch the top 5 most successful countries in olympics. Success is defined by no of medals won.

15.List down total gold, silver and broze medals won by each country.

16.List down total gold, silver and broze medals won by each country corresponding to each olympic games.

17.Identify which country won the most gold, most silver and most bronze medals in each olympic games.

18.Identify which country won the most gold, most silver, most bronze medals and the most medals in each olympic games.

19.Which countries have never won gold medal but have won silver/bronze medals?

20.In which Sport/event, Nigeria has won highest medals.

21.Break down all olympic games where Nigeria won medal for Football and how many medals in each olympic games.

22.Youngest and Oldest Nigerian athletes

23.Which Nigerian athletes has won Gold medal

24.Which athlete has won the most medal in Nigeria?

25.How many medals has Nigeria won

26.Break down the  medals according to the total number won in Nigeria

27.How many games did Nigeria take part in?

28.How many Nigerian athletes won a medal

## Some Insights
- A total of 51 games was played between 1896 – 2016 comprising of 1184 different teams.

- 1896 summer had the least participants of 12 countries while 2016 summer had the most of 207 countries.

- UK, Switzerland, Italy, and France took part in all 51 Olympic games.

- The oldest athlete to take part in the Olympics is John Quincy Adams Ward, 97 years old from Amsterdam.
 
- Michael Fred Phelps of USA have won the most medal of 28 in total.

- USA is the most successful country, 5637 medals won i.e defining success by the total medal won.

- Nigeria participated in 16 of the Olympic games and won the most medal in the football sport (50 medals). In total they have won 99 medals between 1896 – 2016.

- Out of the 565 Nigerian athletes, only 96 won medals.







