# 🤖 AI Agent Hackathon Project – AI-Powered Payment Reminder (n8n)

This is our **AI Agent Hackathon** project — an intelligent, voice-enabled, **multi-language payment reminder assistant** built in [n8n](https://n8n.io/).  
It uses **Google Gemini AI**, **sentimental analysis**, and **VAPI Dashboard** integration to deliver friendly, human-like payment reminders over phone calls.

---

## 👥 Team Members

| Member | Profile |
|--------|---------|
| 🧑‍💻 Yuvarrunjitha R S | ![Profile Pic](./team/name1.jpg) |
| 🧑‍💻 Vijey Abinesh |![Profile Pic](./team/name2.jpg) |
| 🧑‍💻 Srinidhi N | ![Profile Pic](./team/name3.jpg) |
| 🧑‍💻 Varshini R |  ![Profile Pic](./team/name4.jpg) |
| 🧑‍💻 Hemalatha | ![Profile Pic](./team/name4.jpg) |

---

## 🚀 Features
- **Webhook Trigger**: Accepts incoming payment reminder requests from external systems.
- **AI Conversation Agent**: Uses Google Gemini to generate friendly and human-like responses.
- **Multi-Language Support**: Communicates in multiple languages based on customer preferences.
- **Event Scheduling**: Automatically creates calendar events for payment due dates.
- **Sentimental Analysis**: Detects customer tone (Positive / Neutral / Negative) and adjusts response style accordingly.
- **AWS Lambda Integration**: Handles custom payment logic and backend processing.
- **Dynamic Message Routing**: Uses conditional nodes to personalize messages per customer.
- **VAPI Voice Calls**: Integrated via **VAPI Dashboard** to initiate natural-sounding, AI-powered live calls.
- **Webhook Response**: Sends final confirmation/status back to the originating system.

---

## 🛠 Workflow Structure
1. **Webhook** – Receives payment reminder trigger.
2. **AWS Lambda** – Executes custom backend logic for payment processing.
3. **AI Agent (Google Gemini)** – Generates conversational responses.
4. **Google Calendar** – Creates payment due events.
5. **Sentimental Analysis** – Detects customer tone and routes workflow accordingly:
   - **Positive Tone** → Friendly confirmation message.
   - **Neutral Tone** → Standard reminder.
   - **Negative Tone** → More empathetic, understanding message.
6. **Conditional Logic (IF Nodes)** – Branches workflow based on sentiment result.
7. **Edit Fields Nodes** – Prepares personalized message content.
8. **VAPI Call via Dashboard** – Places multi-language AI-powered voice calls.
9. **Respond to Webhook** – Returns final status or confirmation to the original source.

---

## 📦 Integrations
- **Google Gemini Chat Model** (Conversational AI & Multi-language)
- **Google Calendar API** (Event Scheduling)
- **AWS Lambda** (Backend Logic)
- **VAPI.ai Dashboard** (Voice AI Integration)

---

## 📋 Setup Instructions
1. Install [n8n](https://docs.n8n.io/getting-started/installation/) locally or on a server.
2. Create API keys for:
   - Google Gemini
   - Google Calendar
   - AWS Lambda
   - VAPI Dashboard
3. Import this workflow JSON into n8n.
4. Configure environment variables or credentials for each service.
5. Activate the workflow.


---

## 🖼 Workflow Preview

---

## 🖼 Workflow Preview
<img width="1489" height="592" alt="image" src="https://github.com/user-attachments/assets/2362e23b-5eaf-4710-a92e-b50943da58b0" />


---

## 📜 License
This project is licensed under the MIT License.


---

## 📜 License
This project is licensed under the MIT License.




