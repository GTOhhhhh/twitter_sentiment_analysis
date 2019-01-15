# Twitter Sentiment Analysis Model

The goal for this project is to build a model for detecting hate speech in tweets. In other words a binary classifaciton task, (hate speech) or (not hate speech). This repository implements and compares 4 different models for this task: 
- BoW (bag of words)
- LSTM (long term short term memory network)
- SVM (suppor vector) 
- MnB (multinomial bayes).

## Getting Started
Notebook 1 (1_preprocessing_bow.ipynb) contains data preprocessing and the BoW model.

Notebook 2 (2_models_and_analysis.ipynb) contains the LSTM, SVM & MnB and analysis/comparison of results.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

All data for this project is sourced from: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/. Inspiration and some code for this project has been taken from:

- 'Stemming - Natural Language Processing With Python and NLTK p.3'- https://www.youtube.com/watch?v=yGKTphqxR9Q
- https://datascienceplus.com/twitter-analysis-with-python/
Ultimate guide to deal with Text Data (using Python) – for Data Scientists & Engineers 
- https://www.analyticsvidhya.com/blog/2018/02/the-different-methods-deal-text-data-predictive-python/
- 'Deep Learning tutorials in jupyter notebooks.' - https://github.com/sachinruk/deepschool.io
- 'Text Classification Using CNN, LSTM and visualize Word Embeddings' - https://medium.com/@sabber/classifying-yelp-review-comments-using-cnn-lstm-and-visualize-word-embeddings-part-2-ca137a42a97d
- Tensor Flow: Embeddings Guide - https://www.tensorflow.org/guide/embedding
- Comparing scikit-learn text classifiers https://blog.kjamistan.com/comparing-scikit-learn-text-classifiers-on-a-fake-news-dataset/
- Understanding LSTM Networks - http://colah.github.io/posts/2015-08-Understanding-LSTMs/
