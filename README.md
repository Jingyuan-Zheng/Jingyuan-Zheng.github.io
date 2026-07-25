# Jingyuan's Website

This repository contains the generated static files for Jingyuan's bilingual personal website, including articles, open-source projects, technical notes, and a photo wall.

## Website addresses

- New domain: **[https://zjy.is-a.dev/](https://zjy.is-a.dev/)**
- Permanent GitHub Pages address: [https://jingyuan-zheng.github.io/](https://jingyuan-zheng.github.io/)

## Technology

- **Static site generator:** [Hugo](https://gohugo.io/) Extended
- **Theme:** [Hugo Theme Stack](https://github.com/CaiJimmy/hugo-theme-stack) v4.0.3
- **Languages:** English and Simplified Chinese
- **Frontend customization:** Hugo templates, SCSS, and TypeScript
- **Hosting:** GitHub Pages
- **Search discovery:** XML sitemaps and automated IndexNow submission

The Stack theme is extended with local layouts and components, including a customized homepage, photo wall, sharing tools, and an Apple-style dual-time-zone clock widget. Light and dark site themes, responsive layouts, localized navigation, and bilingual article pairs are handled within the Hugo build.

## Deployment

The website follows an automated static deployment workflow:

1. Website content and source changes are maintained in a private source repository.
2. A push to the source repository's main branch starts a GitHub Actions workflow.
3. GitHub Actions installs Hugo Extended and builds the complete static website.
4. The generated `public/` output is published to this repository's `main` branch.
5. GitHub Pages serves the result from the permanent address above.
6. After deployment, the generated sitemap is submitted through IndexNow to help search engines discover updated pages.

This repository is therefore a deployment target rather than the editable source project. Its generated HTML, CSS, JavaScript, images, and other files may be replaced by the next automated deployment and should not be edited directly.

---

# 小景的个人网站

这个仓库存放小景双语个人网站自动生成的静态文件，内容包括博客文章、开源项目、技术笔记和照片墙。

## 网站地址

- 新域名：**[https://zjy.is-a.dev/](https://zjy.is-a.dev/)**
- 永久 GitHub Pages 地址：[https://jingyuan-zheng.github.io/](https://jingyuan-zheng.github.io/)

## 技术架构

- **静态网站生成器：** [Hugo](https://gohugo.io/) Extended
- **主题：** [Hugo Theme Stack](https://github.com/CaiJimmy/hugo-theme-stack) v4.0.3
- **语言：** 英文与简体中文
- **前端定制：** Hugo 模板、SCSS 和 TypeScript
- **托管：** GitHub Pages
- **搜索发现：** XML Sitemap 与自动 IndexNow 提交

网站在 Stack 主题基础上使用本地布局和组件进行扩展，包括定制主页、照片墙、分享工具和苹果风格双时区时钟小组件。网站的亮色与暗色主题、响应式布局、本地化导航以及中英文文章对应关系都在 Hugo 构建过程中处理。

## 自动部署

网站采用自动化静态部署流程：

1. 网站内容与源码在私有源码仓库中维护。
2. 代码推送到源码仓库的 `main` 分支后，GitHub Actions 自动启动。
3. GitHub Actions 安装 Hugo Extended 并构建完整的静态网站。
4. 生成的 `public/` 内容被发布到本仓库的 `main` 分支。
5. GitHub Pages 通过上方的永久地址提供网站访问。
6. 部署完成后，自动通过 IndexNow 提交生成的 Sitemap，帮助搜索引擎发现更新页面。

因此，这个仓库是网站的部署目标，而不是用于日常编辑的源码项目。这里的 HTML、CSS、JavaScript、图片和其他生成文件都可能在下一次自动部署时被覆盖，请勿直接修改。
