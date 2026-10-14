# 三日分化 3D 动作要领

推 / 拉 / 腿三天训练计划的 3D 动作演示站点。单文件静态页面（`index.html`），
3D 引擎 three.js 与字体由 CDN 加载，无需构建步骤。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（例如 `workout-3d-guide`），可见性选 Public。
2. 把本文件夹里的 `index.html`、`.nojekyll`、`README.md` 上传到仓库根目录（Add file → Upload files）。
3. 打开仓库的 Settings → Pages，Source 选 "Deploy from a branch"，Branch 选 `main`，文件夹选 `/ (root)`，保存。
4. 等待约 1 分钟，页面会出现在 `https://<你的用户名>.github.io/<仓库名>/`。

## 本地预览

直接双击 `index.html` 即可在浏览器打开（需要联网以加载 three.js）。
