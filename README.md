
## Solana (SOL) Price Prediction Using LSTM and Beta Coefficient Analysis  

This project aims to predict the price of **Solana (SOL)**, a popular cryptocurrency, by leveraging a **Long Short-Term Memory (LSTM)** model combined with insights from **linear regression**. To achieve this, we utilized the `yfinance` library to gather historical price data for both Solana and Bitcoin (BTC).

---

### 📊 **Data Sources**  
- **Bitcoin (BTC):**  
  Bitcoin's historical price data was used to calculate the **beta coefficient**, which measures Solana's sensitivity and correlation with broader market movements.  
  - The **beta coefficient** is a critical financial metric that provides insights into how Solana's price is influenced by changes in Bitcoin, often considered the benchmark for the cryptocurrency market.  

- **Solana (SOL):**  
  Solana's historical price data, retrieved using `yfinance`, served as the primary dataset for training the LSTM model.  
  - This time-series data is essential for accurately forecasting Solana's future price movements.  

---

### 🛠 **Tools and Libraries**  
- **yfinance:**  
  The `yfinance` library is a powerful Python tool for accessing financial data from Yahoo Finance. It allows users to seamlessly retrieve historical data, including prices, volumes, and market indicators, for a variety of financial instruments such as stocks, cryptocurrencies, and indices.  
  - By leveraging `yfinance`, we ensured a streamlined and reliable data acquisition process for both Bitcoin and Solana.  

- **LSTM (Long Short-Term Memory):**  
  LSTMs are a type of recurrent neural network (RNN) well-suited for time-series forecasting. In this project, the LSTM model captures the temporal patterns in Solana's price data to predict future trends effectively.  

---

### 🔍 **Methodology**  
This project combines:  
1. **Statistical Analysis**: Beta coefficient calculation using Bitcoin's price as a market benchmark.  
2. **Predictive Modeling**: Training the LSTM model on Solana's historical price data to forecast future prices.  

This integrated approach bridges financial analysis with machine learning, offering a robust methodology for predicting Solana's price dynamics based on historical trends and market behavior.  

---

### 🚀 **Results and Insights**  
The synergy between the statistical insights from Bitcoin's beta coefficient and the predictive power of the LSTM model provides a comprehensive framework for forecasting Solana's price, capturing both macro market movements and time-series trends.

---

### 📚 **How to Run the Project**  
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```  
2. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the main script:  
   ```bash
   python main.py
   ```  

---

### 🧩 **Dependencies**  
- Python 3.x  
- yfinance  
- TensorFlow / Keras  
- Pandas  
- NumPy  

---

Feel free to contribute, open issues, or provide feedback to improve this project! 🚀  
