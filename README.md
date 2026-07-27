<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4F46E5,100:7C3AED&height=200&section=header&text=Satyam%20Gupta&fontSize=48&fontColor=ffffff&fontAlignY=42&desc=Software%20Engineer%20%E2%80%94%20in%20the%20making&descAlignY=62&descSize=17&descColor=E0E7FF" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=7C3AED&center=true&vCenter=true&width=620&lines=B.Tech+CSE+%E2%80%94+Invertis+University;Building+production-shaped+software;Frontend+%2F+Full+Stack+%2F+Backend;Open+Source+%E2%80%94+SSOC+2026" alt="Typing SVG" />

<br/><br/>

<a href="https://satyamgupta.vercel.app"><img src="https://img.shields.io/badge/Portfolio-4F46E5?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://linkedin.com/in/satyam-gupta-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/SatyamGupta16"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:satyamgupta18633@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Resume-111827?style=for-the-badge&logo=readdotcv&logoColor=white" /></a>
<!-- TODO: point the Resume badge at a hosted PDF once you have a link -->

</div>

<br/>

## 👋 Software Engineer

Most of my work starts the same way — a real constraint. A patient who needs a fast, trustworthy read on their symptoms. A learner who needs to see exactly where their skill gaps are, not a vague progress bar. A coaching business whose site needs to actually convert, not just look finished. The framework is never the interesting part. Deciding what the system needs to be true for the constraint to disappear — that's the part worth getting right.

I work across the stack because ownership doesn't stop at the API boundary. As team lead on **Healthcare Prediction & Diagnosis**, I took on the parts nobody volunteers for — a Row-Level Security policy that silently broke queries, a backend that cold-started at the worst possible moment — because shipping means the whole system works, not just the demo path.

Three years into a CS degree, most of what I've actually learned came from finishing things: a hackathon build under a deadline, an internship where the code had to survive a real release, a study roadmap I built myself because no one was going to hand me one. I'm still early. I try not to pretend otherwise — but I build like someone who expects to be trusted with production systems soon, because that's the bar I'm holding myself to.

---

## 🧭 Engineering Philosophy

- **Ship production-shaped software** — a working demo and a working system are not the same deliverable.
- **Simplicity is a decision, not a shortcut** — the simplest architecture that satisfies the real constraints wins.
- **Treat friction as a signal** — a cold start or a broken RLS policy is information, not a nuisance to route around.
- **Documentation is part of the build**, not a task appended at the end.
- **Accessibility and validation are UX**, not a checklist item for later.
- **Security and data policy get designed in**, not bolted on after the schema is settled.
- **Learn in public** — build the skill you don't have yet, in the open, on a deadline.

---

## 🎯 Current Focus

| Area | What that means right now |
|---|---|
| **System Design** | Moving from "it works" to "it scales" — starting with the systems I've already shipped |
| **Data Structures & Algorithms** | Working Striver's A2Z end to end, closing gaps surfaced through repeated practice |
| **Backend Depth** | API design, database modeling, auth patterns — via Chai aur Code and applied project work |
| **Cloud & Deployment** | Running real services on Vercel, Railway, and Supabase — not just localhost |
| **Open Source** | Active contributor track through SSOC 2026 |

---

## 🗂️ Featured Projects

<details open>
<summary><b>🌍 Real-World Problem Solving — the build philosophy behind every project</b></summary>
<br/>

Every project below shares the same constraint: it had to be deployed, secured, and usable by someone other than me. Not a tutorial clone, not a localhost-only demo. That standard shapes the tech choices below more than any framework preference does.

</details>

<br/>

<details>
<summary><b>🧠 SkillBridge AI</b> — Explainable-AI career mentoring platform</summary>
<br/>

**Overview**
Built for a hackathon under the *"Responsible and Explainable AI in EdTech"* theme. Analyzes a student's profile to produce career match scores, a skill-gap breakdown, and a 30-60-90 day learning roadmap — with an explainability layer that surfaces *why*, not just *what*.

**Architecture**
Next.js/React frontend consuming a FastAPI backend. The explainability layer (`explainer.py`) generates confidence scores and reasoning alongside every recommendation, surfaced in the UI through a dedicated `XAIDashboard.tsx` component rather than as an afterthought.

**Tech Stack**

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Features**
- Career match scoring against a student profile
- Skill-gap analysis with a 30-60-90 day roadmap output
- Confidence scores and plain-language reasoning for every recommendation

**Lessons Learned**
Explainability is a design constraint, not a UI feature — the reasoning layer had to be designed alongside the model output, not bolted on after the results screen was built.

**Links** — Repository not yet public

</details>

<br/>

<details>
<summary><b>🩺 Healthcare Prediction & Diagnosis</b> — Full-stack ML application, built as Team Lead</summary>
<br/>

**Overview**
A diagnosis-prediction platform built and deployed end-to-end for the IIOT-4 ML program, led as team lead across the ML, frontend, and backend workstreams.

**Architecture**
Next.js 15 frontend deployed on Vercel, a FastAPI backend on Railway serving four Logistic Regression models, and Supabase (PostgreSQL with Row-Level Security) as the data layer.

**Tech Stack**

