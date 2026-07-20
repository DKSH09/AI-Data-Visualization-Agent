
# AI Data Visualization Agent

**Conversational data exploration, powered by LLMs.**

Tactara’s AI Data Visualization Agent transforms static datasets into dynamic insights using natural language. Just upload your CSV, ask a question, and our agent will analyze your data, generate the right charts, and offer rich statistical context — all inside a sleek Streamlit interface.

---

## 🚀 Why Teams Choose Tactara

### 💬 Natural Language Querying  
- Ask questions like: “What are the top-selling products by region?”  
- Follow up in plain English to refine visualizations or dive deeper  
- Combines charts + statistical summaries + contextual insights

### 📊 Intelligent Visualization Engine  
- Selects the right chart automatically based on your question  
- Supports bar, line, scatter, histogram, pie, and more  
- Applies statistical methods (mean, correlation, trend detection)  

### 🧠 Multi-Model AI Backend  
- Built with a model-routing layer for performance and scale  
- Supports:
  - **Meta-Llama 3.1 405B** for complex analysis  
  - **DeepSeek V3** for deep insight generation  
  - **Qwen 2.5 7B** for quick lookups  
  - **Meta-Llama 3.3 70B** for detailed breakdowns

---

## 🛠️ Quickstart

### 1. Clone the Repo

```bash
git clone https://github.com/DKSH09/AI-Data-Visualization-Agent.git
cd AI-Data-Visualization-Agent
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Your API Keys  
You’ll need:

- [Together AI API Key](https://api.together.ai/signin)  
- [E2B API Key](https://e2b.dev/docs/legacy/getting-started/api-key)

Input them via the Streamlit sidebar on first run.

### 4. Launch the App

```bash
streamlit run ai_data_viz_agent.py
```

---

## 📂 Using the Visualization Agent

- Upload a CSV file  
- Ask a question about the data in plain language  
- View charts + textual explanations  
- Ask follow-up questions to refine analysis or change visuals

---

## 🔍 Under the Hood

| Component | Description |
|----------|-------------|
| 🧠 **LLMs** | Power natural language understanding & chart generation |
| 📊 **Visualization Engine** | Matplotlib + Seaborn-based smart plotting |
| 📂 **Streamlit UI** | Seamless user interface for fast experimentation |


