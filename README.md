# ATPRankRegression
DSCI Group Project


DSCI 100 Final Project:
Predicting the ATP Rankings
Introduction

The Assocation of Tennis Professionals is the governing body for international professional men's tennis tournaments. The ATP maintains a widely recognized ranking of professional tennis players based on their past results. For example, Serbian tennis superstar Novak Djokovic currently sits atop of the ATP rankings, while the highest ranking Canadian, Felix Auger-Aliassime, ranks 11th. For this project, we will be making use of an Assocation of Tennis Profesionals (ATP) dataset to predict players' ATP ranking. Generally speaking, the goal of this project is to develop a regression model which can predict the ATP rank of a player given past information about players and matches. Examples of predictor variables include age of the player, ATP rank points, height of the player, and so on and so forth.

The dataset we are using has been compiled from Jeff Slackmans Github page (https://github.com/JeffSackmann/tennis_atp). The dataset contains information regarding players, the match, and the tournament the match was played in. The dataset itself is limited from 2017-2019. However, the ATP ranking formula/system has not changed since then. Therefore, we can test the accuracy of our model by testing its predictive ability on the current rankings of players. For instance, we can attempt to use our model to predict Felix Auger-Aliassime's ranking in 2021.

We are asking a regression question, as we are attempting to discern if one or more variables can be used to predict a numerical variable of interest, in this case, where one would expect a player of a particular height, age, and rank points to be ranked by the ATP relative to their peers.
