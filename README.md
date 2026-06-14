<div align="center">

<!-- HERO BANNER — pure GitHub-native SVG, no external service needed -->
<svg width="900" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#161b27"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7c3aed"/>
      <stop offset="100%" style="stop-color:#a78bfa"/>
    </linearGradient>
  </defs>
  <rect width="900" height="160" fill="url(#bg)" rx="12"/>
  <rect x="0" y="148" width="900" height="3" fill="url(#accent)" rx="2"/>
  <text x="50%" y="58" text-anchor="middle" font-family="monospace" font-size="13" fill="#7c3aed" letter-spacing="6">APPLIED AI ENGINEER</text>
  <text x="50%" y="102" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="38" font-weight="700" fill="#f0f6fc">Mohit Singh Bisht</text>
  <text x="50%" y="134" text-anchor="middle" font-family="monospace" font-size="12" fill="#8b949e">RAG Pipelines  ·  Multi-Agent Systems  ·  LLM Evaluation  ·  Workflow Automation</text>
</svg>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohit197)
[![Portfolio](https://img.shields.io/badge/Portfolio-7c3aed?style=for-the-badge&logo=firefox&logoColor=white)](https://mohit-singh-bisht-1yt066p.gamma.site/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahiviru@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=MohitSinghBisht&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)](https://github.com/MohitSinghBisht)

</div>

---

```python
class MohitSinghBisht:
    role     = "Applied AI Engineer @ Coding Ninjas, Gurgaon"
    focus    = ["RAG Pipelines", "LangGraph Agents", "LLM Evaluation", "Workflow Automation"]
    shipped  = 4        # production LLM PoCs, all running in prod
    mantra   = "LLM judges quality. Python computes scores. Never swap these."

    def currently_exploring(self):
        return ["Langfuse", "FastAPI", "Voice AI (STT→LLM→TTS)", "AutoGen / CrewAI"]
```

---

## 🚀 Production LLM PoCs

> *4 systems built from scratch, each solving a real problem, each in production.*

<table>
<tr>
<td valign="top" width="50%">

### 🎙️ React Mock Interview System
**`LangGraph · LangChain · OpenAI · Whisper · Streamlit`**

- **4 LangGraph agents**: Interviewer · Question Generator · Adaptive Logic · Evaluator
- Dynamic difficulty progression: Easy → Medium → Hard within session
- Voice pipeline via Whisper (STT) + GPT-4o-mini (TTS)
- Weighted scoring: difficulty weight × time efficiency − follow-up penalty
- Outputs: **Strong Hire / Hire / No Hire / Strong Reject**

</td>
<td valign="top" width="50%">

### 🎓 Live Class Audit System
**`GPT-4.1 mini · Gemini · Streamlit · Google Sheets`**

- Ingests Zoom VTT transcripts + chat exports automatically
- **5 audit parameters, 14 sub-checks** (behaviour, engagement, content, quality, escalation)
- Architecture decision: LLM → qualitative flags only; **Python owns all score math**
- 5-min response window pre-computed per student message (doubt detection)
- Cost: **~₹2 per audit** via prompt decomposition

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 📄 AI Resume Analyzer
**`Flask · React · GPT-4.1 mini · Netlify · Render`**

- Benchmarks resumes against **300+ Indian DA job listings** across 3 experience tiers
- 5-prompt sequential chain: gap analysis → ATS score → strategy → write → track
- Anti-hallucination guardrails: verbatim title extraction, `current_date`-anchored experience calc
- Deployed: Netlify (frontend) + Render (backend)

</td>
<td valign="top" width="50%">

### 🤖 Sales Counsellor Bot
**`LangChain · Qdrant · HNSW · OpenAI · Streamlit`**

- HNSW indexing: **10–100× faster retrieval** vs. brute-force, 50–70% memory reduction
- Dual-LLM architecture: Instance A (query understanding: intent, nature, language, search query) → Instance B (response generation)
- Score-based retrieval with **≥0.7 similarity threshold**
- Multilingual: English + Hinglish with auto language detection
- Auto lead extraction to CSV for CRM handoff

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**AI / LLM Frameworks**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-7c3aed?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000?style=for-the-badge&logoColor=white)

**Vector Databases & Retrieval**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)
![HNSW](https://img.shields.io/badge/HNSW_Indexing-1e1b4b?style=for-the-badge&logoColor=a78bfa)
![Hybrid Search](https://img.shields.io/badge/Hybrid_Search-4f46e5?style=for-the-badge&logoColor=white)

**Observability & Evaluation**

![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse_(learning)-F97316?style=for-the-badge&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI_(learning)-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**Automation & Infra**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![OpenClaw](https://img.shields.io/badge/OpenClaw_Agent-1e1b4b?style=for-the-badge&logoColor=a78bfa)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=MohitSinghBisht&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9&ring_color=7c3aed&include_all_commits=true&count_private=true" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohitSinghBisht&layout=compact&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=6" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=MohitSinghBisht&theme=dark&hide_border=true&background=0d1117&ring=7c3aed&fire=a78bfa&currStreakLabel=a78bfa&sideLabels=8b949e&dates=8b949e)

</div>

---

## 🧠 Design Principles I Ship By

```
1. Never delegate score math to the LLM — Python owns determinism
2. Cost-aware prompt decomposition before scaling tokens
3. Observability first — if you can't trace it, you can't debug it
4. Anti-hallucination by architecture, not by prompt hoping
5. Production ≠ demo — edge cases, cost per call, and latency all matter
```

---

<div align="center">

<sub>📍 New Delhi / Gurgaon &nbsp;·&nbsp; Open to AI Engineer roles</sub>

</div>
