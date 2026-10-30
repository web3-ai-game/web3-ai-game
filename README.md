<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=168&section=header&text=Tanyl%20Chou&fontSize=52&fontColor=e6edf3&animation=fadeIn&fontAlignY=36&desc=AI%20systems%20%C2%B7%20Go%20%C2%B7%20Python%20%C2%B7%20Taiwan%20%26%20remote&descAlignY=62&descSize=16&descColor=8b949e" width="100%" alt="Tanyl Chou" />

接案範圍：多模型閘道、自架模型客戶端、可回滾的 VPS 加固、Telegram 機器人。<br/>
Contract work: multi-model gateways, self-hosted model clients, reversible VPS hardening, Telegram bots.

<br/>

[![Email](https://img.shields.io/badge/one%40oece--x.com-21262d?style=flat-square&logo=gmail&logoColor=e6edf3)](mailto:one@oece-x.com)
[![Telegram](https://img.shields.io/badge/%40oecelove__bot-21262d?style=flat-square&logo=telegram&logoColor=e6edf3)](https://t.me/oecelove_bot)
[![Site](https://img.shields.io/badge/oece--x.com-21262d?style=flat-square&logo=googlechrome&logoColor=e6edf3)](https://oece-x.com)
[![Location](https://img.shields.io/badge/Remote-21262d?style=flat-square&logo=googlemaps&logoColor=e6edf3)](https://github.com/web3-ai-game)

</div>

## 正式用量

xAI 主控台，**2026-09-28 至 2026-10-30**。團隊 ID 和帳號名稱已遮。原圖右半的私人視窗沒有放進來。

xAI console, **28 Sep 2026 – 30 Oct 2026**. Team id and account name are redacted. The private window on the right of the original capture is not included.

| Tokens | Requests | 快取提示詞占比 Cached prompt share |
|---|---|---|
| **16.84B** | **1.55M** | **88.5%** |

快取提示詞 13.8B，未快取提示詞 1.8B。13.8 / 15.6 = 88.5%。同一份匯出的文字花費是 $19,067，總花費 $24,143。

Cached prompt tokens were 13.8B. Uncached prompt tokens were 1.8B. 13.8 / 15.6 = 88.5%. Text spend on the same export was $19,067 of $24,143.

<img src="assets/xai-usage-2026-09-28-to-2026-10-30.jpg" alt="xAI usage, 28 Sep 2026 to 30 Oct 2026, account name redacted" width="100%" />

這張帳單後面的架構在 **[system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)**。對應的公開程式在下面六個庫。

The architecture behind this bill is in **[system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)**. The public code is the six repositories below.

## 我做什麼

我做會上線的系統，不是示範頁。金鑰在執行時注入，不進瀏覽器，不進 git。對外主機走 Cloudflare 代理，原點位址不寫在公開頁。

I ship systems that stay up. Secrets are injected at runtime. They do not enter the browser, and they do not enter git. Public hosts sit behind Cloudflare. Origin addresses are not on this page.

正式環境用過的語言：Go、Python、TypeScript、JavaScript、Bash。部署通常是單一二進位或一個容器。

Languages in production: Go, Python, TypeScript, JavaScript, Bash. A deploy is usually one binary or one container.

## 公開作品

GitHub 的釘選要在網頁上手動設定。下面這六個是我希望首頁顯示的庫。

GitHub pins are set in the website UI. These six are the repositories I want on the front page.

<table>
<tr>
<td width="50%">

### [multi-llm-gateway](https://github.com/web3-ai-game/multi-llm-gateway)

單一 Go 二進位。七家廠商，同一套 SSE，檔位配額，管理後台。

One Go binary. Seven vendors, one SSE writer, tiered quotas, an admin panel.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

</td>
<td width="50%">

### [grok-council](https://github.com/web3-ai-game/grok-council)

自架 Grok 客戶端。官方多智能體直通，加上看得到推理過程的八席專家議會。

Self-hosted Grok client. Official multi-agent passthrough, plus an 8-seat council whose reasoning you can read.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### [cursor-xai-gateway](https://github.com/web3-ai-game/cursor-xai-gateway)

LiteLLM 代理。Cursor 呼叫 xAI，金鑰不進 IDE。別名把上下文壓在上游上限之內。

LiteLLM proxy. Cursor calls xAI. The key stays out of the IDE. Aliases keep context under the upstream cap.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
<td width="50%">

### [chain-query-proxy](https://github.com/web3-ai-game/chain-query-proxy)

標準庫 Go 代理。鏈上查詢的白名單、每 IP 令牌桶、快取、2MB 讀取上限。金鑰留在伺服器。

Stdlib Go proxy. Chain allowlist, a per-IP token bucket, a cache, and a 2MB read cap. The key stays on the server.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### [vps-blue-panel](https://github.com/web3-ai-game/vps-blue-panel)

單檔藍隊面板。32 項評分。SSH 變更掛自動還原計時器。蜜罐資料留在本機。沒有從網路一鍵灌入的安裝器。

Single-file blue-team panel. A 32-point score. SSH changes arm an auto-rollback timer. Honeypot data stays on the box. No network installer.

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</td>
<td width="50%">

### [system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)

私有正式系統的架構筆記：SSE 閘道、專家議會、Cursor 閘道、口譯機器人。沒有原始碼。

Architecture notes for the private production systems: the SSE gateway, the council, the Cursor gateway, the interpreter bot. No source.

</td>
</tr>
</table>

## 接案

| 範圍 | 我會交付什麼 |
|---|---|
| AI 應用 | 多模型閘道、知識庫、對話引擎、自備金鑰。Multi-model gateways, knowledge bases, chat engines, bring-your-own-key. |
| 閘道與配額 | OpenAI 相容入口、檔位配額、依使用者和模型記帳。OpenAI-compatible fronts, tiered quotas, per-user and per-model ledgers. |
| Go / Python 後端 | 單一二進位 API、計費控制、資料管線。Single-binary APIs, billing controls, data pipelines. |
| 維運安全 | 日誌監控、自動封鎖、可回滾加固、蜜罐告警。Log monitoring, auto-ban, reversible hardening, honeypot alerts. |
| Telegram 機器人 | 審核、翻譯、佇列、排程。Moderation, translation, review queues, scheduled jobs. |
| 網頁 | React、Next.js、Vite、Firebase、多語。React, Next.js, Vite, Firebase, i18n. |

回信請寄 one@oece-x.com，或從 Telegram [@oecelove_bot](https://t.me/oecelove_bot) 開始。請寫語言、期限，以及要上線還是只交原始碼。

Write to one@oece-x.com, or start at Telegram [@oecelove_bot](https://t.me/oecelove_bot). Say the language, the deadline, and whether you need it deployed or only the source.

## 技術棧

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<div align="center">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=web3-ai-game&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=e6edf3&text_color=8b949e)

<sub>DeepWeay Labs · Remote</sub>

</div>
