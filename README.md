# CMPT 353 Final Project

# Topic: Stock Market Analysis

## Project Summary
The aim of this project is to predict the next hyped up stock by using statistical tests and machine learning models. 

Data analysis begins with determining what we need the data for and what is the main outcome/question we need an answer to. On this project, the most hyped stock is being examined to determine whether to buy or sell it using tests and machine learning models.

## Enivironment used
* **GoogleColab is highly recomended as our project installations are based on it.**
* Python - version 3.0 or higher

## Required APIs and their installations 
### Package managers and installation
Any package managers can be used but we are using pip3 and pip

### Python libraries
* pip install transformers
* pip install requests
* pip install seaborn
* pip install pandas-datareader 

### Machine Learning and Statistical Tests Libraries
* pip install scikit-learn
* pip install tensorflow
* pip install torch
* pip install scipy
* pip install keras


### API Libraries
* ta-lib (only for **GoogleColab**)
	* url = 'https://launchpad.net/~mario-mariomedina/+archive/ubuntu/talib/+files'
	* !wget $url/libta-lib0_0.4.0-oneiric1_amd64.deb -qO libta.deb
	* !wget $url/ta-lib0-dev_0.4.0-oneiric1_amd64.deb -qO ta.deb
	* !dpkg -i libta.deb ta.deb
	* pip install ta-lib
* pip install yfinance
* pip install psaw
* pip install quandl

## Required Libraries
### Python libraries
* pandas
* numpy
* matplotlib
* re
* difflib
* datetime
* pandas_datareader
* transformers
* requests
* seaborn

### Machine Learning and Statistical Tests Libraries
* sklearn
* tensorflow
* keras
* pytorch
* scipy


### API Libraries
* talib
* yfinance
* psaw
* quandl
* BERT

## Order of Execution
* Run "01-Get_stock_tickers.ipynb"
	* Extracts the ticker simbols of stocks listed on NYSE and NASDAQ as 'stock_ticker.csv'

* Run "02-Extracting_reddit_posts.ipynb"
	* Extracts the most talked about stocks from Reddit as 'df_combined.csv' and 'df_combined_10.csv'

* Run "03-Stock_market_analysis.ipynb"
	* This file performs statistical tests and machine learning concepts to predict the next hyped stock.

## Data
* All files used and produced are in 'data' folder
* Since we needed real time data, we are submitting csv files in 'data -> Raw_data' folder and further we are using APIs to get full realtime data. We are submitting implementation using both .csv files and APIs. 
### Raw_data
* This file contains the data we took from Kaggle
### Processed_data
* This file contains cleaned and processed data
### Plots
* This file contains all the plots and visualizations


## Aside
### Using Google-Colab
* Please un-comment the code under 'google-colab' section. 
### File formating
due to relative paths used by us, please follow this file formating scheme:
* cmpt353-group-project
	* data *folder*
	* 01-Get_stock_tickers.ipynb *file*
	* 02-Extracting_reddit_posts.ipynb *file*
	* 03-Stock_market_analysis.ipynb *file*

## Developers
* Jyotiraditya Mayor (jmayor@sfu.ca -> **301401591**)
* Ritika Goyal (rgoyal@sfu.ca -> **301401516**)
* Navjot Kaur (nka57@sfu.ca -> **301404765**)
* Dhairya Kalra (dkalra@sfu.ca -> **301386482**)