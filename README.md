# 🌾 India Agriculture Market Price Pipeline

Real-time analysis of daily crop prices across 819 markets 
and 26 states using live government APMC data.

## 🎯 Problem Statement
Indian farmers often sell their produce in the wrong market
and lose thousands of rupees per quintal. This pipeline 
identifies the best markets for maximum profit using live 
government data.

## 📊 Data Source
- **API:** data.gov.in (Indian Government Open Data)
- **Dataset:** Daily APMC Market Prices
- **Scale:** 4,900+ records | 26 states | 819 markets | 198 commodities
- **Updates:** Daily (live API fetch)

## 🔑 Key Findings
- Arecanut farmers lose ₹41,615/quintal by selling in the 
  wrong market on the same day
- Karnataka (Shimoga) pays highest Arecanut prices in India
- Pepper is the most expensive commodity nationally (₹65,000+/quintal)
- Meghalaya has highest price volatility across all states

## 🤖 ML Model
Built a Linear Regression model to predict Modal Price
- **Input:** State, Commodity, Min Price, Max Price
- **Mean Absolute Error: ₹138** (highly accurate)

## 🛠️ Tools & Technologies
- Python
- Pandas
- Requests (REST API)
- Matplotlib & Seaborn
- Scikit-learn
- data.gov.in API

## 📁 Project Structure
├── india-agri-price-pipeline.ipynb  # Main pipeline notebook
├── live_market_data.csv             # Fetched data
└── README.md
## 🚀 How to Run
1. Clone this repo
2. Get free API key from data.gov.in
3. Replace api_key in notebook
4. Run all cells
