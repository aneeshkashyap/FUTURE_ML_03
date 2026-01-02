# FUTURE_ML_03

# Customer Support Chatbot using Dialogflow & Flask

## 📌 Project Overview
This project implements a customer support chatbot capable of handling common user queries such as order tracking, refunds, cancellations, and account-related issues. The chatbot is built using Dialogflow for intent classification and a Python Flask webhook for backend logic.

The system demonstrates real-time intent handling, fallback management, and webhook integration, similar to customer support bots used in e-commerce platforms.

---

## 🛠️ Tech Stack
- Dialogflow (Intent Classification)
- Python (Flask Webhook)
- Ngrok (Public Webhook Exposure)
- Google Colab (Development & Testing)
- (Optional) ChatGPT API for intelligent fallback handling

---

## 🧠 Architecture
User Query → Dialogflow → Flask Webhook → Response to Dialogflow

- Known queries are handled using intent-based logic
- Unknown queries are routed through a fallback mechanism
- The webhook processes requests dynamically and returns responses

---

## 📂 Features
- Intent-based customer query handling
- Default fallback intent for unmatched queries
- Webhook integration using Flask
- Live testing using ngrok
- Modular and extendable backend logic

---

## 🧪 Sample Intents
- Track Order
- Cancel Order
- Refund Request
- Account Help
- Default Fallback Intent

---

## 📸 Screenshots
![WhatsApp Image 2026-01-02 at 7 41 33 PM](https://github.com/user-attachments/assets/81646386-d079-4cf6-a5e6-91098a4c0b8c)
![WhatsApp Image 2026-01-02 at 7 42 12 PM](https://github.com/user-attachments/assets/5e717724-5592-41b6-a8d7-a7945e7b21f7)
![WhatsApp Image 2026-01-02 at 7 42 40 PM](https://github.com/user-attachments/assets/feec991c-425f-4875-94ee-5747c75af458)


---

## 🚀 How to Run
1. Create a Dialogflow agent and define intents
2. Configure webhook fulfillment with the ngrok URL
3. Run the Flask server
4. Test queries using Dialogflow’s test console

---

## 📈 Learning Outcomes
- Conversational AI design
- Backend API integration
- Webhook debugging and deployment
- Real-world chatbot architecture

---

## 📌 Note
ChatGPT integration is included as an optional enhancement for handling open-ended queries and depends on API availability.