![Next.js](https://img.shields.io/badge/-Next.js%2015-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Python](https://img.shields.io/badge/-scikit--learn-3776AB?style=flat-square&logo=python&logoColor=white)

**Challenges**
- RLS policy conflicts that silently blocked legitimate queries in production
- Cold-start latency on the Railway-hosted ML backend

**Features**
- Four Logistic Regression models serving predictions through a single API
- Row-Level Security enforced at the database layer, not just the app layer
- Full project documentation — report, cover page, and presentation — delivered alongside the code

**Lessons Learned**
Production issues surface only under production conditions. RLS policies and cold starts don't show up in local development — they show up when a real user hits the system, which is exactly when you don't want to be debugging them for the first time.

**Links** — Repository not yet public

</details>

<br/>

<details>
<summary><b>🎓 ElevateIQ</b> — Ed-tech / coaching platform</summary>
<br/>

**Overview**
A full coaching and education website built in the spirit of Byju's and Unacademy, with search visibility and lead capture treated as first-class requirements, not polish.

**Architecture**
Static, SEO-first build on Bootstrap 5, deployed to Vercel, with an EmailJS-powered contact flow replacing a traditional backend form handler.

**Tech Stack**

![Bootstrap](https://img.shields.io/badge/-Bootstrap%205-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Features**
- Full SEO pass: JSON-LD structured data, Open Graph tags
- EmailJS-powered contact flow with a WhatsApp redirect
- Layout and typography modeled on category-leading ed-tech products

**Lessons Learned**
Search visibility is architecture, not an afterthought — structured data and Open Graph tags are far easier to get right when they're part of the initial build than when they're retrofitted later.

**Links** — [Live](https://elevate-iq-topaz.vercel.app) · [Repository](https://github.com/SatyamGupta16/ElevateIQ)

</details>

<br/>

<details>
<summary><b>📝 Smart Registration Form</b> — Accessible form UX (DecodeLabs)</summary>
<br/>

**Overview**
A registration form built to prove that "accessible" and "polished" aren't in tension — live validation, a password-strength meter, and async submission, all usable with a keyboard and a screen reader.

**Architecture**
Vanilla HTML/CSS/JS, refactored into a clean three-file structure (`index.html`, `style.css`, `index.js`) after the initial build to separate concerns cleanly.

**Tech Stack**

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Features**
- Live field validation with a real-time password-strength meter
- Progress tracking through the form
- Async submission with a loading state
- Full accessibility support

**Lessons Learned**
Accessibility and async UX aren't separate concerns — a password-strength meter needs to announce its state to a screen reader to be genuinely usable, not just visually complete.

**Links** — Repository not yet public

</details>

---

## 🧱 Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**Cloud & Deployment**

![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 🛠️ Software Engineering Skills

REST API design · Authentication & authorization · Responsive design · Database modeling · Object-oriented programming · Applied problem solving · Git workflows · Deployment & CI basics · Debugging production issues

---

## 📈 DSA Journey

Working through **Striver's A2Z Sheet** end to end:

`Arrays` `Linked Lists` `Stacks` `Queues` `Recursion` `Backtracking` `Binary Search` `Trees` `Graphs` `Dynamic Programming` `Greedy` `Hashing` `Heaps` `Tries`

<!-- Add your LeetCode / Codeforces handles below to enable live stats cards -->
<!-- <img src="https://leetcard.jacoblin.cool/your-leetcode-username?theme=dark&font=JetBrains%20Mono" /> -->

---

## 🗺️ Learning Roadmap

**Completed**
DecodeLabs frontend projects · AI/ML internship at Edunet Foundation · Virtual quantum computing internship at IIT Roorkee · ElevateIQ · Healthcare Prediction & Diagnosis · SkillBridge AI

**In Progress**
14-month self-directed full-stack + DSA roadmap — closing gaps in backend depth, database design, and frontend-to-backend integration

**Next**
System design depth · sustained open-source contributions · a production-scale personal project

---

## 🌱 Open Source

Active contributor track through **SSOC 2026**. Building toward consistent, meaningful contributions rather than one-off pull requests — learning how real codebases are structured by working inside them.

---

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=SatyamGupta16&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=7C3AED&icon_color=7C3AED" />
<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=SatyamGupta16&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7C3AED" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SatyamGupta16&theme=tokyonight&hide_border=true&background=0D1117&ring=7C3AED&fire=7C3AED" width="75%"/>

<br/>

<img src="https://github-trophies.vercel.app/?username=SatyamGupta16&theme=darkhub&no-frame=true&margin-w=8&row=1" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SatyamGupta16&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=7C3AED&line=7C3AED" width="95%"/>

<br/>

<img src="https://komarev.com/ghpvc/?username=SatyamGupta16&style=flat-square&color=7C3AED&label=Profile+Views" />

</div>

<!-- Snake animation requires a one-time GitHub Action (platane/snk) on this repo to generate live -->

---

## 💡 Fun Facts

- Completed a virtual quantum computing internship at IIT Roorkee alongside a full CS course load.
- Serves as Campus Ambassador for E-Cell, IIT Bombay.
- Led a cross-functional team — ML, frontend, and backend — to ship a healthcare app end-to-end as an undergraduate.
- Builds the DSA and backend skill set entirely through free, self-directed study — no paid bootcamp involved.

---

## 📬 Connect

<div align="center">

<a href="https://linkedin.com/in/satyam-gupta-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:satyamgupta18633@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://satyamgupta.vercel.app"><img src="https://img.shields.io/badge/Portfolio-4F46E5?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/SatyamGupta16"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/X%20%2F%20Twitter-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
<!-- TODO: add your X/Twitter handle or remove this badge -->

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:4F46E5&height=100&section=footer" width="100%"/>

