# SwitchGain

![GitHub](https://img.shields.io/badge/license-MIT-blue)  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  

**SwitchGain** is a Python-based algorithmic trading project that explores **Momentum Trading** and **Mean Reversion** strategies. The project leverages data science techniques to generate automated buy/sell signals and evaluates their performance using key financial metrics.  

## 📌 Features  

- **Two Trading Strategies:**  
  - **Momentum Trading:** Uses RSI and short-term price changes to identify trends.  
  - **Mean Reversion:** Applies Bollinger Bands and Z-Score to detect overbought/oversold conditions.  
- **Automated Data Pipeline:** Fetches historical AAPL data from **Yahoo Finance (yfinance)**.  
- **Interactive Visualizations:** Plotly-based charts for strategy analysis.  
- **Performance Metrics:** Evaluates strategy effectiveness in different market conditions.  

## 🚀 Quick Start  

### Clone the Repository  
```bash
git clone https://github.com/your-username/SwitchGain.git  
cd SwitchGain  
```

## 📊 Strategy Highlights  

| **Strategy**       | **Key Indicators**          | **Signal Condition**                     |  
|--------------------|----------------------------|------------------------------------------|  
| Momentum          | RSI, 5-day % change       | Buy: `Momentum_5D > 0 & RSI (30-70)`     |  
| Mean Reversion    | Z-Score, Bollinger Bands  | Buy: `Price < Lower Band (Z < -1.5)`     |  

## 📈 Results  

- **Momentum** performs best in **trending markets** (e.g., sustained bullish runs).  
- **Mean Reversion** excels in **ranging markets** (e.g., price bouncing between bands).  
- Combining both strategies could improve adaptability.   

## 🤝 Contributing  
Pull requests are welcome! For major changes, open an issue first.  

## 📜 License  
MIT © 2025 Albin James Maliakal  

---  
**🔗 Relevant Links**  
- [Yahoo Finance](https://finance.yahoo.com/)  
- [Plotly Documentation](https://plotly.com/python/)  

---  
**SwitchGain** – Trade smart, not hard! 🚀