# Financial-Sentiment-Analysis-with-Machine-Learning-LSTM-and-BERT-Transformer
This project applies three main methods to make sentiment analysis on financial data: 
1. Machine Learning 
2. LSTM using TensorFlow with Keras API
3. BERT Transformer using the "simpletransformers" library

For the first method, I use two well-known machine learning libraries of scikit-learn and XGBoost. With the former, I make use of these models:
  * Naive Bayes
  * Multinomial Naive Bayes
  * Logistic Regression
  * Support Vector Machine (SVM)

With the latter, I use:
  * XGBClassifier


For the second method, I use LSTM network using Keras API of TensorFlow.

Finally, for the last method, with the convenience of "simpletransformers" library, I use BERT transformer to make sentiment analysis.

# Conclusion:

Among the machine learning models, the poorest performance was Naive Bayes' with 0.52 accuracy. While, LinearSVC and XGBoost achieved the highest accuracy by 0.67.
By using LSTM, I managed to increase the accuracy to 0.70. 
Finally, with BERT, I got the highest accuracy, which is 0.77. 
In conclusion, not surprisingly, the BERT transformer model seems to be the best model for this financial sentiment analysis among the models I made use of.

# Results/Full comparison of the models:

|       Models       | accuracy |
| -----------------  | -------- |
|Naive Bayes         | 0.52     |
|Multinomial NB      | 0.65     |
|Logistic Regression | 0.65     |
|Linear SVC          | 0.67     |
|XGBoost             | 0.67     |
|LSTM                | 0.70     |
|BERT                | 0.77     |


# Links:
* The data: https://www.kaggle.com/sbhatti/financial-sentiment-analysis
* simpletransformers library repository: https://github.com/ThilinaRajapakse/simpletransformers
* "Simple Transformers" website: https://simpletransformers.ai/
