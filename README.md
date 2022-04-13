# :exclamation:# Final-Project :exclamation:

## Overview 
Our team decided on April 4 to develop a stock prediction model. We found a rudimentary model that we are seeking to improve. The current model using historical daily price data for publicly traded companies.
## Project roles:
- Ben: Square 
- Bob: Triangle
- Khagen: X
- Tim: Circle
## Communication used during project
- Slack
- Git Hub
- Zoom
	- Class time & out side of class time
## Tools used
- Conda 4.12.0
- Python 3.7.11
- scikit-learn 0.24.2
- plotly 5.6.0
- pandas 1.3.4
- Amazon Web Services
- Jupiter Notebook
- Jupiter Lab
- PySpark

## Project Details

--------- All completed on the aapl.ipynb file ---------
1. Pull apple stock from API
2. Convert to Data Frame Table
3. Connected to Postgres
4. Connected Postgres to AWS

--------- Switch to the aapl_stock_price_prediction.ipynb file ---------
1. Pull data back from the AWS/Postgres tables
2. Convert to Data Frame again
3. Changed column row names to make it similar to other model
4. Changed needed column / date dtypes
5. Changed index
6. Completed the Prediction model

--------- Other Edits ---------
1. Branch updates completed
2. Merged "ben-branch" with the Main Branch
3. Edited the ReadMe File

## Project Questions
Comparing the Prediction Model from: https://data-flair.training/blogs/stock-price-prediction-machine-learning-project-in-python/ ...
1. Can we download the snippets of this code, and re-create a working model?
2. Can we find an API site instead of the CSV file, and create a working model that is always up-to-date?
3. If we add another industry (like Meme stocks vs Tech stocks), will the model continue to work?
4. Is there another prediction model that would work better?

## Project Progress
We have completed a working model with an integrated API call. We only were able to apply this with the AAPL stock, only. But we expect to add 5 other stocks. We have not posted this model on a website, but will do that in the future. We have completed the requirements of the Final Project Week 1. 

## Rubric Goals

### Presentation
We presented our topic (Stock Prediction Model) , reasons why we selected the topic (We are all interested in investments), description of the source data (The original source was the Data-Flair site listed above. We took a project that was presented there, and re-created it. We expect to test it with other industries and prediction models.), and our questions we hope to answer (listed above in the section: "Project Questions".) during the Presentation on Wednesday, April 6, 2022. 

### GitHub
Our Main branch has this ReadMe file in it, and it includes our communication protocols as well as the programs used while working on this project. We have one branch per person on the team, and each person has committed at least 4 times. We have also included in detail our first week's progress.

### Machine Learning Model
We have based our model on the LSTM (Long Short-Term Memory) Prediction Model. We stored our data (after it was cleaned) in our PostgreSQL database that is connected to our AWS server. We were also able to save a secondary file that has an Output label.

### Database
As mentioned above, our database is initially stored on our PGadmin's PostgreSQL database, and connected to the cloud via our AWS database. Our sample data mimics the expected final database structure and schema. Our Draft machine learning module is connected to the provisional database. 



