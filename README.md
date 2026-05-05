# 🧠 Knowledge Vault

个人知识管理网页应用，专为算法工程师设计。

## 功能

- **Markdown 编辑** — 支持完整 Markdown 语法
- **LaTeX 公式** — 行内 `$E=mc^2$` 和块级 `$$\int f(x)dx$$`，基于 KaTeX
- **代码高亮** — highlight.js，GitHub 暗色主题
- **图片支持** — 拖拽/粘贴图片自动存入 IndexedDB
- **标签系统** — 侧边栏标签过滤
- **全文搜索** — 标题 + 标签搜索
- **导出/导入** — JSON 格式备份与恢复
- **响应式布局** — 桌面 + 移动端适配
- **暗色主题** — GitHub 配色方案

## 使用方式

直接在浏览器中打开 `index.html` 即可使用。也可部署到 GitHub Pages：

1. Fork 本仓库
2. Settings → Pages → Source: Deploy from a branch → main → / (root) → Save
3. 访问 `https://你的用户名.github.io/robot-kb`

## 技术栈

- Vanilla JS（无框架）
- [marked.js](https://marked.js.org/) — Markdown 渲染
- [KaTeX](https://katex.org/) — LaTeX 数学公式
- [highlight.js](https://highlightjs.org/) — 代码语法高亮
- IndexedDB — 本地持久化存储

## 本地开发

```bash
python3 -m http.server 8080
# 浏览器访问 http://localhost:8080
```
