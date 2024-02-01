#### Introduction
Welcome to the **Netflix Genre Classification**🍿!

After learning how broad NLP (Natural Language Processing) application is, what interests me the most is **text/document classification**. 
My self-learning journey on this path is to collaborate the techniques I have been learning in the healthcare and medical field. 
My ultimate goal is to **leverage AI to predict disease/cancer using medical reports**. 

Hence, I am currently learning classification with NLPK during the wait of job-searching to strengthen my muscles. By doing that, I chose to use the Netflix genre dataset because who doesn't love Netflix? 

#### Workflow
- Step 1: Since each movie/TV show has three genre, I picked the first genre from each and chose top 5 genres (Dramas, Comedies, Action and Adventure, Documentaries, Crime TV Shows)

- Step 2: I cleaned the description using NLTK (stopwords, punctuation, tokenize,...) and the output file is 👉 **Description after cleaning.csv**

- Step 3: Vectorized the data and trained the model. Tested out using original data and new Netflix shows' description from IMDB (In this case, I used one of my favorite comedies - Friends) and the output file is 👉 **Output.csv**

#### Result and Discussion
The scores from 6 models are not good. I was expecting the output of Friends would be Comedies. 
The solution is to clean the description better.

#### Dataset used click here 👉
[https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb](https://www.kaggle.com/datasets/shivamb/netflix-shows)https://www.kaggle.com/datasets/shivamb/netflix-shows
