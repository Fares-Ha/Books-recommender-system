# Books-recommender-system


In this code I built more than one type of recommender systems:

1- Popularity based

2- Content based (user-item) by Publishers values

3- Content based (user-item) by Authors values

4- Content based (user-item) using Count Vectorizer by Titles , Authors and Publishers values

5- Collaborative based(user-user) (what similar users like)

6- Hybrid based built on:

      a- Content based (user-item) using Count Vectorizer by Titles , Authors and Publishers values

      b- Collaborative based(user-user) (what similar users like)




## Data Set

The dataset is from kaggle, The Book-Crossing dataset comprises 3 files :

      1- Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers.
      Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL-values.
      
      2- Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset.
      Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher),
      obtained from Amazon Web Services. Note that in case of several authors, only the first is provided.
      URLs linking to cover images are also given, appearing in three different flavours (Image-URL-S, Image-URL-M, Image-URL-L),
      i.e., small, medium, large. These URLs point to the Amazon web site.
      
      3- Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit,
      expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

you can find it in the link below :

https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset
