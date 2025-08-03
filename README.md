# Symptom Classification System

This project uses a language model to classify user-reported medical symptoms into three categories:

- 🟢 General  
- 🔴 Emergency  
- 🟡 Mental Health

It can be integrated into hospital intake systems, AI chatbots, or self-assessment tools to guide users appropriately based on the urgency of their symptoms.

---

## 🚀 Features

- Accepts natural language input describing a symptom
- Classifies symptoms using an LLM (e.g., Gemini / OpenAI)
- Provides appropriate routing to:
  - General consultation
  - Emergency services
  - Mental health counseling

🛠️ Installation

Make sure you’re using Google Colab. Run the following to install dependencies:

```python
!pip install -qU google-generativeai==0.8.5 google-ai-generativelanguage==0.6.15 \
langgraph langchain langchain-google-genai openai
