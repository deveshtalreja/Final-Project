Sentiment_Analysis_Youtube
Overview
This project is a part of a group effort to analyze the sentiment of YouTube comments comparing the United States and Great Britain. We aim to explore the differences in sentiment between these two regions, and consider the effect of the comments sentiment to the interaction on a video.

Contents
Introduction - Background and objectives of the analysis
Data Importing & Cleaning - Loading and preparing the YouTube comments dataset
Exploratory Data Analysis - Uncovering insights through detailed data exploration
Comment Volume Analysis - Comparing number of comments between US and UK
Sentiment Polarity Analysis - Using VADER model to score comment sentiment
Emoji Analysis - Extracting and analyzing use of emojis
Engagement Analysis - Statistical analysis of likes, dislikes, replies
Topic Modeling - Using NMF and LDA to extract discussion topics
Interactive Visualizations - Plots generated using Plotly Express and Dash
Model Development - Training sentiment classification and engagement prediction models
Datasets
USvideos.csv and UScomments.csv - Video metadata and comments from United States
GBvideos.csv and GBcomments.csv - Video metadata and comments from United Kingdom
These CSV files contain samples of YouTube data scraped and published on Kaggle.

Technologies Used
Python
Jupyter Notebook
Pandas
NLTK
Matplotlib
Seaborn
Deepnote Notebook
Results
The sentiment analysis revealed interesting patterns in the comments from both countries. Further details can be found in the Jupyter Notebook provided in this repository.

Future Work
Improve sentiment analysis accuracy by using more advanced natural language processing techniques. Extend the analysis to include comments from other countries for a broader comparison.

How to Run
Clone the repository
Install dependencies like pandas, nltk, scikit-learn
Run jupyter notebook to start Jupyter
Open the youtube_comments_analysis.ipynb notebook
Run the cells in order to reproduce the analysis
Alternatively, view youtube_comments_analysis.html to see a static HTML export of the executed notebook.
Contributors
Aryan Jain
Devesh Talreja
Micah Billington
Rupesh Rangwani
Credits
Thanks to DataSnaek for curating and releasing the YouTube comments dataset on Kaggle.
