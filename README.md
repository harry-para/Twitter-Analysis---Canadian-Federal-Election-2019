# Twitter Analysis: 2019 Canadian Federal Election

This project scraped a total of 500 tweets using a Twitter API and analyzed each candidate's tweets during the 2019 Canadian Federal Election.
The tweets were gathered during the campaign period from September to October 21, 2019. October 21, 2019 was the election date.

The candidates observed were:
1. Justin Trudeau - The Liberal Party of Canada
2. Andrew Scheer - The Conservative Party of Canada
3. Jagmeet Singh - The New Democratic Party of Canada
4. Elizabeth May - The Green Party of Canada
5. Maxime Bernier - The People's Party of Canada

The purpose of this project was to conduct a Twitter sentiment and network analysis of the tweets gathered to analyze each of the candidate's social media presence and impacts.
This twitter analysis was able to scrape, manipulate and visualize tweets to analyze potential policital strategies that were taken on by the candidates.

This analysis used Google Sheets to store the scraped tweets and pandas dataframes online that were later used to produce data visualizations on Tableau using the Python programming language via TabPy.
TabPy is an API that enables evaluation of Python code from within a Tableau workbook.

The link to the Tableau workbook is: https://drive.google.com/drive/folders/1LioDRmmS_W3t-h3vq8htEDLQU9cFllFb 

The name of the file is "Twitter Analysis - Canadian Federal Election 2019.twbx".

Note: This file must be downloaded and opened with Tableau Desktop and a TabPy connection to view.

The Python script and output using Jupyter Notebooks via the Visual Studio Code editor is attached above as "Twitter Canadian Political Analysis.ipynb".

Python libraries used include: oauth2client, df2gspread, GetOldTweets3, plotly, numpy, pandas, scikit-learn, tkinter, datetime, nltk

Python APIs used include: gspread and TabPy
