# 📈 Stock Portfolio Simulator & Advisor

A web app built with **Gradio**, **Plotly**, and **OpenAI’s LLM** tools that lets you:

- Chat with an AI-based **stock investment advisor**  
- Simulate buying U.S.-listed stocks and ETFs using a fictional portfolio  
- View a **dynamic pie chart** of portfolio allocations including cash  
- Ask for live **market prices** fetched via a tool interface  

---

## 🚀 Features

- **💡 Stock Advice**  
  Gives recommended U.S.-tradable stock and ETF ideas, with step-by-step explanations.

- **🎮 Portfolio Simulation**  
  Simulate trades through chat (e.g., “Buy $1,000 of AAPL”), and track holdings + cash.

- **📊 Live Visuals**  
  Pie chart updates in real-time showing proportional allocation in stock vs. cash.

- **🏷️ Market Value Lookup**  
  Ask “What is the market value of MSFT?” — AI fetches the latest price using a tool.

- **🔒 Safe & Compliant**  
  Purely hypothetical—no real money advice. Only U.S.-listed stocks are included.

---

## 🛠️ Quickstart

1. **Clone & install dependencies**
    ```bash
    git clone https://github.com/yourusername/stock-portfolio-simulator.git
    cd stock-portfolio-simulator
    pip install -r requirements.txt
    ```

2. **Set your OpenAI key**  
   ```bash
   export OPENAI_API_KEY="your_api_key_here"
