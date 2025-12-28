📊 Public Sentiment Analysis of the 2024 Indonesian Election and Its Relationship with Politicians’ Stock Prices

📌 Overview
This project explores the relationship between public sentiment toward the 2024 Indonesian General Election and the stock price movements of politically affiliated companies.

Using Twitter data as a representation of public opinion, sentiment was classified into positive and negative categories using a Long Short-Term Memory (LSTM) model. The aggregated sentiment trends were then analyzed alongside stock price data using Spearman’s rank correlation to examine whether public opinion has a measurable impact on market behavior.

The results show a statistically significant negative correlation, indicating that increasing negative public sentiment is associated with downward pressure on related stock prices.

Objectives:
- Analyze public sentiment toward the 2024 Indonesian Election using social media data
- Apply deep learning techniques for sentiment classification
- Examine the relationship between political sentiment and stock market movements
- Demonstrate how public opinion can act as an early signal of political risk in financial markets

Methodology:

Data Collection
- Twitter data related to the 2024 Indonesian Election
- Historical stock price data of politically affiliated companies

Sentiment Analysis
- Text preprocessing and cleaning
- Sentiment classification using an LSTM model
- Evaluation using accuracy, precision, and recall
- Statistical Analysis
- Aggregation of sentiment scores over time
- Correlation analysis using Spearman’s rank correlation

Visualization
- Dashboard and visual plots to observe sentiment trends and stock price movements

🛠 Tech Stack

Programming Language: Python

Deep Learning: LSTM (TensorFlow / Keras)

NLP: Text preprocessing, tokenization

Statistical Analysis: Spearman Correlation

Data Visualization: Matplotlib, interactive dashboards

📊 Key Results

Sentiment classification accuracy of approximately 90%, Precision of 93.6%, and recall of 92.7%

Spearman correlation coefficient of approximately -0.402 (p < 0.05)

Evidence of a negative relationship between public sentiment and stock prices
