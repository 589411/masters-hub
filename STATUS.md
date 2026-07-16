# STATUS — masters-hub（大師專家團 Hub）

**最後更新：** 2026-07-16
**線上：** https://masters.launchdock.app （單一 index.html 靜態頁）

## 一句話現況
5 大主題包、22 位大師打包成 Gemini Gem＋ChatGPT GPT，依任務挑一組專家點了就用；
另有 3 顆單顆即用職場工具。**2026-07-16 再加兩個知識分頁**：`📜 定律寶庫`（30 條管理定律與效應）
與 `📊 數據決策`（決策四層級＋11 種數據分析方法）。Gem/GPT 皆建在 **jjaimark1@gmail.com** 帳號、公開分享。

## 下一個具體動作 ⭐
✅ 全部上線完成，兩個新分頁已 push（2026-07-16）。站台 https://masters.launchdock.app/ live。
目前無待辦；下次要新增大師 → 在對應主題 `<section>` 內複製一張 `.card` 改連結；
新增定律 → 複製一張 `.law`；新增數據方法 → 複製一張 `.dm`。

## 分頁與卡片型別（改動速查）
- 工具卡 `.card`：有「開 Gem/GPT」按鈕。
- 定律卡 `.law`（金色左框、無按鈕）：位於 `#vault` 定律寶庫。
- 數據卡 `.dm`（青綠左框＋例子框）：位於 `#data` 數據決策地圖。
- 導覽 chip 在 `.nav`，每個 = 一個錨點分頁。

> 帳號提醒：repo 屬 **589411** 帳號，改 Pages 設定要用 589411 登入的 Chrome（JosephnJoy 帳號沒有 admin 權限、看不到 Settings）。

## 架構
- `index.html`：唯一內容檔（無建置流程，改它就是改站）。
- `CNAME`：`masters.launchdock.app`。
- 部署：GitHub Pages（master / root）＋ Cloudflare 子網域。

## 大師連結來源
所有 Gem（gemini.google.com/gem/…）與 GPT（chatgpt.com/g/…）連結直接寫在 index.html 的卡片裡。
要新增大師：在對應主題 `<section>` 內複製一張 `.card` 改連結即可。

## 已知坑
- Cloudflare CNAME 必須 **DNS only（灰雲）**，橘雲會與 GitHub SSL 打架。
- 顧客洞察 10 位大師的 Gem/GPT 沿用舊有連結；定價/品牌/談判/組織 12 位為 2026-07-10 新建。
