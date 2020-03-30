#Wrangling WeRateDogs Twitter Data
For this project I was set with the task of cleaning tweet data belonging to the popular WeRateDogs twitter account. This report describes the data wrangling process undertaken. 
 
Gather – The data for this project was gathered from three sources. The twitter archive, which is a csv file containing the tweet, rating, dog name & dog stage data. An Image prediction file was a TSV file that held the tweet & associated tweet Image details, as well as prediction columns that tell us what dog breed the tweet image contains. The twitter API was accessed to collect retweet and favorite counts for each tweet. A Twitter developer account had to be created at this step-in order to gain access to the Twitter API account. 
 
Assess – The data at this step was assessed visually to start with in order to identify any notable / easily identifiable issues with the data. This involved opening the data sources in excel to begin with, were the layout and structure was reviewed. The data was then programmatically assessed using Pandas, based on quality and tidiness predominantly. 
 
Clean – Each of the items documented during the assessing phase then had to cleaned. The aim here was to deliver a tidier, higher quality dataframe at the end which was easier for a data analyst to work with and interpret.  
 
All three phases were performed in the attached python project file: wrangle_act.ipynb in Jupyter Notebook.

Libraries Used: pandas, json, tweepy, matplotlib, seaborn, os, numpy
