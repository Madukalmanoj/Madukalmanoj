<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=FF6B6B&center=true&vCenter=true&width=500&lines=Hi+%F0%9F%91%8B%2C+I%27m+Manoj+Madukal;AI+Engineer+%7C+Hackathon+Builder;Crafting+intelligent+systems+that+matter.)](https://git.io/typing-svg)

</div>

---

### 🌌 About Me

***I build real AI systems — from voice agents and trading bots to multimodal GenAI — and share every decision, failure, and lesson along the way.***

🌾 Currently building **FasalShield** — a GenAI-powered multimodal advisor for smallholder farmers in India, fusing satellite imagery, hyper-local weather, and WhatsApp inputs to deliver proactive, regional crop guidance.

📚 Deep-diving into **Transformer architecture** and sharpening **DSA** on [LeetCode](https://leetcode.com/u/madukalmanoj/).

✍️ Writing about AI + Projects on [Medium](https://medium.com/@madukalmanoj).

📫 **[madukalmanoj@gmail.com](mailto:madukalmanoj@gmail.com)** · 

---

### 🚀 Projects

| Project | What it does | Stack |
|---|---|---|
| [**Voice AI Agent**](https://github.com/Madukalmanoj/local-voice-ai-agent) | Local, privacy-first voice agent — speak a command, it transcribes via Whisper, classifies intent with Qwen2.5, and executes local tools. All on-device, no cloud. | Python · Gradio · faster-whisper · Ollama · Qwen2.5 |
| [**CWT Prediction Agent**](https://github.com/Madukalmanoj/cwt-prediction-agent) | Multi-agent system that discovers profitable traders on Polymarket & Kalshi, classifies them by niche, builds a RAG knowledge base, and lets you chat with the data to make follow-trade decisions. Closed learning loop with Bayesian trust updates. | Python · ChromaDB · OpenRouter · APIFY · SQLite · Rich |
| [**Binance Futures Bot**](https://github.com/Madukalmanoj/binance-futures-bot) | CLI + Web UI trading bot for placing Market, Limit, and Stop-Market orders on Binance Futures Testnet. Pydantic v2 validation, HMAC signing, full error handling, and a Streamlit dashboard. | Python · Typer · Streamlit · Pydantic v2 · Binance API |
| 🌾 **FasalShield** *(in progress)* | Proactive crop advisor for smallholder farmers — satellite imagery + hyper-local weather + WhatsApp for regional language guidance. | GenAI · Multimodal · WhatsApp API |

---

### 🔭 Flagship Build — Voice AI Agent

> **Local, privacy-first voice agent. Speak → Transcribe → Classify → Execute. Fully on-device.**

```
Mic / Audio File
      │
      ▼
faster-whisper (base, CPU)   ← STT
      │
      ▼
Ollama qwen2.5               ← Intent Classifier → JSON: intent / filename / description
      │
      ▼
Tool Router                  ← create_file | write_code | summarize | chat | compound
      │
      ▼
Tool Execution               ← ./output/ (path-safe, traversal-protected)
      │
      ▼
Gradio Web UI                ← Result displayed at localhost:7860
```

**What makes it different:**
- 🔒 **100% local** — no API calls, no data leaves your machine
- 🎯 **Intent-aware routing** — LLM classifies intent to structured JSON before tool dispatch
- 🛡️ **Path traversal protection** — `_safe_output_path()` strips directory components and validates absolute paths
- ⚡ **Compound intents** — handles chained commands like "summarize this and save to summary.txt"

---

### 🧠 Skills & Tech Stack

#### ⚙️ Languages & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/linux-%23000000.svg?style=for-the-badge&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

#### 📊 ML & Data Science
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-008080?style=for-the-badge&logoColor=white)

#### 🤖 GenAI & Agentic Systems
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Huggingface-%23FFD21F.svg?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-101010?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Gen-6DB33F?style=for-the-badge&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-Multi--Agent_Systems-FF6B6B?style=for-the-badge&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-Advanced-blueviolet?style=for-the-badge&logoColor=white)

#### 🎙️ Voice AI
![Faster Whisper](https://img.shields.io/badge/Faster--Whisper-STT-FF6B6B?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-FF6B6B?style=for-the-badge)
![Gradio](https://img.shields.io/badge/Gradio-UI-FF6B6B?style=for-the-badge)

#### 🌐 Backend & APIs
![FastAPI](https://img.shields.io/badge/fastapi-005571?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-6DB33F?style=for-the-badge&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

#### 💹 Trading & Market Data
![Binance API](https://img.shields.io/badge/Binance_API-F3BA2F?style=for-the-badge&logo=binance&logoColor=black)
![Polymarket](https://img.shields.io/badge/Polymarket-Prediction_Markets-6DB33F?style=for-the-badge)
![Kalshi](https://img.shields.io/badge/Kalshi-Event_Markets-0066CC?style=for-the-badge)

---

### ✍️ Writing

I write about what I actually build — not rehashed tutorials.

| | Post | Platform |
|---|---|---|
| 🤖 | Articles on AI, ML, and real engineering decisions | [Medium](https://medium.com/@madukalmanoj) |

---

### 📊 GitHub Stats

<div align="center">

![Manoj's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Madukalmanoj&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6B6B&icon_color=FF6B6B)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Madukalmanoj&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6B6B)

![GitHub Streak](https://streak-stats.demolab.com?user=Madukalmanoj&theme=radical&hide_border=true&background=0D1117&ring=FF6B6B&fire=FF6B6B&currStreakLabel=FF6B6B)

</div>

---

### 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manojmadukal/)
[![Portfolio](https://madakalmanoj-portfolio.vercel.app/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@madukalmanoj)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=white)](https://leetcode.com/u/madukalmanoj/)
[![Email](https://img.shields.io/badge/madukalmanoj%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madukalmanoj@gmail.com)

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Madukalmanoj&color=FF6B6B&style=flat-square&label=profile+views" />
  <br><br>
  <i>Open to AI Engineer / ML Engineer / GenAI roles — hackathon warrior, real system builder.</i>
  <br><br>
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
