# Building Recommender Systems with Machine Learning and AI
Exploring Recommender Systems using various Machine Learning Models & Deep Learning.

### Models and Packages:
```
- Scikit-learn
- Surprise: A Python scikit for building and analyzing recommender systems.
- Content-based filtering - NLP recommendation engine
- Collaborative Filtering Model
- Matrix factorization methods
- Deep Learning & CNN
- TensorFlow & Keras
- Scaling with Apache Spark, Amazon DSSTNE, and AWS SageMaker
```
## 1. Movie Recommender

### Data

MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota.

This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. 

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

## 2. Book Recommender 

### Data

The data is from the Book-Crossing community and contains 278,858 users (anonymized but with demographic information) providing 1,149,780 ratings (explicit / implicit) about 271,379 books.

The Book-Crossing dataset comprises 3 tables.
- BX-Users
Contains the users. Note that user IDs (`User-ID`) have been anonymized and map to integers. Demographic data is provided (`Location`, `Age`) if available. Otherwise, these fields contain NULL-values.

- BX-Books
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (`Book-Title`, `Book-Author`, `Year-Of-Publication`, `Publisher`), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (`Image-URL-S`, `Image-URL-M`, `Image-URL-L`), i.e., small, medium, large. These URLs point to the Amazon web site.

- BX-Book-Ratings
Contains the book rating information. Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.
