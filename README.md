# Facebook Page AI Auto Reply Automation

My first practice project using n8n to automate replies to messages
received on a Facebook Page.

## 📌 Project Overview

This workflow receives incoming Facebook Page messages through a webhook,
processes the message using an AI Agent powered by Google Gemini, and
automatically sends a response back through an HTTP Request.

## 🔄 Workflow

Facebook Page Message
        ↓
     Webhook
        ↓
   Edit Fields
        ↓
     AI Agent
        ↓
  Google Gemini
        ↓
   HTTP Request
        ↓
  Automated Reply

## ⚙️ Workflow Steps

1. Receive the incoming message through a webhook.
2. Extract and prepare the message data.
3. Send the message to an AI Agent.
4. Generate an appropriate reply using Google Gemini.
5. Send the generated response back through an HTTP Request.

## 🛠️ Technologies Used

- n8n
- Webhook
- AI Agent
- Google Gemini
- HTTP Request
- Facebook Page / Messenger API

## 📸 Workflow Screenshot

![Workflow Overview](screenshots/workflow-overview.png)

## 🧪 Project Status

This is my first practice project with n8n and Facebook automation.

I am currently building more Facebook-related automation projects
to improve my workflow automation and AI integration skills.

## 🚀 Future Improvements

- Better AI response handling
- Conversation memory
- Human handoff
- Message logging
- Lead collection
- FAQ automation
- Multiple response scenarios

## ⚠️ Security

API keys, access tokens, passwords, and other credentials are not included
in this repository.

## 👨‍💻 Author

SAMAUN
