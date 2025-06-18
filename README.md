# AI-Chatbot
# 🤖 AI Chatbot using n8n

A no-code AI chatbot built using **n8n**, **Groq Chat Model**, and **SerpAPI**, capable of answering real-time questions such as stock prices.

## 🚀 Features
- Chat-based interface triggered on incoming messages
- Real-time data retrieval using SerpAPI
- Natural language responses powered by Groq LLM
- Session memory using Simple Memory node

## 🛠️ Tools & Technologies
- n8n
- Groq Chat Model
- SerpAPI
- Webhooks
- No-code automation

## 🖼️ Preview
(http://localhost:5678/webhook/16f7959e-117d-4636-84a5-d39eb1243c4e/chat)

## ⚙️ How It Works
1. User sends a chat message (e.g., "current stock price of Tesla")
2. The chatbot uses Groq to interpret the query
3. SerpAPI fetches real-time data
4. A reply is sent instantly

## 🧠 Workflow File
You can import `workflow.json` into your n8n instance to try it out.

## 🌐 Live Demo
> Currently hosted locally. Public link available on request.

## 📁 Setup Instructions
> You must have n8n running locally or via Docker.

1. Open your n8n instance
2. Import the `workflow.json` file
3. Start the workflow and test via webhook/chat input

---

**Made by [Atul kr Prasad]**
