<div align="center">

<h1>👋 Hi, I'm Bhumika Bahuguna</h1>

<p><strong>Backend &amp; AI Systems · CSE Undergrad · Building Things That Work</strong></p>

<!-- Typing SVG - reliable external service -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=20&amp;duration=3000&amp;pause=1000&amp;color=00D9FF&amp;center=true&amp;vCenter=true&amp;width=600&amp;lines=Backend+%2B+AI+systems+from+scratch;Compiler+builder+%7C+LLM+pipelines+%7C+FastAPI;Currently+learning+Agentic+AI+%26+MCP;Open+to+Summer+Internships" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=BhumikaBahuguna&amp;label=Profile%20Views&amp;color=0e75b6&amp;style=flat-square" alt="Profile views" />
<img src="https://img.shields.io/github/followers/BhumikaBahuguna?label=Followers&amp;style=flat-square&amp;color=0e75b6" alt="Followers" />

</div>

---

## About Me

I'm a third-year B.Tech CSE student at **Graphic Era Deemed to be University** (graduating June 2027) who builds backend systems and AI pipelines.

Most of what I build falls into one of two categories: things that handle data well at scale, and things that make AI actually useful rather than just impressive. Lately those two categories keep overlapping.

I wrote a source-to-source compiler from scratch (Lexer → Parser → Semantic Analyzer → Code Gen) because I wanted to understand what happens between the code you write and the code that runs. I built an AI productivity manager because I kept using bad ones. I'm currently learning **agentic AI and MCP pipelines** because that's where the interesting backend problems are going.

**What I'm open to:**
Summer internships in backend engineering, AI/ML systems, or full-stack roles. Remote-friendly. Also open to open source contributions on projects I find interesting.

<p>
  <a href="https://www.linkedin.com/in/bhumika-bahuguna-6b068a306" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" />
  </a>
  <a href="mailto:bhumika.bahuguna@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" />
  </a>
  <a href="https://bhumikabahuguna.github.io/My_Portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&amp;logo=google-chrome&amp;logoColor=white" />
  </a>
</p>

---

## Projects

These are the three I'm most proud of right now. Each one taught me something the textbooks didn't cover.

---

### FinishIt — AI Productivity Manager

A task and habit manager with an actual brain behind it. Not just a to-do list wrapper around an LLM — the AI assistant has full context of your tasks, habits, and matrix state before it says anything.

**The interesting part:** Eisenhower Matrix prioritization running in real time on a React + Supabase architecture, with Google Calendar bidirectional sync. JWT auth, protected routes, and the AI runs on Groq (LLaMA 3) with a structured system prompt built fresh from user data each session.

`React 18` `Vite` `Supabase (PostgreSQL + GoTrue)` `Groq API / LLaMA 3` `Google Calendar API`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&amp;logo=github&amp;logoColor=white)](https://github.com/BhumikaBahuguna/FinishIt)

---

### Notes Summarizer — OCR + LLM Study Pipeline

Upload a photo of your handwritten notes. Get back flashcards, concept maps, quizzes, and a cheat sheet. Stateless and privacy-first — nothing touches a database.

**The interesting part:** Azure Document Intelligence handles primary OCR with PaddleOCR as fallback. Summarization uses a parallel racing strategy — Groq and Gemini both process simultaneously and the first valid response wins. This masks latency spikes without paying for a single provider's worst-case timing. A regex pre-filter strips OCR artifacts before any LLM sees the text, saving tokens and preventing hallucinations on garbage input.

`FastAPI` `React` `Tailwind CSS` `Azure Document Intelligence` `PaddleOCR` `Gemini` `Groq` `Mermaid.js`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&amp;logo=github&amp;logoColor=white)](https://github.com/BhumikaBahuguna/Notes_Summarizer)

---

### Source-to-Source Compiler (Python to C / C++)

A full transpiler built from scratch in Python — no parsing libraries, no shortcuts. Translates Python code to C and C++ through every stage a production compiler runs.

**The interesting part:** Python's semantic whitespace is the hard problem. Solved with an indent stack that emits INDENT/DEDENT tokens, letting the parser treat indentation identically to `{}` blocks. The two-pass semantic analyzer maps all globals in pass one, then validates types and scope in pass two. A behavioral validator compiles the generated C/C++ with GCC and diffs its output against the original Python execution to verify correctness. Every stage visualized in a Flask web UI.

**What I learned:** A language-neutral AST is the key insight — once source is parsed into standardized nodes (IfStmt, ForRangeStmt, BinaryOp), the code generator doesn't need to know the origin language.

`Python 3.8+` `Flask` `Vanilla JS` `GCC / G++`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&amp;logo=github&amp;logoColor=white)](https://github.com/satyamsiuu/Source_to_Source_Code_Compiler)

---

## Tech Stack

Things I've actually used in the projects above.

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white)

### Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&amp;logo=flask&amp;logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&amp;logo=react&amp;logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&amp;logo=tailwindcss&amp;logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&amp;logo=vite&amp;logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&amp;logo=mysql&amp;logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&amp;logo=supabase&amp;logoColor=white)

### AI / ML
![LLMs](https://img.shields.io/badge/LLMs%20(Groq%20%2F%20Gemini)-FF6F00?style=for-the-badge&amp;logo=huggingface&amp;logoColor=white)
![OCR](https://img.shields.io/badge/OCR%20(Azure%20%2F%20Paddle)-0078D4?style=for-the-badge&amp;logo=microsoft&amp;logoColor=white)
![NLP](https://img.shields.io/badge/NLP-4B8BBE?style=for-the-badge&amp;logo=python&amp;logoColor=white)

### Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&amp;logo=github-actions&amp;logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white)

---

## GitHub Stats

<div align="center">

<!-- Shields.io pulls live from GitHub API - no allowlist, always works -->
<img src="https://img.shields.io/badge/Total%20Contributions-875-0e75b6?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Contributions" />
<img src="https://img.shields.io/github/followers/BhumikaBahuguna?style=for-the-badge&amp;logo=github&amp;label=Followers&amp;color=0e75b6" alt="Followers" />
<img src="https://img.shields.io/github/stars/BhumikaBahuguna?style=for-the-badge&amp;logo=github&amp;label=Stars&amp;color=0e75b6&amp;affiliations=OWNER" alt="Stars" />

</div>

---

## Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=BhumikaBahuguna&amp;theme=tokyo-night&amp;hide_border=true&amp;area=true" alt="Contribution Graph" />

</div>

---

## Currently Learning

- **Agentic AI** — multi-step AI workflows that actually do something end-to-end
- **MCP (Model Context Protocol)** — building tools that connect LLMs to real systems
- **System Design** — distributed systems patterns and internship interview prep

---

<div align="center">

**Open to internships, collaborations, and interesting problems.**

*bhumikabahuguna8@gmail.com*

---

*Made with focus and curiosity.*

</div>
