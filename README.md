# 骑迹 · 骑行追踪

用手机浏览器 GPS 实时追踪骑行路线、记录速度与距离的 PWA。

## 本地开发

直接用浏览器打开 `index.html` 即可预览。

## 部署到 GitHub + Netlify

1. 在 GitHub 建一个公开仓库（如 `cycled`）
2. 关联并推送：
   ```bash
   cd /Users/hanl/Documents/Codex/2026-06-24/new-chat/outputs/cycle-web
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. 打开 https://app.netlify.com → Add new site → Import from Git
4. 选 GitHub → 授权 → 找到你的仓库
5. 部署设置保持默认 → Deploy

之后每次 `git push`，Netlify 自动更新。
