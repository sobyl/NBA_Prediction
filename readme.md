[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sobyl/NBA_Prediction/master?filepath=final.ipynb)

# Team members:
Yu Liu, Hui Du, Siyuan Ji

# Problems/Motivation
- [data resource](https://www.basketball-reference.com)
- We want do the predictive project based on the basketball statistical data from website.
We can use all players and team data to predict the winner between two team or MVP (most valueable player).

# What libraries/tools you will need. What you already know and what else you need to evaluate.
- sklearn, requests, pandas
- we already know how to use requests package to scrap data from the html, we need to learn how to normlize our data and train data to predict.

# Data Collection details.
- Player_name
- Home_team
- Guest_team
- Team_History_record
- Player_box_score_history
- Player_fg_before
- Player_pts_before
- Player_mp_before
- Player_eFG_before
- ...etc

# Any Literature review.
- [MVP prediction model](https://towardsdatascience.com/nba-mvp-predictor-c700e50e0917)

# Required work detail before build model(clean up, hypothesis, data bias analysis etc.).
- build data frame
- data clean up
- revelant factors filter

# What is the predictive task and model detail. Model evaluation and selection strategy.
- Predict MVP and a game's result.
- Measure a player’s quality of impact (good or bad).
- Measure a team’s quality of impact (good or bad).

# How a user is going to test the final model. is there any webpage/command line interface. It can be like using curl from command line and calling a function(lambda via API gateway) in the cloud(AWS).
- Users can predict data through commit line.

# Tentative time line of activities.
- data collection 04/22-04/28
- data cleanup 04/29-05/02
- transformation 05/03-05/09
- feature engineering 05/10-05/16
- statistical summary 05/17-05/28
- prediction 05/29-06/04
