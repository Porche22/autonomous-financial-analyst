# Autonomous Financial Analyst

> **Category:** Agentic AI &nbsp;·&nbsp; **Type:** Jupyter notebook project

## Overview

* * *

###  **# Important Points To Note** 

  1. For LLM please use **`"gpt-4o-mini"`** model.
  2. You need to look for **`"<--- 🧩🧩🧩 Your Code Goes Here 🧩🧩🧩 --->"`** and add your code over there, this is a placeholder.
  3. For project submission, please provide the project in **HTML format.** Refer to the **"Guidelines: Converting IPYNB to HTML Files.pdf"** for instructions.
  4. Ensure all **outputs are clearly visible,** and enclose prompts in triple quotes **`"""`** so they remain fully visible when the notebook is converted from IPYNB to HTML.



* * *

#  📊 **Autonomous Financial Research Analyst - Part 1**

**Defining the Agent's Charter with LangChain/LangGraph**

##  **Business Problem - Intelligent Investment Research Automation**

## Project deep dive

This repository contains a complete, end-to-end notebook for **Autonomous Financial Analyst**.
It walks through the full workflow — from framing the problem and exploring the
data, through modeling and evaluation, to the conclusions and recommendations.

- **35 code steps** of analysis and modeling
- Full outputs, tables, and visualizations preserved in the rendered HTML
- A runnable `notebook.ipynb` so you can re-execute and extend the work

## Tech stack

`google-generativeai`, `langchain-community`, `langchain-core`, `langchain-openai`, `langchain_text_splitters`, `langgraph`, `yfinance`, `zipfile`

## What's in this repo

| File | Description |
|------|-------------|
| [`notebook.ipynb`](notebook.ipynb) | The runnable notebook (code recovered from the original export) |
| [`autonomous-financial-analyst.html`](autonomous-financial-analyst.html) | Full rendered notebook with **all outputs & plots** preserved |
| `requirements.txt` | Python dependencies inferred from the notebook |

## View the notebook

GitHub renders `.ipynb` files inline — just open [`notebook.ipynb`](notebook.ipynb).
For the fully-rendered version with every saved output and figure:

- **Rendered notebook (nbviewer):** https://nbviewer.org/github/Porche22/autonomous-financial-analyst/blob/main/notebook.ipynb
- **Rendered HTML export:** https://htmlpreview.github.io/?https://github.com/Porche22/autonomous-financial-analyst/blob/main/autonomous-financial-analyst.html

> Replace `Porche22` with your GitHub username after pushing.

## Run it locally

```bash
git clone https://github.com/Porche22/autonomous-financial-analyst.git
cd autonomous-financial-analyst
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

<sub>Notebook reconstructed from an nbconvert HTML export; code cells recovered
faithfully, rich outputs are preserved in the accompanying `.html`.</sub>
