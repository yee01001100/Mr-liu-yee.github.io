# 🚀 我的个人博客

> 🌏 访问地址: [yee01001100.github.io](https://yee01001100.github.io)

欢迎来到我的个人博客项目仓库！这里记录了我的学习心得、技术分享以及生活随笔。本项目基于 **Hexo** 静态网站生成器，并使用 **Butterfly** 主题进行构建。

---

## 🛠️ 技术栈

本项目使用以下技术构建：

-   **核心框架**: [Hexo](https://hexo.io/zh-cn/) - 一个快速、简洁且高效的博客框架。
-   **主题**: [Butterfly](https://butterfly.js.org/) - 一款基于 Hexo 的 Material Design 风格主题，功能强大且美观。
-   **部署平台**: GitHub Pages
-   **编程语言**: Markdown, HTML, CSS, JavaScript, EJS/Pug (取决于主题模板)

## ✨ 主题特性

Butterfly 主题为本博客提供了丰富的功能支持：

-   **响应式设计**: 完美适配 PC、平板和移动端。
-   **代码高亮**: 支持多种代码高亮主题（如 Prism.js, Highlight.js）。
-   **评论系统**: 支持 Waline, Twikoo, Gitalk 等多种评论插件。
-   **SEO 优化**: 内置友好的 SEO 设置。
-   **暗黑模式**: 支持自动/手动切换深色模式。

## 📦 本地运行与开发

如果你想克隆本项目并在本地运行，请确保你已安装 [Node.js](https://nodejs.org/) 和 [Git](https://git-scm.com/)。

### 1. 安装 Hexo CLI

```bash
npm install -g hexo-cli
```

### 2. 克隆项目

```bash
git clone https://github.com/yee01001100/yee01001100.github.io.git
cd yee01001100.github.io
```

### 3. 安装依赖

```bash
npm install
```

### 4. 启动本地服务器

```bash
hexo server
# 或者简写
hexo s
```

启动后，在浏览器访问 `http://localhost:4000` 即可预览博客。

## 🚀 部署流程

本博客通常通过 GitHub Actions 自动部署，或者使用命令行手动部署。

### 手动部署命令

```bash
# 清理缓存
hexo clean

# 生成静态文件
hexo generate
# 或者简写
hexo g

# 部署到 GitHub Pages
hexo deploy
# 或者简写
hexo d
```
