# Hi, I'm Sai

I'm a Computer Science student at **UT Dallas**, graduating **May 2028**. I'm an aspiring Software Engineer with a passion for learning, collaborating and building. 

I moved to the US from Doha, Qatar for college and I speak English, Malayalam and Hindi. I have a fascination for languages and am able to read Tamil, Arabic (with minimal understanding), and Urdu. 

---

## What I build
Over my 2 years in college (so far), I've built:

### Glass — habit and hydration tracker
My main project, and the one I've learned the most from.

**React + TypeScript + Bootstrap · Python/FastAPI · PostgreSQL · Docker · Render + Neon**

- Multi user habit tracking with per user data isolation, built and tested against IDOR
- Streaks computed in SQL with window functions using a gaps and islands query, kept in a standalone `streaks.sql` rather than buried in ORM code
- Three state streak badge: alive, frozen, dead
- Automated test suite running in GitHub Actions against a Postgres service container
- Separate develop and staging tier with its own services and a Neon database branch
- Live deployment monitored with UptimeRobot

Repo: [github.com/sainair/hydration-tracker](https://github.com/sainair/hydration-tracker) · Live: [glass-g7c5.onrender.com](https://glass-g7c5.onrender.com)

### Briefer — daily calendar brief emailer
**Node.js + TypeScript · Vercel Cron**

- Reads a private ICS feed and emails a clean brief of the day every morning at 7am Central
- Handles daylight saving transitions by firing the cron twice and checking local time in code, instead of trusting a fixed UTC offset
- Currently migrating email delivery off the Gmail API after hitting OAuth verification limits, which turned out to be a good lesson in choosing infrastructure you can actually operate

Repo: [github.com/sainair/daily-brief](https://github.com/sainair/daily-brief)

### Learning projects
Small repos where I work out one thing properly before using it in something real.

- **FastAPI + Docker Compose:** SQLModel CRUD API on Postgres 18, multi stage Dockerfile with hardened base images and credentials passed in as Docker secrets
- **React + Vite + TypeScript:** single Dockerfile with separate development and production build stages, orchestrated with Compose

---

## Experience

**Digital Business Systems Intern, North Oil Company** (Doha, Qatar · Summer 2026)

Worked on the ServiceNow platform, mainly the Strategic Portfolio Management module. Built a customized Employee Service Center portal covering demand management, with search, service navigation, and knowledge base entry points, and presented the work to the team at the end of the internship.

---

## Where I'm headed

I started this portfolio with no React and very little JavaScript. About a year ago (as visible from my contributions graph), I didn't know most of what I use on a daily basis today, and I intend to keep that up. 

Next up:

- **Building with LLMs.** Retrieval, structured outputs, tool use, and the evaluation work that separates a demo from something you can trust
- **Going deeper on Postgres.** Indexing and query plans rather than just making the query return the right rows
- **Getting better at systems thinking.** Designing services, not just shipping features

Long term, I want to be the engineer who owns a system end to end: someone who can design it, deploy it, keep it running, and explain every decision in it.

---

## Toolbox

`Python` `TypeScript` `JavaScript` `Java` `SQL` `React` `FastAPI` `Node.js` `PostgreSQL` `Docker` `Git` `GitHub Actions` `Vercel` `Render` `Neon` `LaTeX` `ServiceNow`

---

## Reach me

- GitHub: [@sainair](https://github.com/sainair)
- LinkedIn: https://linkedin.com/in/sainair06
- Email: saisatish.nair@utdallas.edu
