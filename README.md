# Chong Hao Ooi

Full-stack and AI product developer. Year 2, Diploma in Information Technology (AI & Analytics), Singapore Polytechnic. GPA 3.70/4.00.

## Main products

| Project | What it does | Stack |
| --- | --- | --- |
| [AgniBot](https://github.com/AgniAnt/AgniBot) | Self-hosted messaging app where named AI bots each keep their own role and memory. Bun and TypeScript server with a WebSocket protocol, model router and job queue; native SwiftUI Mac client. | TypeScript, Bun, Swift, SwiftUI |
| [AgniReview](https://github.com/AgniAnt/aReview) | In-house AI code review tool, a cheaper alternative to hosted review products. In progress. | — |

## About

I am a Singapore Polytechnic student. I build web products and applied AI tools, including a student community app, a community fitness and wellness tracker, and a hackathon prototype for AI-agent assurance.

Dell InnovateDash 2026 finalist. UiPath certified. Apple Developer Society subcommittee.

## Tech stack

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-0F172A?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6)
![Node.js](https://img.shields.io/badge/Node.js-0F172A?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![Express](https://img.shields.io/badge/Express-0F172A?style=flat-square&logo=express&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-0F172A?style=flat-square&logo=postgresql&logoColor=4169E1)
![MySQL](https://img.shields.io/badge/MySQL-0F172A?style=flat-square&logo=mysql&logoColor=4479A1)
![Python](https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=3776AB)
![pandas](https://img.shields.io/badge/pandas-0F172A?style=flat-square&logo=pandas&logoColor=150458)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-0F172A?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-0F172A?style=flat-square&logo=ollama&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-0F172A?style=flat-square&logo=capacitor&logoColor=53B9FF)

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| EventNest (private repository) | Team event marketplace. I set up GitHub Actions CI with linting, tests and an 80% coverage threshold on pull requests. I built sign-up, login, sessions, 2 user roles, and RSVP capacity enforcement and cancellation, and wrote unit, integration and end-to-end tests in the team's 460+ test suite. | JavaScript, Express, PostgreSQL, Jest, Playwright |
| [Gamified Wellness Web App](https://github.com/chonghaoooi/BED-CA2) | Individual project: wellness tracker and points-based detective game. 25 REST API endpoints, 18 of them protected with JWT, on a 10-table MySQL database. Uses bcrypt hashing and parameterised SQL. | Node.js, Express, MySQL |
| [AI-Assisted Reporting & Email Automation](https://github.com/chonghaoooi/PDAS-CA2) | Team of three. I led a 14-stage UiPath workflow from data download to Word report and human-approved email. 2 GPT-5.1 steps classify 34 degree titles and draft the summary email. Classifications below 0.80 confidence go to human review. | UiPath, Python, GPT-5.1 |
| Machine Fault & Property Price Prediction (private repository) | AI and machine learning coursework. Compared 4 classifiers and tuned a Random Forest to 0.267 PR-AUC against a 0.058 baseline, catching 66% of rare faults at 24% precision on the held-out test set. Compared 5 regression models and cut property price MAE by 53% against the best baseline (R² 0.74). | Python, pandas, scikit-learn |
| [AgniBot](https://github.com/AgniAnt/AgniBot) | Four-person, self-hosted AI agent app. I built ChatGPT sign-in with OAuth (PKCE) and token renewal, and a bot debugger showing each turn's model calls, tool calls and failures. 5 merged pull requests. | TypeScript, Bun, React |
| [MemWorker](https://github.com/NachikethReddyY/MemWorker) | Mobile case-workflow app for Singapore Children's Society youth workers. Turns notes and recordings into summaries, follow-ups and risk flags. Dell InnovateDash 2026 Finalist. | React Native, Expo, TypeScript |
| [Kaki](https://github.com/chonghaoooi/kaki) · [Live demo](https://kaki-orcin.vercel.app) | Student community app. Students find a small campus plan, then stay in touch through clubs, peer mentorship, and private support. MAJU Hackathon 2026. | React, TypeScript, Node.js, SQLite |
| [TrustLadder](https://github.com/chonghaoooi/OCBC-Trust-Ladder) | AI agent gateway for the OCBC Ignite Challenge 2026. An LLM judge runs five checks on bank chatbot drafts before a human officer approves release. | Python, OpenAI, OpenTelemetry |
| [CCAbot](https://github.com/chonghaoooi/ccabot) | Discord bot for CCA event announcements and member reminders. An organiser can enter an event, or the bot can read a public form, pasted text, or a screenshot. OCR reads the screenshot. A local Ollama model extracts the fields. | Python, discord.py, Ollama, Tesseract |

## Small builds

| Project | What it does | Stack |
| --- | --- | --- |
| [+1 lean](https://github.com/chonghaoooi/plus1lean) | AI calorie and gym app with a private friends-only feed where AI personas react to food and gym choices. | TypeScript |
| [CCA attendance reminder](https://github.com/chonghaoooi/ats-reminder) | Sounds my phone when it is time to take attendance, based on my school timetable. | Kotlin |
| [AI proxy gateway](https://github.com/chonghaoooi/ai-proxy-tailscale) | CLIProxyAPI behind a Node gateway with per-user keys over Tailscale. | JavaScript, Node.js |
| [Uptime monitor](https://github.com/chonghaoooi/ai-proxy-tailscale/tree/main/service-monitor) · [Status page](https://ability1.statuspage.io/) | Cloudflare Worker that checks /health of my Tailscale services each minute and feeds a public status page. | Cloudflare Workers |

## Other projects

| Project | What it does | Stack |
| --- | --- | --- |
| [Wellness Site](https://github.com/chonghaoooi/roblox-wellness-site) | A professional community fitness and wellness tracker: meal logs, workout posts, leaderboards, an optional AI coach, and optional phone step sync. | Next.js, TypeScript, Postgres, Capacitor |
| [auto-auth](https://github.com/chonghaoooi/auto-auth) | Chrome and Edge extension that completes Microsoft sign-in, including the TOTP code, for Outlook and Teams. Credentials stay in the browser. | TypeScript, Manifest V3 |
| [PDAS-CA1](https://github.com/chonghaoooi/PDAS-CA1) | School notebook on provided LinkedIn job-posting files. Pandas merges the files and estimates annual salary. Matplotlib charts compare salary by experience level and by whether a posting is marked remote. The salary comparison uses disclosed USD postings only. | Python, pandas, Matplotlib |
| UiPath RPA | RPA workflow automation built with UiPath. No public repository. | UiPath |

## Team contributions

[Agni](https://github.com/NachikethReddyY/agni-bot) is a self-hosted AI agent in a teammate's repository. Merged pull requests: a ChatGPT subscription provider and onboarding ([#19](https://github.com/NachikethReddyY/agni-bot/pull/19)), memory search that covers every saved fact and carries summaries into tasks ([#1](https://github.com/NachikethReddyY/agni-bot/pull/1)), the ChatGPT callback page theme ([#20](https://github.com/NachikethReddyY/agni-bot/pull/20)), and a bot debugger with the instant lane and the tool and token budgets removed ([#34](https://github.com/NachikethReddyY/agni-bot/pull/34)).

[ReDDone](https://github.com/NachikethReddyY/reddone) is a teammate's approval-gated tool that turns authorized market evidence into a verified application and deployment. Contributions there are selectable workflow models and a Railway-ready backend package.

## Looking for

An overseas internship from March 2027 in product, front-end, full stack, or AI applications.

## Contact

- GitHub: [github.com/chonghaoooi](https://github.com/chonghaoooi)
- Email: [chonghaoooi28@gmail.com](mailto:chonghaoooi28@gmail.com)
