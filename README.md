# AI 企業網站平台建立課程

本教材以「前行管顧科技企業網站」的實作流程驗證而成，適合沒有工程背景、希望用 AI 與 Codex 建立企業形象網站的學員。

## 課程成果

完成後，每位學員會有：

- 一個可在自己電腦預覽的 Astro 靜態企業網站。
- 一份品牌資料收集表、內容架構與設計確認稿。
- 一個 GitHub 私有備份庫，使用 GitHub Desktop 操作，不要求使用命令提示字元。
- 一個 Cloudflare Workers 免費部署網站。
- 一個綁定完成的正式網域（選配）。
- 一套「本機預覽 → 人工確認 → 備份 → 自動部署」的更新標準流程。
- 一套可安裝的既有網站 SEO／AI 搜尋更新模式。

## 教材順序

1. [01_學員手冊.md](01_學員手冊.md)：從零開始的逐步操作。
2. [02_講師操作手冊.md](02_講師操作手冊.md)：授課安排、示範與容易卡住的地方。
3. [03_提示詞庫.md](03_提示詞庫.md)：可直接貼給 Codex 的提示詞。
4. [04_檢查清單.md](04_檢查清單.md)：設計、上線與更新時的核對表。
5. [教材範本/企業形象網站資料收集表.md](教材範本/企業形象網站資料收集表.md)：交給客戶填寫的範本。
6. [學員啟動方式.md](學員啟動方式.md)：從 GitHub 安裝並以一句提示開始。
7. [skills/corporate-site-seo-ai-update/](skills/corporate-site-seo-ai-update/)：既有網站的本機盤點、更新與驗收 skill。

## 核心原則

1. 先收資料、後做設計；先看設計稿、後寫網站。
2. 任何改版都先在本機預覽、人工確認、GitHub 私有庫 Commit／Push，再由 Cloudflare 的 Git 自動建置公開；不得跳過 GitHub 直接部署。
3. 每個客戶各自使用獨立資料夾、GitHub 私有儲存庫、Cloudflare 專案與網域。
4. 形象網站優先使用 Markdown／JSON 內容，不為了方便而過早建立資料庫。
5. 發布前確認文案、圖片、商標、聯絡資料皆有使用權與核准。
6. SEO 與 AI 搜尋可見度從資料收集與本機驗收開始；不承諾排名或 AI 摘要收錄。

## 建議工具與費用

| 用途 | 工具 | 本課程設定 |
| --- | --- | --- |
| AI 協作 | Codex | 學員以自然語言提出需求 |
| 網站框架 | Astro | 靜態網站、速度快、維護單純 |
| 原始碼備份 | GitHub Desktop + 私有儲存庫 | 免費，避免命令列操作 |
| 發布 | Cloudflare Workers | 先使用免費方案 |
| 網域 | 學員既有註冊商（如 GoDaddy） | 僅在需要正式網址時設定 |
| 表單 | Google Forms | 免費、資料留在客戶帳號 |

> 本課程不啟用付費服務，也不在客戶確認前公開部署。

## 一鍵安裝課程 Skill

本庫公開後，學員只需在 Codex 對話框貼上以下一句，不必開啟命令提示字元，也不必登入講師的 GitHub 帳號：

```text
$skill-installer 請從 GitHub 儲存庫 kingcc09-maker/ai-corporate-site-course 安裝 AI 企業網站建置課程 Skill。
```

安裝完成後重新開啟 Codex 對話，即可使用 Skill 開始資料收集與設計流程。

## 一鍵安裝既有網站更新 Skill

既有網站要補做 SEO／AI 搜尋更新時，學員可直接貼上：

```text
$skill-installer 請從 GitHub 儲存庫 kingcc09-maker/ai-corporate-site-course 的 skills/corporate-site-seo-ai-update 安裝既有企業網站 SEO／AI 搜尋更新 Skill。
```

安裝後只需說明專案路徑，即可先取得本機盤點與更新清單；不會直接發布。

## GitHub 發布結構

此資料夾可直接作為 GitHub 範本庫。`skills/ai-corporate-site-course/` 是可安裝的 Codex Skill；其他 Markdown 是給學員閱讀、下載和授課使用的教材。課程公開前，須再次檢查其中沒有客戶資料、帳號、網域、圖片或任何機密資訊。

課程範本庫只負責發放教材與 Skill，**不是學員的網站儲存庫**。公開 Skill 的安裝不需要學員 GitHub 帳號；但每位學員仍須在建立客戶網站備份時，使用自己的 GitHub 帳號為每個客戶建立獨立的私有網站儲存庫。不可登入、共用或使用講師帳號。
