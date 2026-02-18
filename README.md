# 🤖 LLM‑Based Agentic Modelling with Langflow

This repository will help you dive into **LLM‑based autonomous agents** even if you have *zero* coding experience. 
The repository provides additional information and hands-on exercises for the **[KIDA Online-Workshop: AI-based autonomous agents - What, why and how?](https://www.kida-bmel.de/veranstaltungen/archiv)**

---
## 📁 Presentation Folder 
- An introduction to LLM‑powered autonomous agents, key components, common challenges, and real‑world use cases.  
-  A concise overview of the most popular frameworks for practical implementation.

---
## 🎛️ Demonstration Stack
We use **[Langflow](https://www.langflow.org/)** 🧩 for all no‑code demonstrations.  
Solutions built in Langflow can later be ported to other frameworks via API calls.

**Ecosystem companions:**
| Purpose | Tool | Link |
|---------|------|------|
| Visual / no‑code prototyping | 🌐 Langflow | https://www.langflow.org/ |
| Programmatic development | 🛠️ LangChain | https://python.langchain.com/ |
| Production monitoring | 📈 LangSmith | https://smith.langchain.com/ |
| Multi‑agent workflows | 🔀 LangGraph | https://github.com/langchain-ai/langgraph |
| LangGraph UI | 🖼️ LangGraph Studio | https://smith.langchain.com/langgraph-studio |

> **Hands‑on note:** All tutorials below assume you are using Langflow.

---
## ☁️ Getting Started — No Installation Needed
1. Head to the **[DataStax Cloud signup](https://www.datastax.com/)** page.  
2. Create a free account.  
3. Launch Langflow directly in your browser—no local setup required!

---
## 🏋️‍♂️ Exercises Overview (Ex 1 – Ex 3)
Langflow saves the flows in json files, featuring the location of the blocks and their content. You need to upload the provided flow to your langflow environment to open it.

### Ex 1 — Memory‑Enabled Chatbot 🧠
Build an agent that **retains** past conversation context and responds coherently.

### Ex 2 — Linked‑Data via Vector RAG 🔗
**Goal:** Create linked‑data for a term in a research paper (Egg_supply_chain.pdf) 
1. **Upload PDF** ➜ chunk ➜ embed ➜ store in a vector DB.  
2. **Ask & Answer**: Use RAG retrieval to answer a user question.  
3. **Generate Links**: Convert the RAG retriever into a tool that matches the term with an external repository (e.g., Wikidata).

**Example scenario:**  
- Paper: *Egg‑Supply Chain in Germany* 
- Task: “Who is the president of the country where the study was conducted?”  
- Steps: Retrieve “Germany” (Part 2) ➜ consult an external data source (Part 3) ➜ return the president’s name.

### Ex 3 — Multi‑Agent Negotiation 🤝
Conduct a single‑round discussion among multiple agents.  
Demonstrates importing a separate RAG flow (e.g. `RAG_1_doc_2.json`) and using it as a tool in another flow.

---
