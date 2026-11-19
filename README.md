# APEX — 彎道疾行

一個以 Three.js 製作的單頁 3D 賽車原型，使用 GitHub Actions 自動發布至 GitHub Pages。

## 操作方式

- `↑` / `W`：加速
- `↓` / `S`：煞車／倒車
- `←` / `A`、`→` / `D`：轉向
- `Space`：手煞車
- `R`：重置賽車與圈數

遊戲使用固定版本的 Three.js CDN 模組；首次載入需要網路連線。

## 發布

推送至 `main` 分支後，`.github/workflows/pages.yml` 會透過 GitHub Pages Actions 發布網站。首次發布前，請在 repository 的 **Settings → Pages** 將 **Build and deployment → Source** 設為 **GitHub Actions**。