# ConfluxAI
Generate Confluence pages from simple notes using AI

# 🚀 ConfluxAI - AI-powered Confluence Knowledge Assistant

> **From scattered Confluence pages to instant answers, summaries, and structured knowledge.**

---

## 💡 Problem

- Every organization’s Confluence is a **mess of pages, PDFs, meeting notes, and documents**.  
- **Search is slow and keyword-based**, often returning irrelevant results.  
- Employees waste valuable hours searching instead of working.  

---

## ✅ Solution

ConfluxAI is an **AI-powered Knowledge Assistant** trained on your Confluence data that can:

1. **Instant Q&A** → Ask natural language questions and get instant answers with references.  
   - *“What’s the escalation process for client downtime?”* → AI provides answer + source page.  
2. **Semantic Search** → Understands meaning, not just keywords.  
3. **Source Linking** → Always cites the original Confluence page for trust.  
4. **Summarization Agent** → Turns long documents into key takeaways.  
5. **Change Alerts** → Sends Slack/Teams updates when pages are modified.  
6. **Multi-Modal Expansion** →  
   - Explains **tables/diagrams** in plain English.  
   - Converts **meeting notes → action items** automatically.  

---

## ⚙️ Tech Stack

- **Data Ingestion**  
  - Confluence REST API  
  - PDF/Text parsers for attachments  

- **Embeddings + Search**  
  - Vector DB: **FAISS / Pinecone / Weaviate**  
  - Frameworks: **LangChain**  

- **LLMs**  
  - OpenAI GPT-4 

- **UI & Integrations**  
  - Confluence sidebar plugin (iframe)  
  - Slack/Teams bot integration  
  - Config dashboard  

---

### Requirements
- Python 3.9+  
- OpenAI API Key (or HuggingFace model)  
- Confluence API Token  

### Setup
```bash
git clone https://github.com/Harithasridhar130/confluxai.git
cd confluxai
pip install -r requirements.txt

# Set environment variables
export OPENAI_API_KEY=your_openai_key
export CONFLUENCE_API_TOKEN=your_confluence_token
