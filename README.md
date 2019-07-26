# Sentiment-Analysis-using-LSTM-ULMFit

* sentiment_analysis_using_lstm_ulmfit.ipynb : code file

The sentiment analysis of the text in the dataset "Tweets.csv" is done by implementing three LSTM models: 
* Model 1: Simple LSTM Network
* Model 2: LSTM Network with a Dropout Layer
* Model 3: LSTM Network with a Dropout Layer and Regularization

By implementing these, the model's test accuracy was not comparable with the training accuracy even with sufficient hyperparameter tuning. 

On implementing Transfer learning using ULMFiT (Universal Language Model Fine-tuning) to the text in the dataset "Tweets.csv", the test accuracy significantly improved. 

The pre-trained model is also used to predict sentiment of curated dataset of tweets. 

