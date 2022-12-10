# Star Wars: A Sentiment Analysis (INST 737 Project) 
#### Authors: Matthew Chan and Ujwal Gupta

# Introduction 
Our project focuses on performing a sentiment analysis and finding the reasons for those sentiment on Star Wars I to IX user reviews from IMDb. The goal of this project is to provide a potential client, Disney, with a comparison of sentiment results between the George Lucas Star Wars movies (Star Wars I to VI) and the Dinsey owned Star Wars movies (Star Wars VII to IX). We hope that Disney can use this information and recommendations when making future Star Wars movies. This analysis was done using Python and its libraries. Our repository contains all of the files related to this project. This includes a project document that explains the results of our project, a detailed ReadMe file on layout of this repository, Python notebooks used for the analyis, and .csv folders containing datasets used. Below is our ReadMe file explaining how to run the notebooks and required Python libraries that are needed to be installed. 

# Parts of Repository

## Python Notebooks Descriptions

### Web Scraping
This folder contains all of the Python notebooks used for web scraping the user reviews for Star Wars movies from IMDb. Each notebook corresponds to a Star Wars movie. For example  **INST737_Star_wars_IMDB_StarWars1.ipynb** is the web scraping notebook for _Star Wars Episode I: The Phantom Menace_. Each notebook contains the URL to the IMDb page that was used for web scraping. The subfolder here contains the .csv files from the web scrape of each movie. Each .csv file contains the columns review index, review date, author, rating, review title, review, and review url. 

### Topic Modeling 
This folder contains the Python notebooks that was used for our topic modeling analysis. Each notebook corresponds to a Star Wars movie. The topic modeling result aided in understanding the common topics of words used in each movie.

### Sentiment Analysis
This folder contains the Python notebooks that was used for our sentiment analysis. Each notebook corresponds to a Star Wars movie. The subfolder her contains the .csv files of the sentiment analysis of each of the movies with polarity and subjectivity scores (9 files), as well as .csv files of sampled 5% positive reviews and sampled 5% negative reviews of each movie (18 files). 27 files in total. 

## Project Document
The project document is our document that contains all of the related information on our project. This includes the sections: Introduction; Background; Summary and Contributions; Literature Review; Methodolgy: Data Collection and Data Cleaning; Experiment Result: Experiment Setup, Results, Findings; Limitations; Conclusion; Future Work; and References.

# How to run the code

## Web Scraping
In order to run the web scraping Python notebooks, the following files would have to be run:
* INST737_Star_wars_IMDB_StarWars1.ipynb 
* INST737_Star_wars_IMDB_StarWars2.ipynb 
* INST737_Star_wars_IMDB_StarWars3.ipynb 
* INST737_Star_wars_IMDB_StarWars4.ipynb 
* INST737_Star_wars_IMDB_StarWars5.ipynb 
* INST737_Star_wars_IMDB_StarWars6.ipynb 
* INST737_Star_wars_IMDB_StarWars7.ipynb 
* INST737_Star_wars_IMDB_StarWars8.ipynb 
* INST737_Star_wars_IMDB_StarWars9.ipynb 

In order for these notebooks to run successfully, the following Python libraries have to be installed:
* numpy
* pandas
* scrapy 
* selenium
* time 
* tqdm 
* random

## Topic Modeling
The topic modeling analysis was done for each episode. Run these programs in order the following files would have to be run:

* Topic_Modeling_Episode1.ipynb
* Topic_Modeling_Episode2.ipynb
* Topic_Modeling_Episode3.ipynb
* Topic_Modeling_Episode4.ipynb
* Topic_Modeling_Episode5.ipynb
* Topic_Modeling_Episode6.ipynb
* Topic_Modeling_Episode7.ipynb
* Topic_Modeling_Episode8.ipynb
* Topic_Modeling_Episode9.ipynb

In order to run the topic modeling notebooks, the following python libraries would have to be installed:

* pandas 
* regex
* numpy
* gensim
* gensim.corpora 
* from gensim.utils import simple_preprocess
* spaCy
* pyLDAvis
* ntlk
* nltk.download('stopwords')
* stopwords (from nltk.corpus import stopwords)
* pyLDAvis.gensim_models

## Sentiment Analysis
The sentiment analysis was done for each episode. Run these programs in order the following files would have to be run:

* Star_Wars_Episode1_Sentiment_Analysis.ipynb
* Star_Wars_Episode2_Sentiment_Analysis.ipynb
* Star_Wars_Episode3_Sentiment_Analysis.ipynb
* Star_Wars_Episode4_Sentiment_Analysis.ipynb
* Star_Wars_Episode5_Sentiment_Analysis.ipynb
* Star_Wars_Episode6_Sentiment_Analysis.ipynb
* Star_Wars_Episode7_Sentiment_Analysis.ipynb
* Star_Wars_Episode8_Sentiment_Analysis.ipynb
* Star_Wars_Episode9_Sentiment_Analysis.ipynb

In order to run the sentiment analysis notebooks, the following python libraries would have to be installed:

* pandas 
* Textblob

