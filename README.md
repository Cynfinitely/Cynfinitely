<div align="center">

# Celal Yasin Nari

**Senior Fullstack Developer** at [Northfina](https://www.linkedin.com/company/northfina)

I build fullstack web applications with Next.js and Azure, ship products that real users depend on, and work on benefits platforms by day — with open source and side projects on the side.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Cynfinitely)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/celal-yasin-nari)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://cyn-resume-website.vercel.app)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@CynCoding)

</div>

---

## About

Senior fullstack developer based in Helsinki, with experience across the stack — from React and Next.js frontends to Node, Java, and Python backends. I care about clean architecture, readable code, and getting software into the hands of real users. At **Northfina**, I build Next.js and Azure Functions apps for the **Etufillari** bike-benefits platform. Outside of work, I maintain **Control** (life-management), **Engoryx** (engineering management), **CynSeat** (ticketing for NGOs), **DüşYora** (dream interpretation), tools like Craft Master 67, transcription pipelines, and browser extensions, and I'm building a 2D game, **Gloamflux**, in Godot. Every repo follows my own engineering standard — agent rules, git hooks, Conventional Commits, lint/format/audit gates, secret scanning, and CI. I also share job-hunting and engineering content on YouTube and mentor developers.

---

## Featured Projects

### Hobby

#### Product

**[Control](https://github.com/Cynfinitely/Control) · [Live demo](https://control-two-psi.vercel.app)**

Invite-only personal life-management app — todos, goals, budget with bank CSV import, health and migraine diary, journal, food logging and meal planning, exercise and workout programs, religious practice, career, networking, weather, and cross-area reports. Each user switches modules on and off, joins through single-use expiring invite links, and gets a page guide on every page. Cloud PostgreSQL so it works on Mac, desktop, and iPhone.

`Next.js 16` `React 19` `TypeScript` `Prisma` `PostgreSQL` `NextAuth` `Tailwind CSS`

**Engoryx** · private repo

Multi-tenant engineering-management platform — teams, daily updates, project roadmaps and goals, GitHub App integration with pull-request lookup and reports, career tracks, and weekly delivery assessments. Metrics are transparent and evidence-backed, with no developer performance score.

`Next.js` `TypeScript` `Cloudflare Workers` `D1` `Drizzle` `Tailwind CSS`

#### Game

**[Craft Master 67](https://github.com/Cynfinitely/Craft-master-67) · [Live demo](https://craft-master-67.vercel.app)**

Local-first Path of Exile 2 crafting helper. Its crafting brain simulates every technique it knows — essences, desecration with Well of Souls, fracturing, alloys, Greater Exaltation, side omens — tunes each one's options, and ranks them by expected cost per finished item, with the 50% / 90% cost spread, success rate, and a shopping list. Also recommends a base for a goal, mass-crafts batches, plans from a pasted item or PoB code, and re-prices saved plans at live poe2scout prices.

`Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `SQLite` `Drizzle`

**Gloamflux** · private repo · _in development_

A 2D platformer built in Godot 4. Early days: player movement, the first level, and deadly lights that reset it — with GUT tests and CI from day one.

`Godot` `GDScript`

#### Utility

**[AquiReminder](https://github.com/Cynfinitely/AquiReminder)**

Chrome extension that reminds you to stay hydrated. Set a timer, get alerts with sound even when the popup is closed, then acknowledge, snooze, or pause. Available in six languages.

`JavaScript` `Chrome Extension API`

**[EchoScribe](https://github.com/Cynfinitely/EchoScribe) · [Live demo](https://huggingface.co/spaces/Cynfinitely/EchoScribe)**

Turn spoken words into accurate text. Transcribes video and audio with OpenAI Whisper — 99+ languages, timestamps, TXT/SRT/JSON export, and privacy-first processing with no permanent storage. Runs as a Gradio app on Hugging Face Spaces, or self-hosted with FastAPI and Docker.

`Python` `FastAPI` `OpenAI Whisper` `Gradio` `Hugging Face` `Docker`

#### Tooling

**dev-standards** · private repo

My engineering standard, applied to every repo above — AI-agent rules (AGENTS.md for Claude Code, Cursor, and Copilot), Husky hooks (gitleaks secret scan, lint-staged, commitlint, pre-push lint/typecheck/test), Knip, an npm-audit gate with reviewed waivers, and a PR-checks GitHub Actions workflow. Versioned, with a changelog and upgrade steps.

`Shell` `Node.js` `Husky` `GitHub Actions`

---

### Businesses

**[MTS Security](https://github.com/Cynfinitely/mtssecurity) · [Live site](https://www.mts-sicherheit.com)**

Marketing website for MTS Security in Augsburg — homepage plus security and facility service pages, structured data, generated sitemap and robots, optimized images, a zero-dependency build script, and a contact form backed by a serverless email function. Deployed on Vercel.

`HTML` `CSS` `JavaScript` `Vercel`

**DüşYora** · private repo · [Live demo](https://dusyora.vercel.app)

Turkish dream-interpretation platform — customers buy credits or a subscription, submit a dream, and receive a written interpretation from a real interpreter, not an AI. Payments, email, and analytics sit behind small provider ports.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Auth.js` `Tailwind CSS`

---

### Community

**[CynSeat](https://github.com/Cynfinitely/cynseat) · [Live demo](https://cynseat.vercel.app)**

Free ticketing platform for NGOs and event organizers, rebuilt from a single-event storefront into a full platform — organizations with roles and invitations, a shared venue directory, multilingual events, general-admission and reserved seating (seat-map editor and seat picker), each organization's own Stripe Connect account, QR and PDF tickets, refunds, door check-in, attendee exports, and data retention. English, Finnish, and Turkish. The first version served **200+ users and NGOs**.

`Next.js 16` `TypeScript` `PostgreSQL` `Drizzle` `Better Auth` `Stripe` `Tailwind CSS`

---

### Personal

**[CYN Resume Website](https://github.com/Cynfinitely/CYN_RESUME_WEBSITE) · [Live demo](https://cyn-resume-website.vercel.app)**

Newspaper-style personal brand site — experience, projects, skills, and latest YouTube videos in deep-linkable sections, with SEO (sitemap, robots, canonical URLs) and security headers.

`Next.js` `TypeScript` `React` `Framer Motion`

---

## Tech Stack

**Languages**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)

**Backend & Data**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-000000?style=flat-square&logo=betterauth&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Game Dev**  
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**Testing & Quality**  
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Husky](https://img.shields.io/badge/Husky-42B983?style=flat-square&logo=git&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

**Tools & Cloud**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

<div align="center">

Open to connecting on [LinkedIn](https://www.linkedin.com/in/celal-yasin-nari) — especially around fullstack development, benefits platforms, and interesting side projects.

</div>
