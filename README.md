# 🤖 AI-Powered Stock Market Predictor


A real-time **stock forecasting and analysis tool** powered by AI (Groq LLaMA3), technical indicators, and news sentiment.  
Built using **Streamlit**, **Machine Learning**, **Yahoo Finance**, and **LLMs** — hosted on Hugging Face Spaces.

🔗 **Live App**: [Hugging Face Space](https://huggingface.co/spaces/umarfarooq8505/Stock-Market-Predictor)

---

## 🚀 Features

### 📈 Stock Analysis
- Real-time stock price data via Yahoo Finance
- Calculates:
  - SMA / EMA
  - MACD
  - RSI
  - Bollinger Bands
  - Volume indicators

### 📰 Sentiment Analysis
- Estimates sentiment from market trends and price changes
- Simulates news-based analysis using contextual changes

### 🧠 AI-Powered Predictions
- Multi-day price forecasting using:
  - Random Forest Regressor
  - Technical indicators
  - Sentiment signals

### 💬 AI Chat Assistant
- Ask anything about stocks, strategies, indicators, markets
- Powered by **Groq LLaMA3 (70B)** or fallback expert responses
- Context-aware conversation with past history

---

## 📊 How It Works

| Module             | Purpose                                                                 |
|--------------------|-------------------------------------------------------------------------|
| **Data Collection**| Fetches stock and volume data using `yfinance`                         |
| **Technical Analysis** | Computes advanced indicators like RSI, MACD, Bollinger Bands       |
| **Prediction**     | Machine Learning forecasts using Random Forest                        |
| **LLM Chat Assistant**| Interactive chatbot trained on market concepts and indicators       |

---

## 🛠️ Technologies Used

- 🐍 Python
- 📊 Streamlit
- 🤖 Scikit-learn (Random Forest)
- 📰 TextBlob (Sentiment)
- 📉 yFinance API
- 🧠 Groq AI (LLaMA-3)
- 🎯 Plotly Charts
- 🌐 Hugging Face Spaces

---

## 📁 Project Structure

├── app.py # Streamlit main interface
├── stock_predictor.py # AI + technical logic
├── groq_assistant.py # Chatbot with Groq or fallback
├── requirements.txt # All dependencies
├── README.md # This file

yaml
Copy
Edit

---

## 📦 Setup Instructions

### 🔐 Step 1: Add API Keys as Secrets

On **Hugging Face** or **Google Colab**, add these secrets:

- `GROQ_API_KEY` – get it from [Groq Console](https://console.groq.com)
- *(Optional)* `GOOGLE_API_KEY` if using Gemini

In code, they are accessed using:

```python
import os
api_key = os.environ["GROQ_API_KEY"]
▶️ Step 2: Run the App
Option A: 🧪 Run Locally
bash
Copy
Edit
git clone https://github.com/your-username/stock-market-predictor.git
cd stock-market-predictor
pip install -r requirements.txt
streamlit run app.py
Option B: ☁️ Run on Hugging Face (Already Live)
No setup needed — Click here to use it

🧑‍🤝‍🧑 Meet the Team
Name	Role
Irfan Ali	 
Umar Farooq	
Muhammad Ammar Bin Saeed	
Syeda Hania Zahra	
Ahmad Hassan	
Muhammad Azeem Ashraf	

🧠 Example Prompts to Try
Ask the AI assistant:

“What is RSI and how to trade with it?”

“Is AAPL stock overbought or oversold?”

“Explain MACD vs EMA in stock analysis”

“What are signs of a bull market?”

⚠️ Disclaimer
This tool is for educational and demonstration purposes only.
It does not provide financial advice. Always consult a licensed financial advisor before investing.

📄 License
This project is licensed under the MIT License.

