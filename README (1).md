# 🛠️ Blueprint Bot  

**Blueprint Bot** is an AI-powered coding assistant built by **Gauri Nigam**, a third-year B.Tech student.  
Developed using [LangGraph](https://github.com/langchain-ai/langgraph), it works like a multi-agent development team that takes natural language prompts and turns them into complete, working projects — file by file — using real developer workflows.  

---

## 🧩 Overview  
Blueprint Bot acts as a **virtual coding partner**, simplifying the process of building software through automation. It understands user requirements, plans the structure, generates files, and writes production-level code autonomously.  

---

## 🏗️ Architecture  
- **Planner Agent** – Analyzes your request and creates a detailed project plan.  
- **Architect Agent** – Breaks down the plan into engineering tasks with proper file context.  
- **Coder Agent** – Implements tasks, writes directly into files, and uses standard developer tools.  

<div style="text-align: center;">
    <img src="resources/coder_buddy_diagram.png" alt="Blueprint Bot Architecture" width="90%"/>
</div>

---

## 🚀 Getting Started  

### Prerequisites  
- Install **uv** following [these instructions](https://docs.astral.sh/uv/getting-started/installation/).  
- Create a **Groq account** and generate your API key [here](https://console.groq.com/keys).  

---

### ⚙️ **Instsllstion and Startup**
- Create a virtual environment using: `uv venv` and activate it using `source .venv/bin/activate`
- Install the dependencies using: `uv pip install -r pyproject.toml`
- Create a `.env` file and add the variables and their respective values mentioned in the `.sample_env` file

Now that we are done with all the set-up & installation steps we can start the application using the following command:
  ```bash
    python main.py
  ```

### 🧪 Example Prompts
- Create a to-do list application using html, css, and javascript.
- Create a simple calculator web application.
- Create a simple blog API in FastAPI with a SQLite database.

---
Copyright©️ Codebasics Inc. All rights reserved.
