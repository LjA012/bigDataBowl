# bigDataBowl
Repository to show the journey and work for my submission on the Big Data Bowl Kaggle competition. 

## Table of Contents
* [Purpose](https://github.com/LjA012/bigDataBowl/blob/master/README.md#purpose)
* [Data](https://github.com/LjA012/bigDataBowl/blob/master/README.md#data)
* [Data Cleaning](https://github.com/LjA012/bigDataBowl/blob/master/README.md#data-cleaning)

## Purpose
For the capstone project in my Data Science Program, I decided to work on a Kaggle Competition.  https://www.kaggle.com/c/nfl-big-data-bowl-2020.  In short, the competition is sponsored by the NFL and the objective is to see how accurate one can predict the yards a running back will gain after getting the handoff - given 49 features in the dataset. 

## Data
The data consisted of every run play (where a handoff occured) for the 2017 and 2018 season. There were 509,762 rows and each row represented each players interaction on the play.  Each game had a specific 'GameId' and there were 512 games.  Another feature is called 'PlayId' and because there are 22 players on the field for each play, each 'GameId' was responsible for 22 rows, so there were 23,%%% plays. 
Data types included categorical and numerical - I will talk about splitting up the categorical data in the Data Cleaning part.

## Data Cleaning
I spent a large chunk of time getting to know the data and understanding all of the different values for each feature.  For example, the 'GameWeather' feature had so many differnt inputs because of spelling mistakes and no uniform method to input this data.  Inputs like 'Sunny and clear skies' and 'Sun' mean the same thing, but my model would not know that - so that is why the cleaning process was extensive, for all 49 features. 
