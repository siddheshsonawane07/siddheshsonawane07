<div align="center">

# Siddhesh Sonawane

**Freelance Software Engineer** · Pune, India

Lead engineer on a suite of nine business applications for a multi-venue food and beverage operator.
I own delivery end to end — scoping, architecture, deployment, maintenance.

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://siddheshsonawane07.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddheshsonawane07/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/siddhesh_07_dev)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@siddheshsonawane07)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:siddheshsonawane07@gmail.com)

</div>

---

## Client Work

<sub>Private codebases, client names withheld. Happy to walk through any of these on a call.</sub>

### Business Operations Suite
TypeScript · React · Vite · Express · PostgreSQL · Supabase Auth · React Native (Expo) · TanStack Query · Railway

Nine applications for a food and beverage company that runs concession stands inside two stadiums and is opening its first shop. Between them they run the business: the money, the production schedule, the crew on shift, and the people and their pay.

- **One sign-in for every app** — two-factor, with each person seeing only the apps they've been given. It replaced a shared passcode and hard-coded passwords, and removed access takes effect on the next click.
- **Financials** — game-day reports are read straight from PDFs and spreadsheets and each day reconciles itself. One supplier invoice went from **10–15 minutes to under 2**, and the rebuild found a revenue double-count that had counted **every game day twice**.
- **Investor P&L** — a **3–5 year** model by scenario, laid over the season's actual results as they flow in from Financials, with **zero figures re-keyed** and a read-only view for investors.
- **Production planner** — drafts the schedule from **both stadiums' live event calendars**, checking venue access, batter kits, transport and staff on every day. The operations manager adjusts it rather than building it.
- **Crew phone app** — native iPhone and Android. Crew see shifts, clock in at the stand and finish with a count that goes straight into **one stock ledger**, so the company owns its own timesheet.
- **People and pay** — roster, absences, hours and pay in their own app, with pay as a separate permission. A **website admin** tile brings the public site's enquiries and newsletter behind the same sign-in.

### Business Directory Platform
Next.js 15 · React 19 · TypeScript · Supabase · Stripe · Tailwind 4 · Docker

A directory of Caribbean-owned businesses — public listings, paid subscription placements, donations, a blog, and an AI tool that helps the team find new businesses to list.

