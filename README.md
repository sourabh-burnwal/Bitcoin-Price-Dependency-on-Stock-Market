# Bitcoin-Price-Dependency-on-Stock-Market
#### How Bitcoin price movements are related to or affected by the various fluctuations in Stock market. We have considered SP500, Oil Prices, Gold Prices and finding how these three and Bitcoin prices are correlated. Also, how their volatilities affect the others. The goal of this project is to come up with a conclusion which will help in Bitcoin price prediction.


```
├── DATA
│    ├── bitcoin gold price.csv
│    ├── bitcoin_raw.csv
│    ├── raw_v2_dataset.csv
│    ├── oil_price_raw.csv
│    ├── gold_df.csv
│    ├── vixcurrent.csv
│    └── dataset_final.csv  (Final Dataset)
├── Notebook
│    ├── Data Preparation
│    │   ├── feature extraction.ipynb (Feature Extractor Notebook)
│    │   └── dataset prep.ipynb
│    ├──Data_Analysis.ipynb
|
```

### The datasets sources are as Follows :
  - The Base dataset is from Kaggle : https://www.kaggle.com/wojtekbonicki/bitcoin-data
  - Bitcoin historic raw data is from Coindesk portal
  - Oil historic raw data has been acquired from Yahoo Finance
  - VIX close dataset is from CBOE
  - Gold historic data is from World Gold Council (GoldHub)

### The paper we are following : 
  - Rama Malladi et al. (2019), "Predicting Bitcoin Return And Volatility Using Gold And The Stock Market"

### The Extracted Features :
  - Daily Returns of Bitcoin, Gold, Oil, SP500
  - Bitcoin 30 days historic Volatility index, BVOL (source: BitMEX)
  - Gold Volatility: GVOL, and Oil Volatility: OVOL have been calculated using the same formula as on BitMEX
