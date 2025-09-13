#  My Automation Portfolio (n8n + AI)

Welcome to my collection of **automation workflows** built using **n8n**, **AI models**, and other tools.  
These workflows show how I experiment with **local AI hosting, bots, and productivity automations** — all cost-free and self-contained.

---

## 🔹 1. AI Playground Chatbot

- **Tools:** n8n + LM Studio + Mistral-7B  
- **Description:** Connects n8n to a local AI model (Mistral-7B Instruct) running in LM Studio.  
- **How it works:**  
  1. A Set node stores the user prompt.  
  2. An HTTP Request sends the prompt to `http://localhost:1234/v1/chat/completions`.  
  3. The response is captured back into n8n.  

- **Features:**  
  - Fully offline, no API costs.  
  - Custom headers + JSON body integration.  
  - Can be extended into bots (Slack, Telegram, WhatsApp).  

- **Download Workflow:**  
  [📥 ai-playground.json](./ai-playground.json)

---

## 🔹 2. (Coming Soon) Finance Tracker Bot

- **Tools:** n8n + WhatsApp API + Google Sheets  
- **Description:** A bot that logs daily spending and returns weekly finance summaries.  
- **Status:** In progress.  

---

## 🔹 More Projects Coming Soon…
- Messaging bots  
- Research agents  
- Creative automation tools  

---

### ⚡ Why this matters
By hosting AI locally and connecting it with n8n, I can:  
- Build **autonomous AI agents** step by step.  
- Automate tasks without depending on paid API keys.  
- Share workflows as templates for anyone to try.

---

### 📂 How to Use
1. Clone/download this repo.  
2. Import the JSON into your local n8n instance.  
3. Adjust nodes as needed (model name, prompts, or integrations).  

---

💡 **Follow my journey:** I’ll keep adding workflows here as I expand into bots, research assistants, and more.
