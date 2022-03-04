# NLP Sentiment Analysis with Yelp Review Data Set

As one of the most popular local business information app in North America, Yelp is widely used for review and rating. User reviews can bring insight for business owners for service improvement, and help potential customers find their choice of dining, shopping and other local services.

Therefore, the objective of this project is to identify the polarity (positive or negative) of Yelp reviews, and extract keywords that contribute to the positive or negative reviews. The project would mainly focus on enhancing customers’ understanding of restaurants, educating new business owners on market knowledge, and improving existing merchants’ awareness about their performance.

## Tasks

- Identify the polarity (positive or negative) of Yelp reviews using machine learning techniques, specifically, NLP sentiment analysis with Keras.
- Extract keywords and key features from positive and negative reviews using word cloud and SVM regression.

## Data set
- ### Yelp reviews polarity dataset

The Yelp reviews dataset consists of reviews from Yelp Dataset Challenge 2015 data. The Yelp reviews polarity dataset is constructed by Xiang Zhang (xiang.zhang@nyu.edu) and retrieved from https://course.fast.ai/datasets. The Yelp reviews polarity dataset is constructed by considering stars 1 and 2 negative, and 3 and 4 positive. For each polarity 280,000 training samples and 19,000 testing samples are take randomly. In total there are 560,000 trainig samples and 38,000 testing samples. Negative polarity is class 1, and positive class 2.

- ### Yelp reviews sample dataset

The original Yelp reviews dataset is retrieved from Yelp directly: https://www.yelp.com/dataset/download. The json file "yelp_academic_dataset_review.json" is very large, containing 6,990,280 lines. So we read the top 50,000 rows as sample for this tentative analysis.

## Algorithms

- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Support Vector Machines (SVM)

## Result example

For a sample business with 503 reviews:

Keywords in positive reviews

![positive](https://user-images.githubusercontent.com/38342639/156823153-0765e740-1a08-4255-b922-0f8da993ebc7.png)

Keywords in negative reviews

![negative](https://user-images.githubusercontent.com/38342639/156823224-c426c293-c8ff-48ee-9141-8b45fb215d47.png)

Keywords contributing to positive & negative reviews

![bigram](https://user-images.githubusercontent.com/38342639/156823251-41e48443-352b-4b63-8139-47c162cdc52d.png)

