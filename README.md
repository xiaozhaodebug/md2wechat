# 📝 Markdown 转公众号格式工具

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
</p>

<p align="center">
  <b>将 Markdown 一键转换为微信公众号格式的在线工具</b>
</p>

<p align="center">
  <a href="#特性">特性</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#使用指南">使用指南</a> •
  <a href="#在线演示">在线演示</a>
</p>

---

## ✨ 特性

- 🚀 **零配置** - 单 HTML 文件，无需安装，打开即用
- 📝 **Obsidian 支持** - 完美支持 Obsidian 的 `![[image.png]]` 图片语法
- 🖼️ **图片自动处理** - 自动加载本地图片并转为 Base64
- 📋 **一键复制** - 点击即可复制到公众号编辑器
- 🎨 **精美样式** - 内置公众号优化样式，所见即所得
- 💻 **实时预览** - 边写边看，即时渲染

## 🚀 快速开始

### 方式一：在线使用（推荐）

直接访问 GitHub Pages 在线版本：

👉 **[点击使用](https://xiaozhaodebug.github.io/md2wechat/)**

### 方式二：本地使用

1. 下载 `index.html` 文件
2. 双击打开即可使用

```bash
git clone https://github.com/xiaozhaodebug/md2wechat.git
cd md2wechat
open index.html
```

## 📖 使用指南

### 1. 选择图片目录

点击「选择目录」按钮，选择包含图片的文件夹（支持 `.png`, `.jpg`, `.jpeg`, `.gif`, `.webp`, `.svg` 等格式）

### 2. 粘贴 Markdown

在左侧编辑器粘贴你的 Markdown 内容，支持：

- 标准 Markdown 语法
- Obsidian 图片语法：`![[image.png]]`
- 代码块高亮
- 表格、引用、列表等

### 3. 一键复制

点击「一键复制到公众号」按钮，然后直接在公众号编辑器中粘贴即可！

## 🖼️ 支持的图片格式

| 格式 | 说明 |
|------|------|
| `![[image.png]]` | Obsidian 维基链接语法 |
| `![](image.png)` | 标准 Markdown 语法 |
| `![](./image.png)` | 相对路径 |

## 🎨 样式预览

转换后的文章包含以下优化样式：

- ✅ 标题层级样式（H1-H6）
- ✅ 代码块高亮（Atom One Dark 主题）
- ✅ 引用块美化
- ✅ 表格样式优化
- ✅ 列表缩进调整
- ✅ 链接样式优化

## 🛠️ 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式与动画
- **JavaScript (ES6+)** - 核心逻辑
- **[Marked.js](https://marked.js.org/)** - Markdown 解析
- **[Highlight.js](https://highlightjs.org/)** - 代码高亮

## 🤝 贡献

欢迎提交 Issue 和 PR！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📄 许可

本项目基于 [MIT](LICENSE) 许可证开源。

## 💬 交流

如果你有任何问题或建议，欢迎通过以下方式联系：

- 提交 [Issue](https://github.com/xiaozhaodebug/md2wechat/issues)
- 关注公众号：小昭debug

---

<p align="center">
  如果这个项目对你有帮助，请给个 ⭐ Star 支持一下！
</p>
