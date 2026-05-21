<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=Bhumika%20Bahuguna&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Backend%20%26%20AI%20Systems%20%7C%20CSE%20Undergrad%20%7C%20Building%20Things%20That%20Work&descAlignY=58&descSize=15"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Backend+%2B+AI+systems+from+scratch+%F0%9F%94%A7;Compiler+builder+%7C+LLM+pipelines+%7C+FastAPI+%F0%9F%9A%80;Currently+learning+Agentic+AI+%26+MCP+%F0%9F%A4%96;Open+to+Summer+Internships+%E2%9C%85" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=BhumikaBahuguna&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" />
<img src="https://img.shields.io/github/followers/BhumikaBahuguna?label=Followers&style=flat-square&color=0e75b6" alt="Followers" />

</div>

---

## About Me

I'm a third-year CSE undergrad who builds backend systems and AI pipelines.

Most of what I build falls into one of two categories: things that handle data well at scale, and things that make AI actually useful rather than just impressive. Lately those two categories keep overlapping.

I wrote a source-to-source compiler from scratch (Lexer → Parser → Semantic Analyzer → Code Gen) because I wanted to understand what happens between the code you write and the code that runs. I built an AI productivity manager because I kept using bad ones. I'm currently learning **agentic AI and MCP pipelines** because that's where the interesting backend problems are going to be.

**What I'm open to:**
Summer 2025 internships in backend engineering, AI/ML systems, or full-stack roles. Remote-friendly. Also open to open source contributions on projects I find interesting.

<p>
  <a href="https://www.linkedin.com/in/bhumika-bahuguna-6b068a306" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:bhumika.bahuguna@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://bhumikabahuguna.github.io/My_Portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
</p>

---

## Projects

These are the three I'm most proud of right now. Each one taught me something the textbooks didn't cover.

---

### FinishIt — AI Productivity Manager

A task and habit manager with an actual brain behind it. Not just a to-do list wrapper around an LLM — the AI assistant has full context of your tasks, habits, and matrix state before it says anything.

**The interesting part:** Eisenhower Matrix prioritization running in real time on a React + Supabase architecture, with Google Calendar bidirectional sync. JWT auth, protected routes, and the AI runs on Groq (LLaMA 3) with a structured system prompt built fresh from user data each session.

`React 18` · `Vite` · `Supabase (PostgreSQL + GoTrue)` · `Groq API / LLaMA 3` · `Google Calendar API`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BhumikaBahuguna)

---

### Notes Summarizer — OCR + LLM Study Pipeline

Upload a photo of your handwritten notes. Get back flashcards, concept maps, quizzes, and a cheat sheet. Stateless and privacy-first — nothing touches a database.

**The interesting part:** Azure Document Intelligence handles primary OCR with PaddleOCR as fallback. Summarization uses a parallel racing strategy — Groq and Gemini both process simultaneously and the first valid response wins. This masks latency spikes without paying for a single provider's worst-case timing. A regex pre-filter strips OCR artifacts before any LLM sees the text, saving tokens and preventing hallucinations on garbage input.

`FastAPI` · `React` · `Tailwind CSS` · `Azure Document Intelligence` · `PaddleOCR` · `Gemini` · `Groq` · `Mermaid.js`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BhumikaBahuguna)

---

### Source-to-Source Compiler (Python → C / C++)

A full transpiler built from scratch in Python — no parsing libraries, no shortcuts. Translates Python code to C and C++ through every stage a production compiler runs.

**The interesting part:** Python's semantic whitespace is the hard problem. I solved it with an indent stack that emits `INDENT`/`DEDENT` tokens, letting the parser treat indentation identically to `{}` blocks. The two-pass semantic analyzer maps all globals in pass one, then validates types and scope in pass two. A behavioral validator compiles the generated C/C++ with GCC and diffs its output against the original Python execution to verify correctness. Every stage is visualized in a Flask web UI.

**What I learned:** A language-neutral AST is the key insight — once source is parsed into standardized nodes (`IfStmt`, `ForRangeStmt`, `BinaryOp`), the code generator doesn't need to know the origin language. I'd never have understood that from a textbook.

`Python 3.8+` · `Flask` · `Vanilla JS` · `GCC / G++`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BhumikaBahuguna)

---

## Tech Stack

Things I've actually used in the projects above.

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![REST](https://img.shields.io/badge/RESTful_APIs-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### AI / ML
![LLMs](https://img.shields.io/badge/LLMs_(Groq%2FGemini)-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white)
![OCR](https://img.shields.io/badge/OCR_(Azure%2FPaddleOCR)-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

### Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## GitHub Stats

<div align="center">

  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=BhumikaBahuguna&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BhumikaBahuguna&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=BhumikaBahuguna&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=BhumikaBahuguna&theme=tokyo-night&hide_border=true&area=true" />
</div>

---

## Currently Learning

- **Agentic AI** — multi-step AI workflows that actually do something end-to-end
- **MCP (Model Context Protocol)** — building tools that connect LLMs to real systems
- **System Design** — preparing for internship interviews; focusing on distributed systems patterns

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=BhumikaBahuguna&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=1" />
</div>

---

<div align="center">

**Open to internships, collaborations, and interesting problems.**

*bhumika.bahuguna@gmail.com*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>
