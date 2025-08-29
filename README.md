# Agent Experiments

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Status](https://img.shields.io/badge/Status-Experimental-orange)]()  

This repository contains experiments with AI agents, RAG pipelines, and health research prototypes.  
It’s part of my learning process for building **TRIAGE**, a solution-focused AI coaching agent.  

---

## 🚀 Features
- `app.py` – main entry point to run the app
- Environment management with `.venv` and `requirements.txt`
- Configurable via `.env` file (not tracked in Git)

---

## 🛠️ Setup

### 1. Clone the repo
```bash
git clone https://github.com/<your-username>/agent-experiments.git
cd agent-experiments
````

### 2. Create & activate a virtual environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1   # Windows (PowerShell)
# or
source .venv/bin/activate      # macOS/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add environment variables

Create a `.env` file in the root (not committed to Git). Example:

```
OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Running the App

```bash
python app.py
```

---

## 📂 Project Structure

```
agent-experiments/
│── app.py
│── requirements.txt
│── README.md
│── .gitignore
│── me/              # personal or experimental agent code
```

---

## 📌 Notes

* This is an experimental repo for testing AI agent setups.
* Not production-ready — for exploration & learning.

