# 个人简历

简洁专业的中文个人简历网站，根据本人提供的实习简历整理，展示教育背景、专业技能、项目经历与荣誉证书。

- 网站：https://zh-0001.github.io/resume/
- 原生 HTML、CSS 与少量 JavaScript，无需安装依赖或构建。
- 支持手机、平板、电脑浏览，以及浏览器打印 / 另存为 PDF。
- 两个 AI 项目保留「基于 AI 生成」说明。

## 本地预览

直接打开 `index.html`，或在此目录运行 `python -m http.server 8080` 后访问 `http://localhost:8080`。

## 修改内容

编辑 `index.html` 更新简历，编辑 `styles.css` 调整样式。所有资源使用相对路径，兼容 GitHub Pages 项目路径。

## 发布

GitHub Actions 会在推送到 `main` 时部署静态站点。首次发布如未自动启用 Pages，请在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**，再重新运行 **Deploy resume to GitHub Pages** 工作流。

仓库包含公开的电话与邮箱；更新联系方式时请同步修改页面中的邮件链接、电话链接与展示文字。
