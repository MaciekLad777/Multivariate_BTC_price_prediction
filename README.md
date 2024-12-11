# Multivariate_BTC_Price_Prediction  

**This project focuses on building a sequential model to predict the BTC/USD price. It includes data collection, preprocessing, detailed analysis, handling missing values, and final model training and testing.**  

---

## Data  

1. **BTC/USD Price** – Core price data.  

2. **Prices of Related Cryptocurrencies (USD)**  
   - AVAX – Avalanche  
   - BCH – Bitcoin Cash  
   - BNB – Binance Coin  
   - DOGE – Dogecoin  
   - ETH – Ethereum  

3. **Sentiment Data** – Buyer sentiment data indicating the willingness to buy BTC.  
   - Source: [Alternative.me Crypto API](https://alternative.me/crypto/api/)  

4. **Twitter Sentiment** – BTC-related tweets for sentiment analysis.  

5. **BTC Compared to Major World Currencies**  
   - CAD – Canadian Dollar  
   - CNY – Chinese Yuan  
   - EUR – Euro  
   - GBP – British Pound  
   - JPY – Japanese Yen  

6. **Market Volume** – Transaction values conducted using BTC.  

7. **Stock Market Indices**  
   - NYSE – New York Stock Exchange  
   - NASDAQ – Nasdaq Composite Index  
   - LSE – London Stock Exchange  

---

## Notebooks  

1. **`CRYPTO_data_preprocessing.ipynb`**  
   - Data collection and initial analysis.  
   - Reshaping and transforming datasets, handling inconsistencies.  

2. **`CRYPTO_model_training.ipynb`**  
   - Analyzing the impact of individual features on BTC price.  
   - Testing multiple models with different feature sets.  
   - Training and evaluating the final model.  

3. **`CRYPTO_volume_model.ipynb`**  
   - Filling missing values in the **Market Volume** column using interpolation or modeling methods.  

4. **`CRYPTO_twitter_sentiment.ipynb`**  
   - Sentiment analysis of BTC-related tweets.  
   - **Note**: Abandoned due to insufficient tweet data.  

---

## Planned Updates  

1. **Gold Price**  
   - Adding historical and real-time gold price data for correlation analysis.  

2. **Macroeconomic Data**  
   - **Interest Rates** – Tracking changes in loan interest rates.  
   - **Unemployment Rate** – Incorporating unemployment trends to analyze economic impacts on BTC prices.  

---  

This structured approach ensures robust BTC price prediction using multivariate analysis while addressing data gaps and challenges. Future updates will enhance the model with external economic factors for improved accuracy.  