**[Live site](https://www.caribbeangreenbook.com/)**

- **Migrated the whole directory off WordPress** — all **140 business listings** moved onto the new stack with nothing dropped, replacing a site the client could no longer grow.
- **Passwordless self-service billing** — owners hold no platform account, yet change plans, cards and see invoices through a signed link instead of emailing support.
- **Stopped a double charge before it shipped** — free-to-paid and paid-to-paid are different Stripe paths. The server now refuses a second checkout for an existing subscriber and sends them to the Customer Portal.

### Community Heritage Archive
Expo SDK 57 · React Native · React 19 · TypeScript · Supabase · TanStack Query

An iPhone and Android app for a Caribbean island's food, healing, dialect, music and family history, in the voices of the elders, cooks and herbalists who hold it.

*The app is in progress.*

- **Layered media makes it an archive, not a forum** — audio, transcript, photographs and video sit on a single entry, and the dialect is kept as spoken rather than corrected into standard English.
- **A live feed, not a museum** — people post, follow, like and comment, so the archive grows as the community uses it.
- **Runs with no network on a clean clone** — a second, in-memory data layer behind the same interface takes contributor setup from **2–5 days to a single command**.
- **No table accepts a direct write** — reads go through 13 views and writes through 41 checked database functions.

### Logistics Lead-Generation Site
Next.js 16 · React 19 · TypeScript · Plain CSS · Railway · Cloudflare

A rebuild of the site for a US third-party logistics (3PL) provider that stores, picks, packs and ships freight for other brands. Its only job is getting brands and carriers into the sales funnel.

**[Live site](https://www.firsttofinallogistics.com/)**

- **WordPress rebuilt to sub-2-second load** — the band Google ties to conversion lifts up to **27%**, and **8.3% more form submissions per 0.1s** saved on lead-gen pages.
- **Core Web Vitals as shipping gates** — 90+ Lighthouse, LCP under 2.5s, CLS under 0.1, INP under 200ms.
- **Three runtime dependencies** — `next`, `react`, `react-dom`. No UI kit; the design system is hand-written CSS.
- **Three qualified lead paths** — a warehouse-space calculator, carrier signup and a brand onboarding programme, each landing pre-qualified in the client's CRM.

---

## Projects

| | What it does | Tech | |
|---|---|---|---|
| **Premise** | Shared memory for a team's AI coding agents. Records which rule each edit was written under, so when a rule changes it finds every file still on the old one — 9 of 9 in a hand-checked test where search found 7 | FalkorDB, Claude Code, MCP, TypeScript | [Demo](https://youtu.be/MojUWR5jKDs) · [Code](https://github.com/siddheshsonawane07/premise) |
| **Orbital Pinball** | A 3D pinball table that plays in the browser — flippers, ramps, multiball and missions. Built with Claude Code driving the Unity editor through MCP | Unity 6, C#, WebGL | [Play](https://ephemeral-cuchufli-320843.netlify.app/) |
| **Wix Stamps Bridge** | Free, open-source Wix app that ships Wix Stores orders through your own Stamps.com account, with no paid connector. Built and tested, not yet live on Wix | TypeScript, Wix | [Code](https://github.com/siddheshsonawane07/wix-stamps-bridge) |
| **AI Resource Library** | 176 links for building with AI coding agents, each tagged by what you do with it, packaged as a Claude Code skill | Claude Code skill | [Code](https://github.com/siddheshsonawane07/ai-resource-library) |
| **SprintFlow AI** | Turns a goal into a planned sprint — epics, stories and tasks, sequenced. 80% less planning overhead | Archestra.ai, MCP | [Demo](https://www.youtube.com/watch?v=_8dMuHbzci0&t=12s) |
| **Crisis Voice Agent** | Records assessment calls and fills the clinical paperwork — 70% less documentation time, sub-800ms latency, 94% transcript accuracy | FastAPI, Deepgram, React | — |
| **Support Assistant** | Triages support email and drafts the fix — 50+ tickets a day, triage from 18 minutes to 4 | PixieBrix, Azure DevOps | — |
| **GitHub Chatbot** | Lets visitors ask my GitHub questions instead of reading it | LangChain.js, FAISS | [Code](https://github.com/siddheshsonawane07/github_langchain_chatbot) |
| **WhatsApp Parser CLI** | WhatsApp exports into clean JSON you can actually analyse | Node.js | [npm](https://www.npmjs.com/package/whatsapp-chat-parser-cli) |
| **Proctorise** | Keeps remote exams honest — 91% pose-detection accuracy, violations flagged in under 1.2s | TensorFlow.js, React | [Live](https://proctorise.netlify.app/) · [Code](https://github.com/siddheshsonawane07/proctorise) |
| **Excel Visualizer** | Upload a spreadsheet, get the right charts without picking them | Streamlit, Pandas | [Live](https://sidexcelvisualizer.streamlit.app/) · [Code](https://github.com/siddheshsonawane07/excel_visualizer) |
| **Bounties Aggregator** | One place to find and publish on-chain bounties | Solidity, Ethers.js | [Live](https://bountiesaggregator.netlify.app/) · [Code](https://github.com/siddheshsonawane07/bounties_manager_v2) |

<sub>Flutter and Android — <a href="https://github.com/siddheshsonawane07/flutter_ai_radio">Online Radio</a> ·
<a href="https://github.com/siddheshsonawane07/flutter_wordle">Wordle</a> ·
<a href="https://github.com/siddheshsonawane07/flutter_movies_list">Movies List</a> ·
<a href="https://github.com/siddheshsonawane07/flutter_catalog_ui">Catalog UI</a> ·
<a href="https://github.com/siddheshsonawane07/flutter_solar_system_ui">Solar System UI</a> ·
<a href="https://github.com/siddheshsonawane07/reddit_meme_share">Meme Share</a></sub>

---

## Tech

**Frontend** React · Next.js · React Native (Expo) · Flutter · Astro · Redux · TanStack Query · Tailwind · Vite

**Backend** Node.js · Express · FastAPI · PostgreSQL · MySQL · MongoDB · Supabase · Firebase · Stripe

**AI** Claude Code · Claude API · MCP · LangChain · FAISS · FalkorDB · Deepgram · Mistral · TensorFlow.js · Pandas · Streamlit

**3D & Games** Unity 6 · Blender · Blender Python API · WebGL

**Languages** TypeScript · JavaScript · Python · C# · Java · Kotlin · Dart · Solidity · SQL

**Ops** Docker · Railway · GitHub Actions · GCP · Azure · Cloudflare · Netlify

**Automation** Automation Anywhere A360 · UiPath · PixieBrix · Jira

---

## Experience

**Freelance Software Engineer** — Independent · *Aug 2026 – Present*
Lead engineer on a suite of nine business applications for a multi-venue food and beverage operator: finance, investor P&L, production scheduling, a native crew app, and people and pay, behind one sign-in. In parallel, deliver billed products for other clients across web and mobile — scoping from the client call through architecture, deployment and the maintenance afterwards.

**Software Engineer** — Xalta Technologies, Pune · *Mar 2025 – Aug 2026*
Architected an AI crisis-assessment voice agent — real-time browser audio capture, streaming transcription and LLM-driven structured form generation — cutting clinical documentation by 70%. Built a browser-native production-support assistant doing thread-aware triage across 50+ tickets a day, dropping average triage from 18 minutes to 4. Delivered enterprise RPA on Automation Anywhere A360 and Jira Service Management configuration for client teams.

---

## Education

**B.E. Computer Engineering** — Dr. D.Y. Patil Institute of Technology, Pimpri · 8.76 CGPA · 2020–2024
Flutter Co-Lead, Google Developer Student Club.

---

<div align="center">

**Building an MVP, or need someone to own a product end to end?**

[siddheshsonawane07@gmail.com](mailto:siddheshsonawane07@gmail.com)

<sub>Open to freelance and contract work.</sub>

</div>
