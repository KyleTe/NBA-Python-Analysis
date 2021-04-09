# NBA-Python-Analysis

## Introduction

The goal of this project is to process the NBA dataset, clean, interpret, analyze, visualize the data, making prediction and regression analysis. Dataset includes the NBA data of each game from 2004 to 03/01/2020, all statistics of players for a given game and detail such as player performance, played time and seasonal team record.

NBA is usually considered to be the most renowned men's professional basketball league in the world, average regular season viewers reached 2 million and more than 20 million viewers for final games. Exploring NBA dataset could help us find hidden insights and matchup predictions for the team, or identify under-valued players and underdog teams. For instance, in 2017, some NBA teams used data analysis to discover that by scoring more three-point shots will lead to a higher winning probability, such insights made average three-point shots rate increased by more than 40% in 2017. Using such analysis and prediction could systematically help a team to find out the most efficient way of scoring, providing more winning chances for a team, that’s the reason why data analytics is important for NBA.

Since NBA has suspended all games including playoffs due to the pandemic, we will now use all available data of 19-20 regular season to predict our target of interest. Our goals including making analysis or predictions. First, we will analyze the performance of players and teams. In terms of performance, we will calculate each player’s efficiency, which is the most common benchmark teams used for rating player performance. More detail of EFF and its formula could be explored here: https://en.wikipedia.org/wiki/Efficiency_(basketball)

After creating EFF, we could compare the performance and salary to find out who earned millions but wasn’t contributing to the team, identifying the overpaid underperformers, players who perform weakly or have injury issue. We can also Predict MVP of the year, the most valued player usually will be the best player in the final winning team, and will be voted and chosen by media. To achieve predicting MVP, we could use current data to find which potential team is most likely to be in the final match and which statistics of performance is the best. We will also predict Rookie of the year, a best first-season player will be selected by sports reporters. We can first identify all first-season player in 19-20 season then compare their performance statistics. Also, the most importantly, predict which team will win the annual NBA championship. We will use performance of regular season to predict which team is the top eight seed in each conference to make the playoffs. Then predict each match up in playoffs to the final.

Since the 19-20 season only completed about 90% of regular season, we do not have any 19-20 playoffs data. Therefore, in terms of training model to predict our question of interest, we will only use regular season data. For example, we will use 2010-2018 regular season team performance as x, the independent variable, and teams who enter playoffs will be y, target variable. When training model to predict other results such as champion and MVP, will only use regular season data as well.

Choice for Data Processing or Data Analysis:
Since our dataset is relatively clearner than other dataset, for exmaple, only date format and minor parts need to be cleaned. Therefore, we will choose Data Analysis on our project.

## Dataset overview 
The dataset was collected from https://www.kaggle.com/nathanlauga/nba-games

The dataset contains 5 data:

games: all match details from 2004 to 2020
games_details: details of games, all statistics of players for a given game
players: players details
ranking: ranking of NBA given a day
teams: all NBA teams detail such as city, coach, owner
