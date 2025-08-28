# ml-project-imdb-aau2023
Achilles Apostolou project for ML-AAU_CPH-2023

Machine learning for Media Experiences - 2023 Mini Project Report – Achilles
Apostolou 

The idea behind this mini-project is to manipulate the data from a
dataset using some of the algorithms from the course's curriculum. In this
specific case, the dataset used was taken from kaggle. The dataset provided
detailed information on various aspects of each movie, including budget, IMDb
rating, country of origin, and genre. Leveraging machine learning algorithms, I
aimed to uncover insights into the factors influencing a movie's success and
popularity. 
https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset/ 

Methods Used: 

1) Data Collection: a) Acquired a dataset from Kaggle containing information on the top 10,000 movies on IMDb. b) Extracted key features, including budget, IMDb rating, country of origin, and genre.
2) Data Preprocessing: a) Handled missing values, outliers, and any data inconsistencies. b) Applied encoding techniques for categorical variables. 
3) Exploratory Data Analysis (EDA):  a) Conducted an exploration of the dataset to understand the distribution and relationships among variables.  b) Created visualizations to illustrate trends and patterns. 
4) Machine Learning Algorithms:  a) Employed regression analysis to examine the relationship between a movie's budget and its IMDb rating.  b) Utilized classification algorithms to investigate the association between the country of origin and genre. Findings: 
5) Budget vs IMDb Rating: o Identified a negative correlation between a movie's budget and it's IMDb Rating:  a) Used different models to investigate which one would be the most accurate to handle this correlation, by predicting the IMDb rating given the Budget of the film, and calculated the accuracy score. 
6) Country of Origin vs Genre:  a) Used a Random Forest Classifier to try and discover patterns or trends in the relationship between the country of origin and genre, b) Plotted a confusion matrix, to see how accurate the predictions were to the actual genre of each film for a sample size of 1000. 

Findings:
All in all, the dataset used seemed to have an adequate amount of data, even
though the results would certainly be more conclusive had it been larger. The
hypothesis that there is any correlation or causation between the budget of a
film and its rating proved to be wrong, as all the ML models failed to
accurately predict new inputs, and the scatterplot after the data analysis
seemed to be random. The correlation between the genre of a film and its country
of origin seemed to be a bit higher, even though still not high enough to not
account for the size of the dataset.
