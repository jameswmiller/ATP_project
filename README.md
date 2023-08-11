# Data Science Project: Analyse Associaton of Tennis Professional (ATP) Player Data
The aim of this project is to analyse ATP match and ranking data found in [Jeff Sackmann's Git Repository](https://github.com/JeffSackmann/tennis_atp).
The project is split into 3 parts, each written in Python via a Jupyter Notebook.

The full dataset used in this project contains match and ranking data from 1st January 1991 (when the ATP Tour began regularly tracking match statistics) through to 7th August 2023,
just prior to the start of the 2023 Canadian Masters.

## Part 1: ATP_data_conversions.ipynb
The goal of ATP_data_conversions is to convert raw ATP match and ranking data found in matches_rankings into aggregated player statistics.
The notebook contains numerous functions enabling you to specify a minimum number of matches played or won, as well as letting you apply filters to include or ignore
different match lengths (Best of 5, Best of 3) or team competitions such as Davis Cup.

The final output of ATP_data_conversions are two CSVs:
1) players_by_year.csv - seasonal aggregated player statistics i.e. 1 row per player per year they played on the ATP Tour
2) players.csv - aggregated player statistics over entire data set range i.e. 1 row per player that has played on the ATP tour

players_dictionary.txt, describes the columns found in both players CSVs and can be found along with them in the players_CSVs folder.

## Part 2: ATP_eda.ipynb
The goal of ATP_eda is to begin exploratory data analysis on the aggregated statistics produced by ATP_data_conversions. The notebook aims to explore 4 questions regarding the ATP Tour:

1) Are ATP matches getting longer?
2) Are ATP Players getting taller?
3) Are left-handed players at an advantage over right-handed players when serving?
4) Can you predict a players match win percentage using basic serve and return statistics?

To help answer these questions I use a range of methods including basic EDA, hypothesis testing, and multiple linear regression

## Part 3: ATP_models.ipynb
The goal of ATP_models is to expand on the analysis in the previous notebook and create a more powerful supervised machine learning model, namely a Random Forest Classifier and Regressor, 
which will use serve and return stats to predict year-end rankings of players in the data set. I then test the model(s) performance on 2022 player data, and compare predicions made 
by the model(s) to real values.

Throughout I aim to use my insight as a long term tennis player, coach, and avid fan of the professional game to help explain the results, successes and any shortcomings I encountered
when completing the project.

While I hope this project illustrates my ability as a budding data scientist/ analyst to future employers, the main goal of the project was to combine my two biggest passions in life - tennis and science.
I hope to add to and improve the project as I build upon my skills as I enter the field and gain more experience, and suggestions are most welcome.



