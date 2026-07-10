# STATUS — masters-hub（大師專家團 Hub）

**最後更新：** 2026-07-10
**線上：** https://masters.launchdock.app （單一 index.html 靜態頁）

## 一句話現況
5 大主題包、22 位大師打包成 Gemini Gem＋ChatGPT GPT，依任務挑一組專家點了就用；
另有 3 顆單顆即用職場工具。Gem/GPT 皆建在 **jjaimark1@gmail.com** 帳號、公開分享。

## 下一個具體動作 ⭐
✅ 全部上線完成（2026-07-10）。頁面已轉 production（移除原型警示框與「設計說明／C 方案」memo）；
DNS check successful、**Enforce HTTPS 已啟用**、站台 https://masters.launchdock.app/ live。
目前無待辦；下次要新增大師 → 在對應主題 `<section>` 內複製一張 `.card` 改連結。

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
