# CryptoCurrency Price Regression Model

The goal of this project is to use linear regression to identify relationships between Cryptocurrency Price and its related factors that contribute to fundamental analysis of Crypto and yield investment opportunities.  I worked with 3 datasets focused on Circulating Supply, Market Capitalization, Social Media volumes, and On-Chain Transactions. After running baseline regression models, conducting cross validation, applying regularization, and utilizing feature engineering, I was able to find strong correlations with certain crypto factors and build a blueprint for fundamental analysis.  

Design

Digital currencies or Cryptocurrencies are exploding into mainstream. With the rise of Bitcoin, Ethereum, and other altcoins, more and more investors are developing a keen interest in them. A key problem is that there has not been an established way to fundamentally evaluate  cryptocurrencies, and thus this project is dedicated to find crypto factors that are correlated with price and serves as a starting point to crypto fundamental analysis.

Data

There were 3 datasets I worked off of. First and second dataset are scraped from www.coinmarketcap.com. Third dataset is taken via API from www.sentiment.net.


Algorithms
Methodology & Steps:

Step 1: Scrape Data from website or Download from API
  
  Step 2: Clean Data
	
  Step 3: Create Baseline OLS linear regression model
	
  Step 4: Check Assumption and Evaluation
	        
          Check for outliers using Cook D
	        Check for Non-normality (scatter and Q-Q plot)
	        Check for Collinearity (VIF)
	
  Step 5: Residual Analysis - look for high residual observations for insight
	
  Step 6: Apply Cross Validation
  
	        Train, validation, test
	        5-fold cross validation using K-Fold
	
  Step 7: Apply Regularization - Ridge, Lasso, Elastic Net
	
  Step 8: Apply Feature Engineering
  
	        Interaction Terms using Polynomial Features
	        Adding Dummy Variables
	
  Step 9: Conclude and pick the best model
  
Result

Since Circulating Supply is highly correlated with CryptoPrice (R^2 = 0.868), we can use our regression model to find over or undervalued crypto’s through predictions. In Dataset 3, we found correlations with Reddit and very strong correlation with On-Chain Transaction^2. These three components are starting points to build a blueprint for fundamental analysis of crypto.

Tools

Selenium, BeautifulSoup, Pandas, Matplotlib, Seaborn, SkLearn, Statsmodel

Communication

Slides and visuals are in PPT, submitted via PDF.

