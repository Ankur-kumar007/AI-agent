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
   
4.
   ![Image](https://github.com/user-attachments/assets/0c75ae8c-6260-48dc-8d77-9bbaad68ccad)
6. ![Image](https://github.com/user-attachments/assets/11d26c45-ae1a-4b97-84c0-82b24e3193f8)
7. ![Image](https://github.com/user-attachments/assets/fd8cfcc8-39ae-4011-9065-6419b25f7527)


## 🛠️ Setup Instructions  
1. **Install n8n** (if not already installed)  
   ```sh
   npm install -g n8n
