<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f35,100:0f2444&height=220&section=header&text=Tanyl%20Chou&fontSize=65&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=AI%20systems%20%C2%B7%20multi-model%20gateways%20%C2%B7%20GCP%20%C2%B7%20blue-team%20tooling&descAlignY=60&descColor=8b949e" />

[![Email](https://img.shields.io/badge/one%40oece--x.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:one@oece-x.com)
[![Telegram](https://img.shields.io/badge/@oecelove__bot-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/oecelove_bot)
[![Site](https://img.shields.io/badge/oece--x.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://oece-x.com)

</div>

---

## Production usage

xAI console, **28 Sep 2026 – 30 Oct 2026**. Team id and account name are redacted. The right-hand window from the original capture is not included.

| Tokens | Requests | Cached prompt share |
|---|---|---|
| **16.84B** | **1.55M** | **88.5%** |

Cached prompt tokens were 13.8B. Uncached prompt tokens were 1.8B. 13.8 / 15.6 = 88.5%. Text spend on the same export was $19,067 of $24,143.

<img src="assets/xai-usage-2026-09-28-to-2026-10-30.jpg" alt="xAI usage console, 28 Sep 2026 to 30 Oct 2026, account name redacted" width="100%" />

Architecture for the systems behind this bill: **[system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)**.

---

## About

I design and run multi-model chat gateways, a self-hosted Grok client, Telegram bots, and reversible VPS blue-team tooling.

Languages in production: Go, Python, TypeScript, JavaScript, Bash. Deploy path is usually a single binary or a container, behind Cloudflare, with secrets injected at runtime and kept out of the browser.

公開作品都在下面。私有系統的架構、SSE 併發、專家議會與用量記帳寫在 [system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)，原始碼不開放。

---

## Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## Pinned work

<table>
<tr>
<td width="50%">

### [system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)

Architecture and benchmarks for the private production systems: multi-model SSE gateway, MoE expert council, Cursor-to-xAI gateway, interpreter bot.

No source. Diagrams and numbers only.

</td>
<td width="50%">

### [vps-guard](https://github.com/web3-ai-game/vps-guard)

Tails `auth.log` and nginx, bans through UFW, sends Telegram alerts, and gates the ops panel behind a PIN.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### [ebook-to-md](https://github.com/web3-ai-game/ebook-to-md)

Ebook to Markdown with OCR, LLM structure detection, resume, and dedup. The repo notes **5,153** documents processed.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
<td width="50%">

### [chat-distill-pipeline](https://github.com/web3-ai-game/chat-distill-pipeline)

Pulls local and cloud files, distills at low temperature, redacts, and exports JSONL for a vector store.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### [eldercare-ai-bot](https://github.com/web3-ai-game/eldercare-ai-bot)

Two Telegram bots for family eldercare. Shared memory, model routing, and a multi-model cross-check. Docker Compose.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
<td width="50%">

### [NYCKING](https://github.com/web3-ai-game/NYCKING)

Translation PWA for Chinese, English, Thai, Lao, and Burmese. Voice and text. Provider keys stay on the API server.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
</tr>
</table>

---

## Contract work

| Area | What I ship |
|---|---|
| AI applications | Multi-model gateways, knowledge bases, chat engines, bring-your-own-key setups |
| Gateways and quotas | OpenAI-compatible fronts, tiered quotas, per-user and per-model cost ledgers |
| Go / Python backends | Single-binary APIs, billing controls, data pipelines |
| DevSecOps | Log monitoring, auto-ban, reversible hardening, honeypot alerts |
| Telegram bots | Moderation, translation, review queues, scheduled jobs |
| Web apps | React, Next.js, Vite, Firebase, i18n |
| Automation | Shell deploy tooling, distillation pipelines, monitors |

<div align="center">

[![Email](https://img.shields.io/badge/one%40oece--x.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:one@oece-x.com)
[![Telegram Bot](https://img.shields.io/badge/@oecelove__bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/oecelove_bot)

</div>

---

<div align="center">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=web3-ai-game&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

<sub>DeepWeay Labs</sub>

</div>
