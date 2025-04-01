# AI-agent

# 🤖 AI Chatbot Workflow for n8n

This repository contains an **AI-powered chatbot workflow** created in **n8n**, utilizing multiple tools to process user queries intelligently.

## 🚀 Features  
- **AI Agent (Tools Agent)** – Acts as the central processor, handling user queries.  
- **OpenAI Chat Model** – Generates intelligent responses using GPT.  
- **Simple Memory** – Stores conversation history for context-aware responses.  
- **SerpAPI** – Fetches real-time search results from Google.  
- **Calculator** – Performs mathematical calculations.  
- **Trigger on Chat Message** – The workflow starts when a chat message is received.  

## 📂 Workflow Overview  
1. A **chat message is received** as input.  
2. The **AI Agent** processes the message using:  
   - **OpenAI Chat Model** for responses.  
   - **Simple Memory** to retain previous interactions.  
   - **SerpAPI** for online searches.  
   - **Calculator** for mathematical queries.  
3. The system **returns a relevant response** based on the query type.  

## 🛠️ Setup Instructions  
1. **Install n8n** (if not already installed)  
   ```sh
   npm install -g n8n
