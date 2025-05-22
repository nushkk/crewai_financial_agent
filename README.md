# 📈 CrewAI Financial Analysis Agent

This project simulates a multi-agent system for financial market analysis using [CrewAI](https://github.com/joaomdmoura/crewai) and OpenAI's GPT-3.5-turbo. It models a collaborative team of AI agents that work together to analyze stock data, generate trading strategies, plan execution, and assess risk.

## 🤖 Agents

- **Data Analyst** – Monitors market data and identifies trends  
- **Strategy Developer** – Builds trading strategies based on risk and insights  
- **Trade Advisor** – Plans execution of trades based on timing and pricing  
- **Risk Advisor** – Assesses financial risks and proposes mitigation strategies

## 🧪 Technologies Used

- Python  
- Jupyter Notebook  
- CrewAI  
- LangChain + OpenAI  
- Serper.dev (search tool)  
- `.env` + `utils.py` for secure API management

## 🚀 How to Run

1. **Clone this repo**
   ```bash
   git clone https://github.com/nushkk/crewai_financial_agent.git
   cd crewai_financial_agent
```

2. **Create a `.env` file** in the root directory:

   ```
   OPENAI_API_KEY=your-openai-api-key
   SERPER_API_KEY=your-serper-api-key
   ```

3. **(Optional but recommended)** Set up a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install crewai==0.28.8 crewai_tools==0.1.6 langchain_community==0.0.29
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   Then open `financial_trading_agent.ipynb` and run all cells.

> ⚠️ **Note**: You need valid API keys to run this notebook. The keys are not included for security reasons.

## 📚 What I Learned

* How to design collaborative AI agent systems
* Using CrewAI to delegate tasks and manage reasoning across roles
* Prompt engineering for financial workflows
* API key management using `.env` and Git best practices

