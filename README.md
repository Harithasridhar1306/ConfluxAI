ConfluxAI

Generate Confluence pages from simple notes using AI

- ConfluxAI generates a Confluence page with:  
- Title + sections  
- Tables / lists / links  
- Clean formatting in Confluence storage format  
- Automatically published in the correct space  

---

## ⚙️ Tech Stack

- **Language Model**: GPT-4 (or Claude / Llama 3)  
- **Backend**: Python (FastAPI / Flask)  
- **Integration**: Confluence REST API  
- **Optional UI**:  
- CLI tool (`confluxai create "title" "notes"`)  
- Web app (Streamlit / React)  
- Slack/Teams bot  

---

## 🔑 Features

- ✅ Generate Confluence pages from simple prompts  
- ✅ AI expands notes into structured docs  
- ✅ Auto-publish via Confluence REST API  
- ✅ Supports sections, tables, and references  
- 🔜 Templates (Meeting Notes, Runbooks, Design Docs)  
- 🔜 Slack/Teams integration  

---

## 📦 Requirements

- Python 3.9+  
- OpenAI API Key (or HuggingFace model)  
- Confluence API Token + Space Key  

---

## ⚡ Setup

```bash
# Clone repo
git clone https://github.com/Harithasridhar1306/confluxai.git
cd confluxai

# Install dependencies
pip install -r requirements.txt

# Set environment variables
export OPENAI_API_KEY=your_openai_key
export CONFLUENCE_API_TOKEN=your_confluence_api_token
export CONFLUENCE_BASE_URL=https://yourcompany.atlassian.net/wiki
export CONFLUENCE_SPACE_KEY=DEVOPS
