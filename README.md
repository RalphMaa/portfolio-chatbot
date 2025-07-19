# 📊 StockAdvisorAI

**StockAdvisorAI** is an AI-powered investment assistant that allows you to simulate stock and ETF trades, view your portfolio breakdown as a pie chart, and interact via chat or voice. It leverages OpenAI's LLMs and real-time stock data through Alpaca's API to offer a seamless, conversational investing simulation experience.

---

## 🚀 Features

- 💬 Conversational chat interface powered by LLMs
- 🗣️ Voice input for hands-free interaction
- 🛒 Simulated portfolio management (buy stocks & ETFs, view holdings)
- 📈 Real-time market data via Alpaca API
- 📊 Live-updating pie chart showing portfolio allocation (including cash on hand)
- 🧠 Reasoned, step-by-step investment insights

---

## 🧾 Project Structure

All logic is contained in a single notebook:

```
📁 StockAdvisorAI/
│
└── 📄 Stock_advisor_chatbot.ipynb  # Main Jupyter Notebook
```

---

## ⚙️ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/your-username/StockAdvisorAI.git
cd StockAdvisorAI
```

### 2. Set up your environment

Install dependencies with pip:

```bash
pip install openai gradio plotly python-dotenv alpaca-trade-api
```

Or install from a `requirements.txt` if provided:

```bash
pip install -r requirements.txt
```

### 3. Create `.env` file with your API keys

In the root directory, add a `.env` file:

```env
OPENAI_API_KEY=your_openai_key_here
ALPACA_API_KEY=your_alpaca_api_key_here
ALPACA_SECRET_KEY=your_alpaca_secret_key_here
```

> ✅ You must use **Alpaca Paper Trading** mode (not live mode)

### 4. Launch the app

Open the notebook in Jupyter:

```bash
jupyter lab
```

Run `Stock_advisor_chatbot.ipynb` from top to bottom. Once launched, Gradio will open a local web app with:

- 💬 Chat panel (left)
- 📊 Portfolio pie chart (right)
- 🎤 Voice-to-text input (below chat)

---

## 💡 Example Use Cases

- “What ETF tracks the Nasdaq?”
- “Buy 3 shares of AAPL”
- “Show my portfolio”
- “What’s the market value of SPY?”
- “How much cash do I have left?”

---

## 🔐 Disclaimer

This tool is **strictly for educational and simulation purposes**. It does not provide real financial advice or execute real trades.

---

## 📌 Tech Stack

- [Gradio](https://gradio.app/) – Frontend interface
- [OpenAI](https://openai.com/) – Natural language processing
- [Alpaca](https://alpaca.markets/) – Real-time market data
- [Plotly](https://plotly.com/python/pie-charts/) – Dynamic pie chart
- [Python Dotenv](https://pypi.org/project/python-dotenv/) – Secure API key loading

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- OpenAI for language models
- Alpaca for free market data API
- Gradio for building fast UIs in Python
