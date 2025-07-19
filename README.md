# StockAdvisorAI 🧠📈

An AI-powered voice-enabled investment assistant that helps users explore ETF options, check stock prices, place simulated buy orders, and view their portfolio breakdown — all through a conversational interface backed by LLMs and real-time Alpaca API data.

## 🚀 Features

- 💬 **Chat with a Stock Advisor (LLM-powered)**
- 📊 **Visual Portfolio Pie Chart**
- 🗣️ **Voice-to-Text Input Support (Microphone Enabled)**
- ⚙️ **Tool Use with Function Calling (e.g., buy orders, market value checks)**
- 📡 **Real-time data from Alpaca Trading API**
- ✅ **Simulated portfolio management (No real money used)**

## 📂 Project Structure

All the functionality is self-contained in the Jupyter notebook:

📄 Stock_advisor_chatbot.ipynb

bash
Copy
Edit

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/StockAdvisorAI.git
cd StockAdvisorAI
2. Install Dependencies
Use a virtual environment if you'd like, then run:

bash
Copy
Edit
pip install -r requirements.txt
Or manually install the main libraries:

bash
Copy
Edit
pip install openai gradio python-dotenv plotly alpaca-trade-api
3. Add API Keys
Create a .env file in the root directory with the following content:

env
Copy
Edit
OPENAI_API_KEY=your_openai_key_here
ALPACA_API_KEY=your_alpaca_key_here
ALPACA_SECRET_KEY=your_alpaca_secret_key_here
Make sure your Alpaca account is in paper trading mode for testing purposes.

4. Run the App
Open Stock_advisor_chatbot.ipynb in Jupyter and run the entire notebook.

💡 You’ll see a Gradio app that:

Has a chatbox on the left

A pie chart showing your simulated portfolio on the right

A microphone button to ask questions via voice

💡 Example Use Cases
Ask: “What ETF tracks the Nasdaq?”

Ask: “Buy 2 shares of QQQ”

Ask: “How much money do I have left?”

Ask: “What is the current price of AAPL?”

All backed by OpenAI and Alpaca APIs.

📌 Notes
This is a simulated advisor only — no real financial advice is provided.

Works with GPT-4o-mini by default. You can expand to Anthropic models.

Audio functionality is browser-based through Gradio's mic input.

📃 License
MIT License — feel free to use, extend, or modify this project.

🙌 Acknowledgements
OpenAI
Alpaca Markets
Gradio
Plotly
vbnet
Copy
Edit
