---
title: career_conversation
app_file: app.py
sdk: gradio
sdk_version: 5.34.2
---
🧠 Career Digital Twin Alter Ego


An AI-powered career agent that represents me in a professional conversation. It uses Gemini 2.0 Flash, OpenAI SDK, and Gradio to simulate a digital twin that can answer questions about my background, experience, and skills — as if you were chatting with me directly.

Key features:

📄 Reads my resume (PDF) and career summary to form contextual memory

💬 Responds to career-related questions in a friendly, professional tone

📱 Sends real-time mobile notifications via Pushover:

When a user provides contact info (email/name)

When it encounters a question it cannot answer

🛠️ Uses function-calling to handle tools like record_user_details and record_unknown_question

🚀 Deployed with Gradio and Hugging Face Spaces

This project demonstrates my ability to build real-time, agentic AI tools with API integration, prompt engineering, and deployment on production-ready platforms.


and Next ?
  
improve the resources - add better context about yourself. If you know RAG, then add a knowledge base about you.
Add in more tools! You could have a SQL database with common Q&A that the LLM could read and write from?
Bring in an Evaluator and add other Agentic patterns.

