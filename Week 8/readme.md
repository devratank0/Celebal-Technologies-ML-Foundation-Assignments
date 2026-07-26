# 🤖 Single AI Agent for Intelligent Task Routing

This repository contains my **Week 8 Machine Learning Foundation assignment** completed as part of the **Celebal Technologies Machine Learning Foundation Internship Program**.

---

# 📌 Project Overview

This project implements a **Single AI Agent** capable of intelligently routing user requests to specialized tools based on the user's intent.

The agent can perform multiple tasks through a unified interface, including mathematical calculations and keyword extraction. By analyzing the user's input, the agent selects the appropriate tool and returns structured JSON responses.

This project demonstrates the fundamental concepts of **AI Agents**, **Intent Recognition**, **Tool Routing**, and **Modular Programming**.

---

# 🎯 Objectives

- Understand the architecture of a Single AI Agent.
- Implement intent-based task routing.
- Build modular tools for different tasks.
- Route user requests to the correct function.
- Handle invalid inputs gracefully.
- Return structured JSON responses.
- Create an interactive AI assistant.

---

# 🛠️ Tools & Libraries Used

- Python
- Google Colab
- Jupyter Notebook
- Regular Expressions (re)
- Math Library

---

# 📂 Repository Structure

```text
Week-8/
│
├── ML_Foundation_Week_8_Single_AI_Agent.ipynb
└── README.md
```

---

# ⚙️ Workflow Followed

1. Import required Python libraries.
2. Build a Calculator Tool.
3. Build a Keyword Extraction Tool.
4. Implement the AI Agent.
5. Detect user intent.
6. Route requests to the appropriate tool.
7. Return structured JSON responses.
8. Test the agent using multiple sample queries.
9. Enable interactive user conversations.

---

# 🏗️ System Architecture

```text
               User Query
                    │
                    ▼
             Intent Detection
                    │
        ┌───────────┴───────────┐
        │                       │
        ▼                       ▼
 Calculator Tool       Keyword Extraction Tool
        │                       │
        └───────────┬───────────┘
                    ▼
            JSON Response Output
```

---

# 📊 Features

- ✅ Mathematical Calculations
- ✅ Keyword Extraction
- ✅ Intent-Based Routing
- ✅ JSON Response Format
- ✅ Error Handling
- ✅ Interactive Chat Mode
- ✅ Modular Design

---

# 📈 Sample Outputs

### Calculator

```python
agent("Calculate 25 + 15")
```

Output

```python
{
    "type": "calculation",
    "query": "Calculate 25 + 15",
    "result": "40"
}
```

---

### Keyword Extraction

```python
agent("Extract keywords from Artificial Intelligence is transforming healthcare.")
```

Output

```python
{
    "type": "keywords",
    "query": "...",
    "result": [
        "artificial",
        "intelligence",
        "transforming",
        "healthcare"
    ]
}
```

---

### General Conversation

```python
agent("Hello")
```

Output

```python
{
    "type": "general",
    "query": "Hello",
    "result": "I can help with calculations and keyword extraction."
}
```

---

# 🎯 Learning Outcomes

This assignment strengthened my understanding of:

- AI Agents
- Intent Recognition
- Tool Routing
- Modular Programming
- Python Functions
- Error Handling
- JSON Response Formatting
- Natural Language Processing (NLP)
- Interactive AI Systems

---

# 🚀 Future Improvements

- Integrate Large Language Models (LLMs).
- Add Sentiment Analysis.
- Support Voice Commands.
- Connect External APIs.
- Develop a Streamlit Web Application.
- Add More AI Tools.
- Implement Multi-Agent Collaboration.

---

# 👨‍💻 Author

**Devratan**

- 🎓 PGDM (Business Analytics & Marketing)
- 🏫 Lloyd Business School
- 💼 Data Scientist – Celebal Technologies

---

# 📝 Note

This project has been developed for **academic submission and learning purposes** as part of the **Machine Learning Foundation Program at Celebal Technologies**.

It demonstrates the implementation of a **Single AI Agent** capable of routing user requests to specialized tools using intent recognition and modular programming principles.
