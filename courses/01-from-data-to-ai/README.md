# 01 · From Data to AI: Building the Foundation for Intelligent Business

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harshika-Pareek/ai-training-hub/blob/main/courses/01-from-data-to-ai/From_Data_to_AI_NovaBank.ipynb)

**Course promise:** turn messy financial data into a trustworthy AI assistant, and prove that it works.

## The project: NovaBank Controls Assistant
NovaBank is a fictional bank. Its Global Finance Controls team reviews flagged card transactions and needs an assistant that explains *why* a transaction was flagged and *which policy* applies.

| Step | You'll build | Key lesson |
|---|---|---|
| 1 · Data first | Five data quality checks, and cleaning with a quarantine | Data quality checks are controls |
| 2 · From data to ML | A fraud model, read with precision and recall | 99% accurate can still be useless |
| 3 · From data to GenAI | RAG over policy documents | Bad documents give bad answers |
| 4 · Eval | A test set and a release gate: fail → fix the data → pass | Eval is control testing for AI |
| 5 · Launch | A Gradio chatbot with cited sources | Put it all together |

## Learning objectives
1. Spot the data quality issues that make or break AI
2. Prepare data and read an ML model's results correctly
3. Explain how RAG connects your documents to GenAI
4. Evaluate an AI system before it goes live
5. Launch a simple chatbot on top of your pipeline

## Practical exercise
Add a new policy ("Crypto purchases over €1,000 require review"), write three test questions for it, re-run the eval until it passes, and relaunch the chatbot. Details are at the end of the notebook.

## Requirements
- A Google account (for Colab), or Python 3.10+ locally with `pip install -r ../../requirements.txt`
- Optional: a free Gemini API key. Without one, the notebook still runs and quotes policy text instead of writing answers.

Next course: [02 · AI Agents for Business](../02-ai-agents-for-business)
