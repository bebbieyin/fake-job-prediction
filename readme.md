# Real/Fake Job Prediction with BiLSTM

Predicting whether a job advertisement is real or fraudulent based on the text features. BiLSTM is used to exploit the sequential nature of the data. Different from similar methods, extra steps is used to ensure the handling of imbalanced data. In addition, data analysis is done to gain more insight on the data. 
<br>

## Dataset

Dataset is  Employment Scam Aegean Dataset (EMSCAD) by University of the Aegean, Laboratory of Information & Communication Systems Security. It is made available on [Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction). <br>
It has 18k instances with 18 attributes. The target variable is fraudulent where 0 means real and 1 means fake. The class distribution is highly imbalanced, out of a total of 17880 samples, only 866 of them are fraudulent jobs. 

## Results

Precision, Recall and F1-score is used to evaluate model performance instead of accuracy due to the imbalanced data. 

| Metrics      |  |
| ----------- | ----------- |
| Precision      | 68       |
| Recall   | 76        |
| F1-score   | 80        |
| Precision-Recall Curve (PRC)   | 72        |