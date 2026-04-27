# 3. AI Auto-Reply Customer Support Bot
### n8n + Groq AI + Email/Webhook

## What It Does
When a customer sends a message or inquiry, this workflow:
- Receives the message via webhook or email
- Sends it to an AI model with a custom business prompt
- Automatically replies with a professional, context-aware response
- Logs the conversation to Google Sheets

**Use cases:** Clinics answering appointment questions, gyms replying to membership inquiries, e-commerce support, service businesses

## Workflow
```
Webhook (incoming message) → Groq AI (generate reply) → Send Auto-Reply (Email/API) → Log to Sheets
```

## Setup
1. Import `workflow.json` into n8n
2. Add your Groq API key
3. Edit the system prompt to match YOUR business (name, services, FAQs)
4. Connect email or your messaging platform
5. Activate

## Customization
Edit the system prompt in the AI node to define:
- Business name and services
- Tone (formal / friendly)
- FAQs to answer automatically
- When to escalate to human support

## Tools
- [n8n](https://n8n.io) · [Groq API](https://groq.com) · Google Sheets

---
Built by **Fatma Mohamed** — Business Automation Specialist | [LinkedIn](https://linkedin.com/in/fatmamohamed-remot)