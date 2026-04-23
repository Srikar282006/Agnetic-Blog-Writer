# 📝 AI Blog Writer with LangGraph + Multi-Agent Pipeline

An advanced AI-powered blog generation system built using **LangGraph**, **LangChain**, and **LLMs**.  
This project dynamically generates high-quality technical blogs using a **multi-agent workflow** with optional research and automatic image generation.

---

## 🚀 Features

- 🔀 **Smart Routing System**
  - Decides whether research is required (`closed_book`, `hybrid`, `open_book`)

- 🔍 **Automated Research (Tavily API)**
  - Fetches real-time evidence for up-to-date blogs

- 🧠 **Multi-Agent Architecture**
  - Planner (Orchestrator)
  - Section Writers (Workers)
  - Reducer (Merges content + images)

- 🖼️ **AI Image Generation**
  - Generates diagrams using Gemini API
  - Inserts images automatically into blog

- 📄 **Structured Blog Output**
  - Markdown format
  - Clean sections
  - Optional citations


### 🔹 Components

| Component        | Description |
|-----------------|------------|
| Router          | Decides research mode |
| Research        | Fetches evidence using Tavily |
| Orchestrator    | Creates blog plan |
| Worker Nodes    | Generate sections |
| Reducer         | Merges + adds images |

---

## 🧩 Tech Stack

- **LangGraph**
- **LangChain**
- **OpenAI (ChatOpenAI)**
- **Tavily Search API**
- **Google Gemini (Image Generation)**
- **Pydantic**
- **Python 3.10+**

---

## 📦 Installation

```bash
git clone https://github.com/your-username/ai-blog-writer.git
cd ai-blog-writer

pip install -r requirements.txt

#running
# step1 in terminal 1 -python backend.py
# step2 in terminal 2 - python frontend.py

