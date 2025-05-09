# 🧠 Dojo AI — A Collaborative Learning Repository

Welcome to **Dojo AI**, a shared space for curious minds learning and experimenting with Artificial Intelligence. This repository is part study log, part lab, and part project launcher — built by and for members of our study group.

---

## 📚 Study Materials

We’re exploring foundational concepts of modern AI, including LLMs, prompt engineering, embeddings, and agents. These are our core reading materials:

### 🔹 Foundation & Architecture

1. [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) — *Stephen Wolfram*
2. [Foundational Models and Text Generation](https://www.kaggle.com/whitepaper-foundational-llm-and-text-generation) — *Kaggle Whitepaper*
   - [PDF](https://github.com/phoenix0706/5-Day-Gen-AI-Intensive-Course-Kaggle/blob/master/whitepaper_Foundational%20Large%20Language%20models%20%26%20text%20generation.pdf)

### 🔹 Prompt Engineering

3. [Prompt Engineering](https://www.kaggle.com/whitepaper-prompt-engineering) — *Kaggle Whitepaper*

### 🔹 Embeddings & Retrieval

4. [Embeddings and Vector Stores](https://www.kaggle.com/whitepaper-embeddings-and-vector-stores) — *Kaggle Whitepaper*

### 🔹 Agents & Tool Use

5. [Agents](https://www.kaggle.com/whitepaper-agents) — *Kaggle Whitepaper*
6. [Agent Companion](https://www.kaggle.com/whitepaper-agent-companion) — *Kaggle Whitepaper*

---

## 🗂️ Repository Structure

```
dojo-ai/
├── README.md              # Overview and how to get started
├── .gitignore
├── meetings/              # Session notes and topics covered
│   └── 2025-05-08.md
├── concepts/              # Code experiments to understand theories
│   ├── transformers/
│   ├── prompt-engineering/
│   └── agents/
├── projects/              # Group-built projects
│   ├── ai-chatbot/
│   └── document-summarizer/
├── resources/             # External references
│   ├── papers/
│   ├── videos/
│   └── summaries/
└── contributors.md        # List of members and their contributions
```

---

## ⚙️ Getting Started with `uv` (Python Dependency Manager)

We use [`uv`](https://github.com/astral-sh/uv) to manage Python dependencies faster and cleaner.

### ✅ Prerequisites:

* Python 3.8+
* `curl` or `pipx`

### 🔽 Install `uv`

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
```

Or with pipx:

```bash
pipx install uv
```

### 🏁 Start a Project:

```bash
uv venv ai-dojo-group   # Create a virtual environment
source ai-dojo-group/bin/activate # Activate it (Linux/macOS)
uv pip install numpy openai # Example install
uv pip freeze > requirements.txt  # Save environment
```

### 📌 Lock Environment (Like `poetry` or `pipenv`)

```bash
uv pip install -r requirements.txt
uv pip compile       # Creates a uv.lock file for reproducibility
```

---

## 🙌 Contributing

* Fork this repo
* Create a branch with your topic or feature
* Submit a PR

Use clear commit messages (`feat`, `fix`, `docs`, etc.) and always keep your code inside the right folder (`concepts/`, `projects/`, `resources/`).

---

Let’s learn, build, and grow together. 💥
