# AmbitionMap AI

A student-focused career guidance web app that helps you discover tech career paths from your skills and interests, then gives you a practical learning plan and roadmap to get there.

**Live demo:** [https://ambitionmap-ai.vercel.app](https://ambitionmap-ai.vercel.app)

**GitHub:** [https://github.com/Sriram-554/AmbitionMap-AI](https://github.com/Sriram-554/AmbitionMap-AI)

> If `ambitionmap-ai.vercel.app` is not connected yet, the previous domain may still work:
> https://career-compass-ai-ochre-rho.vercel.app

---

## Project Description

AmbitionMap AI is a full-stack career discovery platform for college students. It combines a structured assessment, explainable career recommendations, AI coaching plans, and stage-by-stage learning roadmaps so students can move from uncertainty to a clear next step.

Students can:
1. Complete a skills and interests assessment
2. Receive ranked career matches with transparent reasons
3. Get a personalized 30-day coach plan for their top match
4. Follow learning roadmaps with free resources and progress tracking
5. Optionally create an account to sync progress across devices

---

## Technologies Used

- **Frontend:** React 19, Vite
- **Styling:** Custom responsive CSS (dark theme)
- **Recommendation engine:** Rule-based scoring (skills, interests, preference, branch, year)
- **AI coaching:** Vercel Serverless API + Groq LLM (with guided fallback)
- **Backend / Auth / Database:** Supabase (Auth, PostgreSQL, Row Level Security)
- **Storage:** Browser localStorage for guests; cloud sync for logged-in users
- **Hosting / Deployment:** Vercel
- **Testing:** Vitest

---

## Project URL

https://ambitionmap-ai.vercel.app

---

## What it can do

### Career discovery
- Multi-step assessment (education, skills, interests, preference)
- Optional college invite codes
- Ranked recommendations across 8 careers
- Match scores, skill gaps, advanced next steps, and ranking explanations

### AI career coach
- Personalized plan for the top match
- Why-fit narrative, focus skills, 30-day plan, project ideas
- Production LLM generation via secure API
- Guided fallback if AI is unavailable

### Learning roadmaps
- Stage-based paths with topics, tools, and projects
- Free resources and checkpoints
- Progress tracking, export checklist, print view

### Accounts & sync
- Guest mode: device-only local save
- Logged-in mode: Supabase cloud sync

### Product UX
- Unified dark theme
- Results tabs: Matches / Plan / Share
- Mobile-friendly layout

---

## Supported careers

- Machine Learning Engineer
- Web Developer
- Data Analyst
- Cybersecurity Analyst
- Cloud Engineer
- DevOps Engineer
- Mobile App Developer
- Research Scientist

---

## Getting started

```bash
git clone https://github.com/Sriram-554/AmbitionMap-AI.git
cd AmbitionMap-AI
npm install
npm run dev
```

### Scripts

```bash
npm run dev
npm run build
npm run preview
npm test
npm run lint
```

Setup guides:
- `BACKEND_SETUP.md`
- `LLM_SETUP.md`
- `DOMAIN_SETUP.md`

---

## License

Intended for learning, demos, and portfolio use.
