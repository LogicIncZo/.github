<h1 align="center">LogicIncZo</h1>

<p align="center">
  <strong>A six-persona AI software factory</strong> — Alex, Priya, Marcus, Fatima, Lunga &amp; Yuki —<br>
  shipping open source on and around <a href="https://zocomputer.com">Zo Computer</a>.
  <br>
  <sub>Operated by <a href="https://github.com/CashlessConsumer">@CashlessConsumer</a> (srikanthlogic)</sub>
</p>

<p align="center">
  <a href="https://logicinczo.github.io/semantic-thinking/"><img src="https://img.shields.io/badge/Semantic_Thinking-blog-8B5CF6?style=flat-square" alt="Blog"></a>
  <a href="https://logicinczo.github.io/zai-usage/"><img src="https://img.shields.io/badge/zai--usage-docs-2563EB?style=flat-square" alt="zai-usage docs"></a>
  <a href="https://logicinczo.github.io/zo-cobrowse/"><img src="https://img.shields.io/badge/zo--cobrowse-docs-2EA44F?style=flat-square" alt="zo-cobrowse docs"></a>
  <a href="https://logicinczo.github.io/tamil-bench/"><img src="https://img.shields.io/badge/Tamil_Bench-scoreboard-FF6B6B?style=flat-square" alt="Tamil Bench"></a>
</p>

---

Work runs factory-style: every project carries a contract — **BRIEF → PLAN → ARCHITECTURE → PROGRESS → DELIVERABLES** — coordinated through a Discord control plane. The personas are agent roles; the repos are the output.

## ⚙️ Zo Computer Platform Tooling

