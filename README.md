# News_sentiment_analysis
The major task of these three files is to provide a stable sentiment prediction model to handle prediction challenges in online business news for fashion companies.

Experiment 1:  Sentiment Labelling Based on Pseudo-Labelling Method (File name: dictionary_based labelling and semi-supervised learning)
The first experiment applies NLP methodologies, such as word2vec embedding, in order to transform the raw text of articles, our unstructured data, into a Vector Space Model and extract features. For the purpose of labelling, we build a set of machine learning models containing support vector machine (SVM), XGBoost, long short-term memory (LSTM) and random forest (RF) on labelled dataset and then apply pseudo-labelling to opt an optimal labelling model.


Experiment 2: ‘Brand-oriented’ Sentiment Prediction Modelling (File name: Final_modelling)
The second experiment leverages the sentiment labelling output as the model’s label and selects articles’ other features such as tags, exclusivity, traffic metrics like page views, Facebook “likes” and LinkedIn shares from Scrapy, which may also contain important sentiment information. In addition, article key words are extracted based on frequency-inverse document frequency (TF-IDF) algorithm as model inputs. 

