# 🧠 DigestIQ
AI-powered news intelligence — summarize, categorize & analyze any article instantly.

## What it does
- **Summary** — 3-sentence summary of any article
- **Category** — Auto-classifies into Tech, Health, Business, Politics etc.
- **Sentiment** — Positive / Negative / Neutral detection
- **Key Takeaway** — Single most important insight extracted

## Tech stack
Python · Streamlit · Groq API · Llama 3.3 70B · newspaper3k

## Setup
```bash
pip install streamlit groq newspaper3k lxml[html_clean]
```
Add your Groq API key to `.streamlit/secrets.toml`:
