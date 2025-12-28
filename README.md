# 🚀 Agentic AI Labs — Jonathan Marx

Welcome to my personal repository for the **DeepLearning.AI Agentic AI** course series.

This repository documents my hands-on work building **agentic AI systems** that go beyond single-shot LLM calls. The focus is on **reflection, execution feedback, and self-improving workflows** that produce more reliable and correct results.

These labs demonstrate how modern AI agents can:
- Generate initial solutions
- Evaluate their own outputs
- Incorporate feedback (including real execution results)
- Refine responses before producing a final answer

---

## 🧪 Labs Overview

| Lab | Title | Core Pattern | Key Insight |
|----|------|-------------|-------------|
| 01 | Agentic Workflow with Reflection | Reflect → regenerate code | LLMs can iteratively improve executable outputs |
| 02 | Agentic SQL Generation with Reflection | Execute → reflect → refine | SQL can be syntactically correct but semantically wrong |

---

## 🧠 Technologies & Concepts

- Agentic AI workflows
- Reflection patterns
- Execution-aware validation
- Natural language → code / SQL
- Multi-step LLM reasoning
- Python, Pandas, SQLite
- OpenAI GPT-4.x models
- dotenv for secure API configuration

---

## 📁 Repository Structure

```
AgenticLabs/
├── labs/
│ ├── 01_agentic_workflow/
│ │ ├── M2_UGL_1.ipynb
│ │ ├── utils.py
│ │ ├── coffee_sales.csv
│ │ ├── chart_v1.png
│ │ ├── chart_v2.png
│ │ ├── coffee_quarterly_v1.png
│ │ ├── coffee_quarterly_v2.png
│ │ ├── drink_sales_v1.png
│ │ ├── drink_sales_v2.png
│ │ └── README.md
│ │
│ ├── 02_sql_reflection_agent/
│ │ ├── M2_SQL_Reflection_Workflow.ipynb
│ │ └── README.md
│
├── README.md
├── .gitignore
└── requirements.txt

```

---

## 🧪 Lab 1 — Agentic Workflow with Reflection
📍 `labs/01_agentic_workflow`

This lab implements a **reflection-based agent** that improves Python-generated data visualizations.

### Workflow
1. Generate Python code from a natural-language instruction
2. Execute the code to produce an initial chart (V1)
3. Reflect on the chart and code using an LLM
4. Regenerate improved code
5. Execute again to produce a refined chart (V2)

### Key Insight
Reflection enables LLMs to iteratively improve not just *text*, but **executable artifacts** like charts and analysis code.

---

## 🧪 Lab 2 — Agentic SQL Generation with Reflection
📍 `labs/02_sql_reflection_agent`

This lab demonstrates an **execution-aware agentic workflow** for improving natural-language-to-SQL generation.

### Workflow (V1 → V2)
1. Generate an initial SQL query (V1) from a natural-language question
2. Execute the query against a SQLite database
3. Reflect on the *actual query output* (external feedback)
4. Identify semantic issues (e.g., sign errors, aggregation mistakes)
5. Refine the SQL (V2) and re-execute to confirm correctness

### Key Insight
SQL that *looks* correct can still be **semantically wrong**.  
Grounding reflection in **real execution results** allows agents to self-correct subtle but critical errors.

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/jonathanlmarx/AgenticLabs-JonathanMarx.git
cd AgenticLabs-JonathanMarx

```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
.\venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your API keys to a `.env` file

```
OPENAI_API_KEY=your-openai-key
GOOGLE_API_KEY=your-google-key
ANTHROPIC_API_KEY=your-anthropic-key
TAVILY_API_KEY=your-tavily-key
```

---
#🎯 Goals of This Repository

Build a growing portfolio of agent-based AI systems

Demonstrate practical LLM engineering skills

Explore reflection, evaluation loops, and execution grounding

Serve as a foundation for more advanced agent architectures

# 📌 Upcoming Labs

I will continue adding labs as I progress through the Agentic AI curriculum:
* **Planning Agents**
* **Multi-Agent Orchestration**
* **Tool-Using Agents**
* **Retrieval-Augmented Agents**

Stay tuned for more!

---

# 👤 About Me

**Jonathan Marx**
Data Scientist | Business Analyst | AI Engineer-in-Training
Passionate about agentic AI systems, LLM engineering, and end-to-end intelligent pipelines.

🔗 GitHub: [https://github.com/jonathanlmarx](https://github.com/jonathanlmarx)
📧 Email: [jonathan.l.marx@gmail.com](mailto:jonathan.l.marx@gmail.com)

---

# ⭐ If you found this interesting…

Consider starring the repository — it helps visibility and encourages further development!