| Repo | What it is |
|------|-----------|
| [`zo-kotlin`](https://github.com/LogicIncZo/zo-kotlin) | Kotlin SDK for Zo — `/zo/ask` SSE + conversations, and `api.zo.computer/mcp` JSON-RPC (104 agent tools) |
| [`zo-voice`](https://github.com/LogicIncZo/zo-voice) | Android voice client for Zo — hands-free voice in/out over streaming `/zo/ask` |
| [`zo-cobrowse`](https://github.com/LogicIncZo/zo-cobrowse) | Co-browsing browser extension powered by Zo — dual-channel: `/zo/ask` for AI, zo.space for data |
| [`zai-usage`](https://github.com/LogicIncZo/zai-usage) | Terminal CLI for Z.ai GLM Coding Plan usage — quota windows, model matrix, reset packs, cost runway. Zero-dep Bun/TS |
| [`zai-widget`](https://github.com/LogicIncZo/zai-widget) | Android home-screen widget for GLM Coding Plan quota — clock-style ring dial, runway ETA |
| [`ShowZo`](https://github.com/LogicIncZo/ShowZo) | AI agentic walkthrough video generator — URL + scenario → produced product video |
| [`zo-kvaesitso-plugin`](https://github.com/LogicIncZo/zo-kvaesitso-plugin) | Search your Zo workspace from the Kvæsitso Android launcher |
| [`zoqr`](https://github.com/LogicIncZo/zoqr) · [`zoqr-wedges`](https://github.com/LogicIncZo/zoqr-wedges) · [`zoqr-pages`](https://github.com/LogicIncZo/zoqr-pages) | QR toolchain: generator, wedges, published pages |
| [`skills`](https://github.com/LogicIncZo/skills) | Agent Skills Registry |

## 🧩 Swamp DuckDB Extensions

| Repo | What it is |
|------|-----------|
| [`swamp-duckdb`](https://github.com/LogicIncZo/swamp-duckdb) | DuckDB query model + datastore backend for the swamp extension system |
| [`swamp-extension-creator`](https://github.com/LogicIncZo/swamp-extension-creator) | Scaffolds, validates, and publishes other swamp extensions |
| [`swamp-sops-age`](https://github.com/LogicIncZo/swamp-sops-age) | SOPS + age vault extension — AES-256-GCM encrypted local secret management |
| [`swamp-zocc-extensions`](https://github.com/LogicIncZo/swamp-zocc-extensions) | @zocc extensions — Tor probe/fetch/crawl and the L0–L5 claim rubric |

## 🇮🇳 Tamil Computing & Language

| Repo | What it is |
|------|-----------|
| [`kalappai`](https://github.com/LogicIncZo/kalappai) | கலப்பை — Tamil-first open-source typing tutor PWA (Tamil99, InScript, Typewriter, Phonetic) |
| [`kalappai-cert`](https://github.com/LogicIncZo/kalappai-cert) | Certification service for Kalappai — W3C Verifiable Credentials, Open Badges 3.0 shape |
| [`tamil-bench`](https://github.com/LogicIncZo/tamil-bench) | A runnable exam for AI models in Tamil — API-only, published scoreboard |
| [`tamil-llm-eval`](https://github.com/LogicIncZo/tamil-llm-eval) | LLM-judged Tamil benchmark — morphology, proverbs, diglossia, syntax |
| [`SEA-HELM`](https://github.com/LogicIncZo/SEA-HELM) | Tamil-specific evaluation using SEA-HELM methodology |
| [`kanagasabai`](https://github.com/LogicIncZo/kanagasabai) | கனகசபை — Tamil Nadu policy research (Seyarkai Arasiyal) |

## 🏛️ Civic Data & Public-Interest Tech

| Repo | What it is |
|------|-----------|
| [`chennai-flood-undersight`](https://github.com/LogicIncZo/chennai-flood-undersight) | Oversight from below for Chennai's ₹107.2-cr flood-forecasting system — open-data audit + debt monitoring |
| [`parkwise-game`](https://github.com/LogicIncZo/parkwise-game) | ParkWise: Pay &amp; Display — 3D game + evidence bench countering smart-parking surveillance |
| [`no-parandhur`](https://github.com/LogicIncZo/no-parandhur) | A data-driven case against the Parandur greenfield airport project |
| [`agristack-farmers-voice`](https://github.com/LogicIncZo/agristack-farmers-voice) | Farmer-centric analysis of India's AgriStack |
| [`companies`](https://github.com/LogicIncZo/companies) | Documentary dossiers on every listed entity in India |
| [`world-bank-india`](https://github.com/LogicIncZo/world-bank-india) | World Bank India — Marxist data review |
| [`QuestCraft`](https://github.com/LogicIncZo/QuestCraft) | Make and play quests — AI-powered educational board game engine |

## 📝 Publishing & Experiments

| Repo | What it is |
|------|-----------|
| [`semantic-thinking`](https://github.com/LogicIncZo/semantic-thinking) | AI critique blog — structured reasoning recipes applied to the week's most consequential claims |
| [`swartzism`](https://github.com/LogicIncZo/swartzism) | A doctrine of information power, constructed from the record of Aaron Swartz |
| [`books`](https://github.com/LogicIncZo/books) | Source-controlled books with automated PDF publishing (pandoc + Eisvogel) |
| [`feedflow`](https://github.com/LogicIncZo/feedflow) · [`digest-tracker`](https://github.com/LogicIncZo/digest-tracker) | Topic tracking and digest generation |
| [`lagrange-job`](https://github.com/LogicIncZo/lagrange-job) | LLM-adaptive narrative RPG |
| [`dyk-api-saas`](https://github.com/LogicIncZo/dyk-api-saas) | Semantic search over Wikipedia DYK facts |
| [`claw-family`](https://github.com/LogicIncZo/claw-family) · [`OpenFlaw`](https://github.com/LogicIncZo/OpenFlaw) · [`WebArk`](https://github.com/LogicIncZo/WebArk) | Open-source AI agent framework guides and experiments |

---

<p align="center">
  <sub>Sister orgs: <a href="https://github.com/CCAgentOrg">CCAgentOrg</a> (open data · infrastructure accountability) · <a href="https://github.com/DigitalIndiaArchiver">DigitalIndiaArchiver</a> (DPI open-data archives)</sub>
</p>
