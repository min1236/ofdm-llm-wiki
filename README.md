# OFDM LLM Wiki × HTML 教學簡報

以 Karpathy 的 [LLM Wiki 概念](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) 為方法，建立 OFDM 初學者知識庫與教學簡報。

## 快速開啟
- 專案首頁：`index.html`
- Wiki：`wiki/index.html`
- HTML 簡報：`slides/index.html`（可按 ← →、空白鍵切換）
- 流程設計：`workflow.md`
- AI 維護規則：`AGENTS.md`
- 實作檢查紀錄：`logs/log.md`

## 來源與 Wiki 對應
| Wiki 頁面 | 使用來源 |
|---|---|
| introduction | S01, S02, S03 |
| orthogonality | S01, S03 |
| transceiver | S01, S02, S03 |
| cyclic-prefix | S01, S03, S04 |
| applications | S01, S05 |
| tradeoffs | S01, S03, S04 |

## GitHub Pages 設定
1. 建立公開 Repository，將此資料夾中的**檔案及資料夾**上傳到儲存庫根目錄。
2. GitHub Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save。
3. 之後首頁網址通常為 `https://<帳號>.github.io/<儲存庫名稱>/`。
4. 簡報：`https://<帳號>.github.io/<儲存庫名稱>/slides/`，Wiki：`.../wiki/`。

## 實作範圍聲明
`raw/S01~S05.md` 是對外部文件的**閱讀與整合筆記**，不是外部全文下載。此次是利用 LLM 在單次工作中輔助建立、互相引用、檢查與生成的示範，**不是已部署的持續自動化 Agent**。如課堂要求實際 agent 工具呼叫，可用 AGENTS.md 配合 Codex / Claude Code 再跑一次 Ingest/Query/Lint 並追加 log。
