# Spark-Data-Analysis
1. Read goalscorers.csv and results.csv into spark, and display some metadata of the given datasets. 
a. Display first 20 lines using show().
b. Try to show some other properties of the given datasets.
2. Based on the goal data goalscorers.csv, calculate and visualize the distribution of goals according to the happening time. 
a. Conclude how many goals happened in each minute. For example, 403 goals
in 1st minute, 501 goals in 2nd minute, and so on.
b. Draw a histogram to visualize the distribution of goals in each minute.
3. Based on the goal data goalscorers.csv, calculate the number of goals of each player. Output the top 10 players’ names as well as their goal numbers. 
a. Omit own goals, which cannot be taken into consideration when counting the number of goals for a specific player.
b. Rank players according to the goal numbers.
4. Based on the goal data goalscorers.csv, find the top 10 players who have scored the most goals
from penalty, and output players’ names as well as their number of penalty scores. 
a. Rank players according to the number of penalty scores.
5. Based on the match result data result.csv, calculate the winning rates of all national teams and output the ten teams with the highest winning rates. 
a. For the same country, the results of both home_team and away_team need to be considered.
b. The dataset only gives the scores of each match, determine the match results according to the values in columns home_score and away_score.
There are three possible match results:
home_score > away_score: home_team win, away_team lose
home_score = away_score: home_team draw, away_team draw home_score < away_score: home_team lose, away_team win
c. Calculate win rate.
d. Rank countries according to the winning rate.