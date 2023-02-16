# Basic Sentiment Analysis using Scikit-learn

The program uses Python’s scikit-learn library for implementing sentiment analysis using the Naive Bayes, Random Forest and Support Vector Machine algorithms on a dataset of IMDB movie reviews.

The dataset has already been split into the training, test and validation sets. In this program, the train and test sets have been combined and split again using train_test_split. The validation dataset is ignored as evaluation of the model is beyond the scope of the program.

The kaggle dataset can be accessed here: https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format

The Random Forest Classifier and Support Vector Machine yield the best accuracy(85.65) followed by the Naive Bayes Classifier(78.26).

As the data isn’t extremely suitable for the model, due to X being a sparse matrix, neural network models could provide better accuracy.
