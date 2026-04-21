# LifeAtlas Level 3 Agent 🚀

An explainable AI agent built with Python that connects to the LifeAtlas LPI MCP server, queries multiple tools, and uses Ollama to generate intelligent answers with source transparency.

---

## 📌 Features

* Accepts natural language user questions
* Connects to MCP tool server
* Uses multiple tools to gather knowledge
* Combines outputs using a local LLM
* Produces explainable responses with cited tool sources
* Runs locally without paid API keys

---

## 🛠 Tech Stack

* Python 3.x
* Node.js
* MCP (Model Context Protocol)
* Ollama
* qwen2.5:1.5b model
* requests library

---

## 📂 Project Structure

```text
lifeatlas-level3-agent/
│── agent.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Tools Used

* smile_overview
* query_knowledge
* get_case_studies

---

## ▶️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/SandeepGunti18/lifeatlas-level3-agent.git
cd lifeatlas-level3-agent
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Build LifeAtlas MCP Server

```bash
npm install
npm run build
```

### 4. Start Ollama

```bash
ollama serve
ollama pull qwen2.5:1.5b
```

---

## ▶️ Run Project

```bash
python agent.py
```

---

## 💬 Example Query

```text
How can hospitals use digital twins?
```

## Example Output

* Predict equipment maintenance
* Improve patient flow
* Optimize staffing
* Reduce operational cost
* Simulate emergency scenarios

Sources:

* smile_overview
* query_knowledge
* get_case_studies

--=
---

## 📚 What I Learned

* MCP tool-calling systems
* Local LLM integration
* Explainable AI design
* Python + Node.js interoperability
* GitHub project publishing workflow

---

## 🚀 Future Improvements

* Streamlit web UI
* Chat history memory
* More LifeAtlas tools
* Better prompt engineering
* Export reports as PDF

---

## 👤 Author

Sandeep Gunti
GitHub: https://github.com/SandeepGunti18
