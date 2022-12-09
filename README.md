# Star Wars: A Sentiment Analysis (INST 737 Project) 

# Introduction 
Our project focuses on doing a sentiment analysis of user reviews between different Star Wars movies. The movies that this project focused on is Episode 1 to 9 and the user reviews are from Imdb.com. The goal of this project is to provide Disney a comparison of sentiment results between the George Lucas Star Wars films and the Dinsey owned Star Wars films, that way Disney can use this information for future Star Wars movies. This analysis was done using python and this repository contains all of the files related to this project. This includes a project document that explains the results/findings of our project, python notebooks used for the analyis, and .csv files that contain the datasets used. The following sections of this readme will explain the different parts of this repository and information on how to install the required python libraries. 

# Parts of this repository

## Python Notebooks

### Webscraping
This folder contains all of the python notebooks used for web scraping the user reviews for Star Wars movies from IMDb.com. Each notebook correponds to a Star Wars movie/epsiode. For example  **INST737_Star_wars_IMDB_StarWars1.ipynb** is the web scraping notebook for Star Wars Episode I The Phantom Menace. Each notebook will also have the URL to the IMDb page that was used for web scraping. 

### Topic modeling and sentiment analysis
This folder contains the python notebooks that were used for our topic modeling analysis and sentiment analysis. Both types of analysis were done in the same python notebook for each episode. For example ""Textblob_test_episode4"" would be the python notebook that was used for episode 4's topic modeling and sentiment analysis. 

## Project Document
The project document is our document that contains all of the information that relates to our project. This invovles the introduction of our project, background information, project summary, literature review, methodolgy, experiment results, project conclusion, and future work

## Datasets
This folder is divided into two sub-folders. The first sub-folder is called ""IMDb datasets" and this folder will contain all of the reviews that we webscraped for each episode from IMDB.com. In total this subfolder has 9 datasets, each dataset represents an episode. The next sub-folder is called "Sentiment analysis datasets", this subfolder contains the datasets that have the polarity and subjectivity of each review for each epsiode. Similar to the first folder, each dataset corresponds to an episode. For both subfolders, all datasets are in .csv format.

# How to run the code

## Webscraping
In order to run the webscraping python notebooks, the following files would have to be run:
* INST737_Star_wars_IMDB_StarWars1.ipynb 
* INST737_Star_wars_IMDB_StarWars2.ipynb 
* INST737_Star_wars_IMDB_StarWars3.ipynb 
* INST737_Star_wars_IMDB_StarWars4.ipynb 
* INST737_Star_wars_IMDB_StarWars5.ipynb 
* INST737_Star_wars_IMDB_StarWars6.ipynb 
* INST737_Star_wars_IMDB_StarWars7.ipynb 
* INST737_Star_wars_IMDB_StarWars8.ipynb 
* INST737_Star_wars_IMDB_StarWars9.ipynb 

## Topic modeling and Sentiment Analysis 

