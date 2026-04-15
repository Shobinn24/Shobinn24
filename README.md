# Hi there, I'm Shobinn Clark 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shobinn-clark-27722a85/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail)](mailto:Shobinn24@gmail.com)

</div>

## 🚀 About Me

**AI Agent Developer & Full-Stack Engineer** building production Claude- and Gemini-powered systems for clients. I ship autonomous agents, multi-tenant chatbot SaaS, and AI-augmented operational tools — real software that runs in production, not demos.

- 🎯 **Focus:** Anthropic Claude API · Google Gemini · Model Context Protocol (MCP) · production agent architecture
- 💼 **Currently:** Freelance development at E-Clarx LLC (Jan 2026 – Present). Client engagements in apparel, legal, and e-commerce.
- 🔧 **Building:** AI image generation, embeddable chatbot SaaS, marketplace automation, autonomous reporting agents
- 📍 **Location:** White Plains, MD · Remote-first

## 🛠️ Tech Stack

### AI / LLM
![Claude](https://img.shields.io/badge/Anthropic%20Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-black?style=for-the-badge)

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Deploy & DevOps
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Testing
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

## 🏆 Featured Projects

### 🎨 AI Product Photography Tool
AI product photography tool for a DTC apparel client. Python + Google Gemini generates 53 audited pose variations × 10 model profiles × multiple colorways.
- 🖼️ Full web UI with team auth, progress streaming, thumbnail grid, and ZIP download
- 🗄️ SQLite-backed gallery persistence on a mounted Railway volume — survives redeploys
- 🔐 CORS-locked API boundary, environment-driven config, production secrets hygiene
- 📚 Deploy documentation clean enough to onboard the next engineer

**Tech:** `Python` `Google Gemini API` `FastAPI` `Vercel` `Railway` `SQLite`

---

### [🤖 Claude Daily Brief](https://github.com/Shobinn24/claude-daily-brief)
Autonomous AI agent that delivers an executive news brief every morning. Fetches RSS feeds, summarizes via Anthropic Claude, emails the result — fully unattended.
- 🔁 Idempotent runs tracked in SQLite — safe to manually re-trigger
- ⚡ Exponential backoff retry on 429 / 5xx errors
- ⏰ `launchd` scheduled on macOS (cron-compatible on Linux)
- 📝 ~500 lines across five clean modules, written to be forked and adapted

**Tech:** `Python` `Anthropic SDK` `SQLite` `SMTP` `launchd`

---

### [💬 FirmChat — Multi-Tenant AI Chatbot SaaS](https://github.com/Shobinn24)
Embeddable AI chatbot product that businesses embed on their websites with a single script tag. Each bot custom-trained on the client's business info for 24/7 support.
- 🏢 Multi-tenant architecture with per-client system prompts
- 💾 Session persistence via localStorage, real-time typing indicators
- 📱 Mobile-responsive design with fullscreen mode
- 💰 Tiered pricing (Starter, Professional, Enterprise)

**Tech:** `Anthropic Claude API` `FastAPI` `React` `PostgreSQL` `Vite` `Railway` `Vercel`

---

### [🔄 KonvertIt — Marketplace Conversion SaaS](https://github.com/Shobinn24/KonvertIt)
Production SaaS that converts Amazon & Walmart listings into optimized eBay drafts. Built for E-Clarx LLC.
- 🛒 Scrapes product data with proxy rotation and circuit-breaker resilience
- 🎯 6-step eBay title optimization engine and professional description templates
- 💰 Profit calculator with eBay fee-aware pricing and VeRO brand compliance
- 📡 Real-time WebSocket notifications, SSE bulk streaming, tiered rate limiting
- 🧪 **811 tests** (unit, integration, E2E) with CI/CD via GitHub Actions
- 💳 Stripe subscription billing with free/pro/enterprise tiers

**Tech:** `Python` `FastAPI` `React` `TypeScript` `PostgreSQL` `Redis` `Docker` `Playwright` `Stripe`

---

### [⚖️ Case Raft — Legal Reporting Tool](https://github.com/Shobinn24/case-raft)
Live SaaS for solo law firm attorneys. Integrates with **Clio Manage** to generate court-ready case reports as downloadable PDFs.
- 🔐 OAuth 2.0 integration with Clio Manage API for live case data
- 📄 Comprehensive PDF reports: matter details, billing, invoices, contacts
- 📦 Batch generation — select up to 20 cases at once

**Tech:** `Python` `Flask` `React` `PostgreSQL` `WeasyPrint` `Docker` `OAuth 2.0`

**🔗 [Live at caseraft.com →](https://caseraft.com)**

## 📊 GitHub Stats

<div align="center">

![Shobinn's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Shobinn24&show_icons=true&theme=radical&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shobinn24&layout=compact&theme=radical&hide_border=true)

</div>

## 💼 What I Bring

```javascript
const shobinnClark = {
  role: "AI Agent Developer & Full-Stack Engineer",
  company: "E-Clarx LLC (Founder, Freelance)",

  shipping: {
    productPhotography: "AI image generation with 53 audited poses — Python + Gemini",
    claudeDailyBrief: "Autonomous RSS-to-brief agent — Python + Anthropic SDK",
    firmChat: "Multi-tenant chatbot SaaS — Claude + FastAPI + React",
    konvertIt: "Marketplace conversion SaaS with 811 tests + Stripe billing",
    caseRaft: "Live legal-tech SaaS at caseraft.com — Clio integration"
  },

  strengths: [
    "AI agent architecture — retry/backoff, idempotency, prompt caching",
    "Production deployment — Railway + Vercel with secrets hygiene, CORS, volumes",
    "Full-stack fluency — Python + TypeScript, FastAPI + React, SQL + SQLite",
    "Clear handoff documentation — the kind that survives the freelancer leaving",
    "Ship fast, test thoroughly, own the consequences"
  ],

  lookingFor: [
    "AI / agent engineering contracts and freelance builds",
    "Full-time Software Engineer roles",
    "Startup or growth-stage teams that ship"
  ]
};
```

## 📫 Let's Connect

I build production AI systems that run unattended. Let's talk.

- 🌐 **Portfolio:** [eclarx.com](https://www.eclarx.com/)
- 💼 **LinkedIn:** [linkedin.com/in/shobinn-clark-27722a85](https://www.linkedin.com/in/shobinn-clark-27722a85/)
- 📧 **Email:** Shobinn24@gmail.com
- 📍 **Location:** White Plains, MD · Remote-first

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Shobinn24&color=blueviolet&style=for-the-badge)

</div>
