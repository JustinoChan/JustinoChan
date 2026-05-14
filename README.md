<!-- Profile README for JustinoChan/JustinoChan -->

<h1 align="center">Justin Chan</h1>
<p align="center">
  Software Engineer | UCI Software Engineering B.S. | Full-stack, AI/RL, search, and reliable systems
</p>
<p align="center">
  <a href="mailto:justinochan16@gmail.com">Email</a> |
  <a href="https://github.com/JustinoChan/Website">Portfolio</a> |
  <a href="https://github.com/JustinoChan/AscensionAI">AscensionAI</a>
</p>

---

## General Introduction

Hi, I am Justin, a software engineer based in Brentwood, California. I graduated from the University of California, Irvine in March 2025 with a B.S. in Software Engineering, and I like building software that connects practical product work with deep technical systems.

My work spans full-stack web applications, search and information retrieval, database-backed products, and AI systems. Recently I have been focused on AscensionAI, a reinforcement learning project that trains an autonomous agent to play Slay the Spire through behavior cloning, PPO fine-tuning, legal-action masking, and parallel rollout collection from live game instances.

I am currently looking for software engineering roles where I can contribute to a strong team, ship clean and maintainable systems, and keep growing as an engineer.

---

## What I Build

| Area | What I like working on | Examples |
|---|---|---|
| AI and reinforcement learning | Training loops, observation encoders, policy optimization, action masking, evaluation, long-running automation | AscensionAI |
| Full-stack products | Responsive frontends, authenticated APIs, database-backed features, real-time interactions | BitLink, Capstone Project Archive |
| Search and data systems | Indexing, query processing, algorithm optimization, structured data pipelines | Python search engine over 56,000+ pages |
| Reliability tooling | Crash recovery, atomic checkpoints, stale-data rejection, worker monitoring, resumable runs | AscensionAI training infrastructure |
| Developer experience | Terminal-style interfaces, clean project structure, documentation, practical workflows | Personal portfolio and project writeups |

---

## Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Backend and Data

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6F00?style=flat-square&logo=postman&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=111111)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

### AI, ML, and Reinforcement Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square&logo=python&logoColor=white)
![PPO](https://img.shields.io/badge/PPO-6C5CE7?style=flat-square)
![Behavior Cloning](https://img.shields.io/badge/Behavior_Cloning-2D3436?style=flat-square)
![GAE](https://img.shields.io/badge/GAE-0984E3?style=flat-square)
![Actor-Critic](https://img.shields.io/badge/Actor--Critic-00B894?style=flat-square)
![Action Masking](https://img.shields.io/badge/Action_Masking-D63031?style=flat-square)

### Tools and Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Agile](https://img.shields.io/badge/Agile%2FScrum-4A5568?style=flat-square)
![Testing](https://img.shields.io/badge/Software_Testing-2F855A?style=flat-square)

---

## Featured Project: AscensionAI

[AscensionAI](https://github.com/JustinoChan/AscensionAI) is my most ambitious current project: an end-to-end reinforcement learning system for training an autonomous agent to play Slay the Spire against the live game process.

| System Piece | Details |
|---|---|
| Environment | Live Slay the Spire integration through ModTheSpire, BaseMod, CommunicationMod, and SpireComm |
| Observation space | 530-dimensional structured encoder covering player state, screens, hand cards, monsters, powers, choices, relics, potions, deck profile, and map lookahead |
| Action space | 134 discrete actions with legal-action masking so the policy only samples valid actions |
| Model | Actor-critic MLP policy/value network, roughly 235K parameters, CPU-friendly inference |
| Learning pipeline | Behavior cloning warm-start followed by PPO fine-tuning with GAE, entropy annealing, target-KL early stopping, and BC anchor loss |
| Scaling strategy | Parallel rollout workers collect live games into checkpoint-tagged `.npz` files for a central offline trainer |
| Reliability work | Atomic checkpoint saves, resumable behavior-cloning progress, crash detection, stale-rollout rejection, worker relaunch, and stuck-state recovery |
| Current status | Core pipeline is implemented; long-run convergence validation and evaluation are ongoing |

AscensionAI is where I have been practicing the kind of engineering I enjoy most: turning a messy real-world interface into a structured learning problem, then making the system reliable enough to run for hours without constant babysitting.

---

## Selected Projects

| Project | Stack | What it showcases | Links |
|---|---|---|---|
| AscensionAI | Python, PyTorch, Gymnasium, PPO, behavior cloning | RL systems, game automation, long-running training reliability, parallel workers | [repo](https://github.com/JustinoChan/AscensionAI) |
| Personal Portfolio | Next.js, React, TypeScript, Tailwind CSS | Terminal-inspired UI, clean responsive pages, project writeups, profile/resume presentation | [repo](https://github.com/JustinoChan/Website) |
| Search Engine | Python, JSON, information retrieval | Indexed 56,000+ web pages and reduced average query response time by 35% through tokenization and algorithm optimization | [repo](https://github.com/Vincent10351/Indexer) |
| Capstone Project Archive | React, Django, Firebase Auth, MySQL8 | Student project hosting app, REST API work, database integration, Agile team coordination | [repo](https://github.com/cpark50/capstone-archive) |
| BitLink | Angular, TypeScript, Node.js, MongoDB, Passport.js, BCrypt | Full-stack social platform with real-time messaging, auth, posts, likes, and follows | [repo](https://github.com/SusLiu03/BitLink) |

---

## Engineering Strengths

- Building across the stack, from database-backed APIs to responsive frontend experiences.
- Designing systems that survive long runs: checkpoints, resumable progress, crash recovery, and clear logs.
- Translating ambiguous problems into structured models, interfaces, and testable workflows.
- Optimizing practical bottlenecks, including search query speed, training throughput, and human-in-the-loop debugging.
- Writing documentation and project summaries that make the system understandable to someone seeing it for the first time.

---

## Current Focus

- Running and evaluating larger AscensionAI PPO training experiments.
- Improving RL stability through reward analysis, fixed-seed evaluation, and checkpoint versioning.
- Expanding my portfolio of production-style projects with strong documentation and clean UX.
- Preparing for software engineering roles where I can contribute to full-stack, backend, AI infrastructure, or developer tooling work.

---

## Education

**University of California, Irvine**<br>
B.S. in Software Engineering, March 2025

Relevant coursework included algorithms, data structures, operating systems, software testing, human-computer interaction, information retrieval, databases, web applications, and software design.

---

## GitHub Snapshot

| Profile Area | Highlights |
|---|---|
| Main profile | [github.com/JustinoChan](https://github.com/JustinoChan) |
| Featured AI/RL work | [AscensionAI](https://github.com/JustinoChan/AscensionAI), an end-to-end reinforcement learning system for Slay the Spire |
| Portfolio source | [Website](https://github.com/JustinoChan/Website), a Next.js profile and project showcase |
| Project history | Full-stack apps, information retrieval, database-backed web projects, and AI training infrastructure |
| Most represented skills | Python, TypeScript, React, Next.js, Django, Node.js, SQL, PyTorch, Gymnasium, Git |

I keep the profile README static on purpose: no third-party stats images, no fragile external render services, and no broken cards when a provider is down.

---

## Contact

I am open to software engineering opportunities, collaboration, and technical conversations.

- Email: [justinochan16@gmail.com](mailto:justinochan16@gmail.com)
- GitHub: [github.com/JustinoChan](https://github.com/JustinoChan)
- Portfolio source: [github.com/JustinoChan/Website](https://github.com/JustinoChan/Website)
