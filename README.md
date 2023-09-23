# Exploratory_Data_Analysis
EDA on IMDB movies&amp;shows data

This dataset compiles information about TV shows and movies available on Netflix, gathered through Flexible, a third-party Netflix search engine. The purpose of this project was to employ data analysis and machine learning techniques to cluster Netflix's content into similar categories, mirroring the approach used by Netflix itself. By examining various aspects of each title such as genre, cast, and plot, and utilizing algorithms to discern patterns and similarities, we aimed to enhance content recommendations for users.

Netflix has devised an intricate system of 1,300 recommendation clusters based on users' viewing preferences, enriching the overall user experience. The target audience for Netflix primarily comprises tech-savvy individuals, including teenagers, college students, young professionals, and entrepreneurs, all connected through the digital realm. To optimize content recommendations, Netflix segments its consumer base based on demographics, behavioral intent, and psychographic attributes.

In terms of content acquisition, Netflix employs traditional licensing agreements wherein compensation is structured per film, determined by rate cards linked to a sliding scale based on each title's domestic or worldwide box office earnings. The integration of machine learning and algorithms aids Netflix in challenging viewers' preconceived notions and guiding them towards shows they may not have initially considered. This is achieved by delving into nuanced threads within the content rather than relying solely on broad genres to make predictions. This project represents a deep dive into Netflix's content categorization strategies, showcasing a solid understanding of data analysis and machine learning in a real-world context.


Generally, movie recommendation systems cluster the users in a finite number of similar groups based on their previous activities and profile. Then, at a fundamental level, people in the same cluster are made similar recommendations. Netflix developed a new machine learning algorithm based on reinforcement learning to create an optimal list of recommendations considering a finite time budget for the user. Here are 7 examples of clustering algorithms in action.
- Identifying Fake News. Fake news is not a new phenomenon, but it is one that is becoming prolific. 
- Spam filter.
- Marketing and Sales. 
- Classifying network traffic.
- Identifying fraudulent or criminal activity. 
- Document analysis. 
- Fantasy Football and Sports.



Problem Statement :

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

About the Data :

We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle

Dataset info:

Number of records: 7787

Number of features: 12

Features information:

The dataset contains features like:


show_id : Unique ID for every Movie / Tv Show

type : A Movie or TV Show

title : Title of the Movie / Tv Shows

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Generes

description: The Summary description

Project Work flow:

- Importing Libraries,
- Loading the dataset,
- Data Summary,
- Data Cleaning & Data Analysis,
- Feature selection,
- Implementing different clustering methods,
- Conclusion,
- Future Work.


Conclusion:

- Director and cast contains a large number of null values so we will drop these 2 columns .
- In this data-set there are two types of contents where 30.86% includes TV shows and the remaining 69.14%  carries Movies.
- We have reached a conclusion from our analysis from the content added over years that Netflix is focusing
movies and TV shows (From 2016 data we get to know that Movies is increased by 80% and TV shows is  increased by 73% compare)
- From the data-set insights we can conclude that the most number of TV Shows released in 2017 and for  Movies it is 2020
- On Netflix USA has the largest number of contents. And most of the countries preferred to produce movies  more than TV shows.
- Most of the movies are belonging to 3 categories
- TOP 3 content categories are International movies , dramas , comedies.
- 	In text analysis (NLP) I used stop words, removed punctuation's , stemming & TF-IDF vectorizer and other  functions of NLP.
- 	Applied different clustering models like K-means, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements.
- 	By applying different clustering algorithms to our data-set .we get the optimal number of  cluster is equal to 3
- 	From this clustering analysis we can create Netflix movies and tv shows recommendation systems & also we can use topic modelling.
