# 九州 · 城市织造局

中国城市程序化 3D 生成器 —— 完全在浏览器中实时生成重庆、上海、西安、深圳、江南五座城市的三维沙盘。

- 在线访问：<https://springrain-tr.github.io/>
- 源码仓库：<https://github.com/springrain-tr/CityLoom>

## 说明

本仓库仅存放由 `npm run build` 生成的静态产物（Vite 构建），通过 GitHub Pages 发布。

- `index.html` — 页面入口
- `assets/` — 构建后的 JS / CSS
- `.nojekyll` — 跳过 Jekyll 处理，确保 `assets/` 原样发布

更新方式：在源码仓库执行 `npm run build`，将 `dist/` 内容同步到本仓库 `main` 分支根目录后推送。
