# NLP Sentiment Analysis with Yelp Review Data Set

As one of the most popular local business information app in North America, Yelp is widely used for review and rating. User reviews can bring insight for business owners for service improvement, and help potential customers find their choice of dining, shopping and other local services.

Therefore, the objective of this project is to identify the polarity (positive or negative) of Yelp reviews using machine learning techniques, specifically, NLP sentiment analysis with Keras. The project would mainly focus on enhancing customers’ understanding of restaurants, educating new business owners on market knowledge, and improving existing merchants’ awareness about their performance.

## Tasks

- Identify the polarity (positive or negative) of Yelp reviews using machine learning techniques, specifically, NLP sentiment analysis with Keras.
- Extract keywords and key features from positive and negative reviews using word cloud and SVM regression.

## Data set
- ### Yelp reviews polarity dataset

The Yelp reviews dataset consists of reviews from Yelp Dataset Challenge 2015 data. The Yelp reviews polarity dataset is constructed by Xiang Zhang (xiang.zhang@nyu.edu) and retrieved from https://course.fast.ai/datasets.

The Yelp reviews polarity dataset is constructed by considering stars 1 and 2 negative, and 3 and 4 positive. For each polarity 280,000 training samples and 19,000 testing samples are take randomly. In total there are 560,000 trainig samples and 38,000 testing samples. Negative polarity is class 1, and positive class 2.

The files train.csv and test.csv contain all the training samples as comma-sparated values. There are 2 columns in them, corresponding to class index (1 and 2) and review text. The review texts are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). New lines are escaped by a backslash followed with an "n" character, that is "\n".

- ### Yelp reviews sample dataset

The original Yelp reviews dataset is retrieved from Yelp directly: https://www.yelp.com/dataset/download. The json file "yelp_academic_dataset_review.json" is very large, containing 6,990,280 lines. So we read the top 50,000 rows as sample for this tentative analysis.

## Algorithms

- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Support Vector Machines (SVM)
