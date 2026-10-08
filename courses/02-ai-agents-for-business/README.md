# 02 · AI Agents for Business: From Assistants to Autonomous Workflows

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harshika-Pareek/ai-training-hub/blob/main/courses/02-ai-agents-for-business/AI_Agents_NovaBank.ipynb)

**Course promise:** build an AI agent that investigates and acts, safely, and prove it behaves before you trust it.

## The project: NovaBank Fraud Investigator Agent
Given a flagged transaction, the agent decides which tools to use, gathers evidence, and recommends an action. A human approves anything risky. You can start here even if you haven't taken Course 01: the notebook rebuilds everything it needs in its first cell.

## Three lessons

| Lesson | Notebook sections | Key lesson |
|---|---|---|
| 1 · What an agent really is | 0 · Setup, 1 · Tools, 2 · The agent loop | An agent is just a loop around an LLM, with tools |
| 2 · Agents you can trust | 3 · Human in the loop, 4 · Agent eval | AI recommends, a human decides; test the path, not just the answer |
| 3 · Is an agent worth it? | 5 · Add a new tool | Grow agents one tested tool at a time |

Starting a later lesson? Click its first cell, then **Runtime → Run before**.

## Learning objectives
1. Tell an assistant, a workflow and an agent apart, and know when each fits
2. Explain how an agent works: LLM, tools, memory and the loop
3. Design tools and guardrails, including human approval
4. Evaluate an agent on its answers and its actions
5. Decide when an agent is worth building

## Practical exercise
Add an action tool, `send_customer_alert`, choose its risk tier (run freely, log it, or require approval), update the rulebook, add an eval scenario, and re-run until everything passes.

## Requirements
- A Google account (for Colab), or Python 3.10+ locally with `pip install -r ../../requirements.txt`
- Optional: a free Gemini API key. Without one, a **simulated agent** follows the same tools and rules, so every step still runs.

Previous course: [01 · From Data to AI](../01-from-data-to-ai)
