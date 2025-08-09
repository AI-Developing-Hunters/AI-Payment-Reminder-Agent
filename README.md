# AI-Payment-Reminder-Agent

# 📞 AI-Powered Payment Reminder Workflow (n8n)

This project is an **AI-based payment reminder assistant** built in [n8n](https://n8n.io/) that integrates sentiment analysis, conversational AI, and voice calling to automate friendly payment reminders.

---

## 🚀 Features
- **Webhook Trigger**: Accepts incoming payment reminder requests from external systems.
- **AI Conversation Agent**: Uses Google Gemini to generate friendly and human-like responses.
- **Event Scheduling**: Automatically creates calendar events for due dates.
- **Sentiment Analysis**: Analyzes customer tone to adjust communication style.
- **AWS Lambda Integration**: Handles custom payment logic and data processing.
- **Dynamic Message Routing**: Uses conditional nodes to personalize messages.
- **VAPI Voice Calls**: Initiates live calls to customers with conversational AI.
- **Webhook Response**: Sends final confirmation/status back to the source system.

---

## 🛠 Workflow Structure
1. **Webhook** – Receives payment reminder trigger.
2. **AWS Lambda** – Executes custom backend logic.
3. **AI Agent (Google Gemini)** – Generates conversational responses.
4. **Google Calendar** – Creates payment due events.
5. **Sentiment Analysis** – Detects customer tone (Positive/Neutral/Negative).
6. **Conditional Logic (IF Nodes)** – Branches communication based on sentiment.
7. **Edit Fields Nodes** – Prepares personalized message data.
8. **VAPI Call** – Places AI-powered voice calls.
9. **Respond to Webhook** – Returns final response to the original request.

---

## 📦 Integrations
- **Google Gemini Chat Model**
- **Google Calendar API**
- **AWS Lambda**
- **VAPI.ai** (Voice AI Platform)

---

## 📋 Setup Instructions
1. Install [n8n](https://docs.n8n.io/getting-started/installation/) locally or on a server.
2. Create API keys for:
   - Google Gemini
   - Google Calendar
   - AWS Lambda
   - VAPI
3. Import this workflow JSON into n8n.
4. Configure environment variables or credentials for each service.
5. Activate the workflow.

---

## 🖼 Workflow Preview
<img width="1429" height="484" alt="image" src="https://github.com/user-attachments/assets/dfc6b8b2-a5c6-4ac6-9419-ab04bbbf840b" />


---

## 📜 License
This project is licensed under the MIT License.


