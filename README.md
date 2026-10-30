# Tanyl Chou

多模型閘道、自架模型客戶端、可回滾的 VPS 加固。金鑰在執行時注入，原點位址不寫在公開頁。

Multi-model gateways, self-hosted model clients, and reversible VPS hardening. Keys are injected at runtime. Origin addresses stay off the public page.

[one@oece-x.com](mailto:one@oece-x.com) · [Telegram](https://t.me/oecelove_bot) · [oece-x.com](https://oece-x.com)

## 接案範圍

| | |
|---|---|
| 多模型閘道 | 七家廠商走同一套串流，配額在寫出之前檢查。One stream path. Quota is checked before the first byte. |
| 自架模型客戶端 | 金鑰留在伺服器。手機和桌面裝成 PWA。The key stays on the server. Phone and desktop install it as a PWA. |
| VPS 加固 | 先評分，再改。動 SSH 的步驟掛自動還原。Score first. SSH changes arm an auto-rollback timer. |
| Telegram 機器人 | 審核、翻譯、排程。失敗時沉默，不把半句草稿發出。Moderation, translation, schedules. A fragment is not sent. |

來信請寫語言、期限，以及要上線還是只交原始碼。

In the first email, say the language, the deadline, and whether you need it deployed or only the source.

## 公開庫怎麼讀

| 庫 | 打開它是為了看什麼 |
|---|---|
| [multi-llm-gateway](https://github.com/web3-ai-game/multi-llm-gateway) | 單一 Go 二進位。廠商註冊表、共用 SSE、檔位配額。One binary. Registry, shared SSE, tiered quotas. |
| [grok-council](https://github.com/web3-ai-game/grok-council) | 自架客戶端。八席專家的推理看得到，不是只給議長結論。You can read each expert, not only the chair. |
| [cursor-xai-gateway](https://github.com/web3-ai-game/cursor-xai-gateway) | Cursor 呼叫 xAI。金鑰不進 IDE。別名把上下文壓在上游上限內。The key stays out of the IDE. |
| [chain-query-proxy](https://github.com/web3-ai-game/chain-query-proxy) | 標準庫 Go。鏈白名單、每 IP 限速、快取。金鑰留在伺服器。Allowlist, per-IP limit, cache. |
| [vps-blue-panel](https://github.com/web3-ai-game/vps-blue-panel) | 單檔面板。32 項評分，SSH 可回滾。沒有從網路一鍵灌入的安裝器。No network installer. |
| [system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio) | 上面幾套的架構圖和流程。私有系統不附原始碼。Diagrams. Private systems stay private. |

## 用量

xAI 主控台，2026-09-28 至 2026-10-30。帳號名稱已遮。

xAI console, 28 Sep 2026 – 30 Oct 2026. Account name redacted.

| Tokens | Requests | Cached prompt |
|---|---|---|
| 16.84B | 1.55M | 88.5% |

13.8B cached / 15.6B prompt。讀法寫在 [system-design-portfolio](https://github.com/web3-ai-game/system-design-portfolio)。

<img src="assets/xai-usage-2026-09-28-to-2026-10-30.jpg" alt="xAI usage, 28 Sep 2026 to 30 Oct 2026" width="720" />
