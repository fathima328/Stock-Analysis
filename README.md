STOCK MOVEMENT ANALYSIS BASED ON SOCIAL MEDIA SENTIMENT

Overview:
For this study, stock movement is analyzed using sentiment analysis from social media. The objective is to use sentiment analysis of Reddit posts—more especially, sentiment in post titles and content to 
forecast the direction of stock prices, whether they will move upward or downward. Data on stock prices and their relationship to sentiment scores are also included in the analysis.

Description:
For this project,
1. Reddit information on stocks was scraped.
2. Used Natural Language Processing (NLP) to do sentiment analysis on Reddit postings titles and content.
3. Examined historical stock price data, and adjusted close prices.
4. Combined stock price data with sentiment data from Reddit.
5. Carried out correlation analysis and produced infographics.
6. Developed a machine learning algorithm that uses sentiment ratings to forecast the direction of stock prices.

Technologies Used:
Python, required libraries(praw, pandas, numpy, matplotlib, seaborn, sklearn, nltk (for sentiment analysis))

Data Sources:
Reddit data via scraping (using PRAW or other scraping tools),
Stock price data from Yahoo Finance API or CSV files.

Machine Learning Model:
Logistic Regression or any other classification model

Visualization: 
The analysis includes sentiment distribution charts, correlation heatmaps, stock price trends over time. 

How to run:
1. Clone the repository.
2. Install the required dependencies: Latest version of python, python libraries(pandas,numpy), machine learning libraries(sklearn), data visualization libraries(matplotlib,seaborn), NLP libraries(nltk),
   data scraping libraries(praw).
3. Run the code: Open Stock sentiment analysis.ipynb in jupyter notebook, then scrape the data, preprocess it, perform sentiment analysis, and train the machine learning model.

Result:
The sentiment scores from Reddit posts were used to predict stock price movements. The machine learing model achieved an accuracy of approximately 85% in forecasting stock price directions.







