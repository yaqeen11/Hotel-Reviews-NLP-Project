# Hotel Reviews for Sentiment Analysis.
## Overview
*Reviews on websites:*

As simple it sounds; but it has a significant impact on how tourists choose their accommodation. It is vital for hotels to have reputation for quality and it would work as trustable verification for the hotel quality. A recent Barclays study showed there is potential of an extra £3.2 billion, by just paying more attention to online reviews. The dataset that was collected from Booking.com. 

*The goal is to:*

Build unsupervised (NLP) machine learning models that decide whether a text review is positive review or negative review. 

*Project target costumers:*

(Local business such as hotels, restaurants, coffee shops…)
*Benefit* hotels to determine the category of text review and cluster them automaticity to improve their services.

## Data
The data for this project will be read into a CSV file (dataset  [link](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe/discussion)). 
This dataset is a scraped data from booking.com contains 515,000 customer reviews (rows)  for 1493 hotels across Europe and it has 17 columns as will. However, 
this data set has been manipulated to contain only two columns: review text , and its category (positive review 1 or negative review 0 ).

## Algorithms
The classification algorithms that has been used in this project on both Counter Vectorization and TF-IDF:
- Logistic Regression
- Bernoulli NB
- Decision Tree

Best Algorithm was Logistic Regression TF-IDF with testing score 0.943 without overfitting.


Topic modeling algorithms that has been used in this project:
- LSA
- NMF
- CorEX

Best Algorithm that made sensible results is CorEX with 3 topics for posative reviews and 4 negative reviews topics.


## Tools
- Pandas library will be used to create data frames.
- NLTK toolkit to perform common NLP tasks.
- Sklearn library will be to implement the classification and clustering models.
- Matplotlib, Seaborn and Wordcloud to visualize and discuss the results of the analysis.
- Autocorrection for Spelling Correction.
- SVD for building recommendation system.


## Communication
The project process and result has presented. To see the presentation slides click [here](https://github.com/halaalanzi/Hotel-Reviews-NLP-Project/blob/main/Presentation/Presentation.pdf).
