# Amazon-ML-Accelerator-NLP
Final Problem for passing 3 day Amazon ML accelerator NLP course

# Problem Statement

**Business Problem**
Amazon Retail receives billions of reviews on its products every year. Some of these reviews indicate a safety issue and a need to potentially suppress the product (ASIN). In these cases, review text is sent to annotation teams worldwide that decide whether there is a product safety issue or not. 

The team responsible for this annotation is looking at a potential Machine Learning solution to automate this process given the extensive dataset created.

**ML Problem**
This is a binary classification problem of using review text, review title, star rating and date information to predict if a product is a Product Safety Issue (1) or Not Product Safety Issue (0). We will be using F1 score as our evaluation metric.

**Dataset Description**
There are seven features in the dataset, five that are useful. 

- ID: Unique ID created by Leaderboard when splitting the dataset. Numeric
- doc_id: Amazon ID for the review instance. Numeric.
- Text: raw review text as it appeared on the Amazon site. Text.
- date: time stamp for the review. Text.
- star_rating: 0-5. Numeric.
- title: raw review title as it appeared on the Amazon site. Text.
- human_tag: Ground truth if Amazon's human annotators determined if the review was a Product Safety Issue or Not Product Safety Issue. Binary.

# Resources
- https://towardsdatascience.com/text-classification-with-state-of-the-art-nlp-library-flair-b541d7add21f
- https://github.com/zalandoresearch/flair/blob/master/resources/docs/TUTORIAL_6_CORPUS.md
- 
