<h1 align="center">Guilherme Diniz</h1>

<p align="center">
  Full stack developer in Curitiba, Brazil.<br/>
  I build the systems, apps and integrations small and mid-size companies use every day.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/guilherme-diniz-dev/">LinkedIn</a> ·
  <a href="https://github.com/DinizGui?tab=repositories">Repositories</a>
</p>

---

## What I ship

- **Business systems**: ERPs, admin dashboards, CRMs, purchasing and finance control.
- **Mobile apps**: React Native (Expo) apps published on the App Store and Google Play, including the Apple review back-and-forth.
- **Integrations**: Brazilian electronic invoicing (NF-e, NFS-e), bank slips, Stripe, WhatsApp, accounting exports.
- **Automation**: scrapers, document extraction with vision (PDF deed to appraisal report), scheduled workers.

A few real ones:

| Project | What it does |
|---|---|
| Aktra Engenharia | ERP + client app + purchasing/finance CRM for a high-end construction company. 35 tables, 205 tests, 3 weeks to production. |
| Moss | Tachograph metrology: on-site test, sync, report, digital signature and submission to INMETRO, with billing tied to operations. |
| Real estate appraisals | Reads the property deed PDF with vision, fills the report, plots the route and queries CAR/SIGEF. |
| E-commerce invoicing | NF-e issuing for an online furniture store, including SEFAZ rejections and the config order that caused them. |

Most client work is private. The public repos below are side projects and labs.

## How I work

- **Claude Code, several agents in parallel.** Each agent gets its own git worktree, on its own branch. I decide what goes in, review every diff and do the merge.
- **Orca**: my own CLI that creates the worktree, opens a terminal with the agent inside and hands it the task. `node_modules` is shared across worktrees through a junction, so one install serves all of them.
- **Tests and written decisions** so the next person (or agent) does not need me on the phone.
- I write about the mistakes too. The Android build that shipped with a dev `.env` pointing to localhost is on my LinkedIn.

## Stack

Next.js · React · React Native (Expo) · Node.js · TypeScript · Prisma · PostgreSQL · MySQL · Python · Playwright · Vercel · Docker

## Public repos worth a look

- [site-generator](https://github.com/DinizGui/site-generator): AI landing page builder with guided briefing, JSON copy generation, section editor and live preview.
- [concord](https://github.com/DinizGui/concord): Discord-style chat built with Next.js and Prisma.
- [sf90-gsap-lab](https://github.com/DinizGui/sf90-gsap-lab): scroll-driven cinematic landing, GSAP + ScrollTrigger + Lenis.
- [scrape-gui](https://github.com/DinizGui/scrape-gui): REST API + automated scraper with Node, Express, Puppeteer and Prisma.
- [ZooApi](https://github.com/DinizGui/ZooApi): .NET 8 Web API + React front end.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DinizGui&show_icons=true&hide_border=true&theme=graywhite" alt="GitHub stats" height="150" />
</p>

---

<p align="center"><sub>Português: desenvolvedor full stack em Curitiba. Faço o sistema, o app e a integração que a empresa pequena e média usa todo dia. Fala comigo no LinkedIn.</sub></p>
