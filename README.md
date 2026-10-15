from pathlib import Path

readme = """<div align="center">

# Hey, I'm Kartikey Sharma 👋

### Full Stack Developer · Exploring AI Engineering

I build web applications and explore how LLMs can power useful products.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-111827?style=flat-square&logo=vercel&logoColor=white)](https://kartikey-xo.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartikey-sharma-a7b336381/)
[![GitHub](https://img.shields.io/badge/GitHub-Kartikey349-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kartikey349)

</div>

---

### 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,python,cpp,react,nextjs,tailwind,nodejs,express,fastapi,mongodb,postgres,redis,redux,docker,git,github,postman" alt="Tech stack icons" />
</p>

### 🤖 Currently Exploring

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- AI agents and tool calling
- LangChain and LangGraph
- Building AI-powered full-stack applications

### 🛠️ Tools & Technologies

![Groq](https://img.shields.io/badge/Groq-LLM_API-F55036?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC244C?style=flat-square)
![Drizzle ORM](https://img.shields.io/badge/Drizzle-ORM-C5F74F?style=flat-square)
![Clerk](https://img.shields.io/badge/Clerk-Authentication-6C47FF?style=flat-square)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Realtime-010101?style=flat-square&logo=socketdotio&logoColor=white)

---

### 🌐 Find Me Online

- **Portfolio:** [kartikey-xo.vercel.app](https://kartikey-xo.vercel.app/)
- **LinkedIn:** [Kartikey Sharma](https://www.linkedin.com/in/kartikey-sharma-a7b336381/)
- **GitHub:** [@Kartikey349](https://github.com/Kartikey349)

---

<div align="center">

*Learning consistently. Building thoughtfully. Improving every day.*

</div>
"""

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created complete README at {path}")
