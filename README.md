## BITCOIN PRICE PREDICTION WITH MARKET SENTIMENT ANALYSIS

This research explores the integration of market sentiment analysis, derived
from social media platforms with Bitcoin historical price data, into the prediction
models for Bitcoin prices. The study aims to leverage machine learning algorithms for
Bitcoin price prediction, incorporating sentiment features extracted from social media
discussions. The potential variables to be used in training the Bitcoin price prediction
model would include not only Bitcoin historical price data but also sentiment scores and
sentiment indices derived from social media such as Twitter. The machine learning
algorithms that would be applied in this paper to train the Bitcoin price prediction
model would be Linear Regression, Decision Tree, Random Forest, XGBoost and
Neural Network, Long Short Term Memory. In order to evaluate the effectiveness of the
suggested machine learning models in this work, evaluation measures such as Mean
Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE),
and R2 will be utilized. This research contributes to the evolving field of cryptocurrency
price prediction by emphasizing the role of market sentiment, offering insights into the
relationship between social media discourse and cryptocurrency price movements while
also aiming to compare different machine learning models that are used to predict
Bitcoin price.

Jupyter Notebook description:
1. processing.ipynb - Basic text processing workflow and data processing steps
2. VADER_Analysis.ipynb - Vader analysis is performed on the cleaned text and sentiment scores were obtained
3. Plot.ipynb - Data visualization workflow
4. ML.ipynb - Machine learning algorithms such as Linear Regression, Decision Tree, Random Forest and XGBoost being performed
5. Deep_Learning.ipynb - Long Short Term Memory (LSTM) being performed
6. model.ipynb - A simple steamlit local web application to showcase the best model in predicting the price in the next 1 hour.

Data description:
1. Binance_BTCUSDT_1h.csv - Historical bitcoin price data
2. final_sentiment_data.csv - Combined historical bitcoin price data with sentiment score data of 0, -1 and 1 obtained from Vader analysis.

