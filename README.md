# 🤖 AI Agent Hackathon Project – AI-Powered Payment Reminder (n8n)

This is our **AI Agent Hackathon** project — an intelligent, voice-enabled, **multi-language payment reminder assistant** built in [n8n](https://n8n.io/).  
```It uses Google Gemini AI, sentiment analysis, and VAPI Dashboard integration to deliver friendly, human-like payment reminders over the phone.```

![image](https://camo.githubusercontent.com/525201e24fcf0d7d87f167b8f972bf33242f0588d8bb426b7df5e2911bcc609a/68747470733a2f2f7777772e616e696d61746564696d616765732e6f72672f646174612f6d656469612f3536322f616e696d617465642d6c696e652d696d6167652d303138342e676966)

## 👥 Team Members

| Members |
|--------|
| [Yuvarrunjitha R S](https://github.com/2024yuva) |
| [Vijey Abineesh](https://github.com/VijeyAbinessh) |
| [Srinidhi N](https://github.com/srinidhi31-max) | 
| [Varshini R](https://github.com/Varshinirajesh) | 
| [Hemalatha](https://github.com/hema027) | 

![image](https://camo.githubusercontent.com/525201e24fcf0d7d87f167b8f972bf33242f0588d8bb426b7df5e2911bcc609a/68747470733a2f2f7777772e616e696d61746564696d616765732e6f72672f646174612f6d656469612f3536322f616e696d617465642d6c696e652d696d6167652d303138342e676966)

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

![image](https://camo.githubusercontent.com/525201e24fcf0d7d87f167b8f972bf33242f0588d8bb426b7df5e2911bcc609a/68747470733a2f2f7777772e616e696d61746564696d616765732e6f72672f646174612f6d656469612f3536322f616e696d617465642d6c696e652d696d6167652d303138342e676966)

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

![image](https://camo.githubusercontent.com/525201e24fcf0d7d87f167b8f972bf33242f0588d8bb426b7df5e2911bcc609a/68747470733a2f2f7777772e616e696d61746564696d616765732e6f72672f646174612f6d656469612f3536322f616e696d617465642d6c696e652d696d6167652d303138342e676966)

## 🖼 Workflow Preview
<img width="1489" height="592" alt="image" src="https://github.com/user-attachments/assets/2362e23b-5eaf-4710-a92e-b50943da58b0" />

[🎥 Watch the Payment Reminder Agent Demo](https://drive.google.com/file/d/19qe7LxflVIRCM2pcM_p8-bCUMjs4ArPt/view?usp=sharing)


---


## Multi-lang support

Our AI Payment Reminder Agent supports multiple languages for text and voice interactions.
Using ElevenLabs, we dynamically generate natural, human-like speech in the customer's preferred language, making communication smooth and personalised.

How It Works:
Language Detection – The system detects the user’s preferred language or takes manual input.

Text Translation – Payment reminder messages are translated into the target language.

Voice Synthesis – ElevenLabs converts the translated text into high-quality speech.

![image](https://camo.githubusercontent.com/525201e24fcf0d7d87f167b8f972bf33242f0588d8bb426b7df5e2911bcc609a/68747470733a2f2f7777772e616e696d61746564696d616765732e6f72672f646174612f6d656469612f3536322f616e696d617465642d6c696e652d696d6167652d303138342e676966)


🙌 Thanks, Team!
Huge shout-out to my awesome teammates — thanks for the brainstorming sessions, late-night fixes, and all the laughs along the way. Couldn’t have pulled this off without your energy, support, and dedication! 🚀💙


