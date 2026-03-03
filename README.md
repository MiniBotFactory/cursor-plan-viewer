# Cursor Plan Viewer | 开发计划阅读器

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Status](https://img.shields.io/badge/status-stable-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-Web-brightgreen.svg)]()

*English | [中文](#中文)*

</div>

---

## English

### About The Project

**Cursor Plan Viewer** is a web-based tool for reading and browsing Cursor IDE's development plans. It provides an intuitive interface to explore project plans exported as ZIP files or stored in local directories.

### Features

- 📦 **ZIP File Import** - Upload Cursor Plan exported ZIP files directly
- 📂 **Directory Support** - Select local directories containing plan files
- 📊 **Dashboard Overview** - Visual summary of milestones and tasks
- 📖 **Rich Markdown Rendering** - Tables, code blocks, headers, and more
- 🔍 **Smart Categorization** - Auto-detect task types (TASK-*, PLAN, CONFIG, etc.)
- 💬 **Feedback System** - Collect user feedback for plan improvement
- 🌙 **Dark Theme** - Developer-friendly dark UI

### Quick Start

```bash
# Clone or download this project
cd /path/to/project

# Start a local server (Python)
python3 -m http.server 8080

# Or using Node.js
npx serve .
```

Then open http://localhost:8080/plan-viewer.html in your browser.

### Usage

1. **Upload ZIP** - Click "上传 ZIP 文件" to select a Cursor Plan exported ZIP file
2. **Or Select Directory** - Click "选择本地目录" to choose a folder with plan files
3. **Browse Plans** - Use the sidebar to navigate between files
4. **View Details** - Click any file to view its content with rich formatting
5. **Dashboard** - Click "概览" tab to see project milestones and statistics

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Escape` | Return to upload page |
| Click file | View file content |

### Project Structure

```
.
├── plan-viewer.html   # Main application (single-page)
├── plans.zip          # Sample plan file (for testing)
├── README.md          # Bilingual README
└── LICENSE            # MIT License
```

### Technologies

- Pure HTML/CSS/JavaScript (no build required)
- [JSZip](https://stuk.github.io/jszip/) for ZIP handling
- Google Fonts (Noto Sans SC, Space Grotesk, JetBrains Mono)

---

## 中文

### 项目简介

**Cursor Plan Viewer** 是一款基于 Web 的开发计划阅读工具，专为浏览 Cursor IDE 导出的开发计划而设计。它提供直观的界面，让用户可以轻松探索和分析项目计划。

### 主要功能

- 📦 **ZIP 文件导入** - 直接上传 Cursor Plan 导出的 ZIP 文件
- 📂 **目录支持** - 选择包含计划文件的本地目录
- 📊 **仪表盘概览** - 可视化展示里程碑和任务统计
- 📖 **Markdown 渲染** - 支持表格、代码块、标题等丰富格式
- 🔍 **智能分类** - 自动识别任务类型（TASK-*、PLAN、CONFIG 等）
- 💬 **反馈系统** - 收集用户反馈用于改进计划
- 🌙 **深色主题** - 开发者友好的深色界面

### 快速开始

```bash
# 进入项目目录
cd /path/to/project

# 启动本地服务器（Python）
python3 -m http.server 8080

# 或使用 Node.js
npx serve .
```

然后在浏览器中打开 http://localhost:8080/plan-viewer.html

### 使用方法

1. **上传 ZIP** - 点击"上传 ZIP 文件"选择 Cursor Plan 导出的 ZIP 文件
2. **或选择目录** - 点击"选择本地目录"选择包含计划文件的文件夹
3. **浏览计划** - 使用侧边栏在文件之间导航
4. **查看详情** - 点击任意文件查看其内容和格式
5. **仪表盘** - 点击"概览"标签查看项目里程碑和统计信息

### 键盘快捷键

| 按键 | 功能 |
|-----|------|
| `Escape` | 返回上传页面 |
| 点击文件 | 查看文件内容 |

### 项目结构

```
.
├── plan-viewer.html   # 主应用程序（单页应用）
├── plans.zip          # 示例计划文件（用于测试）
├── README.md          # 双语说明文档
└── LICENSE            # MIT 许可证
```

### 技术栈

- 纯 HTML/CSS/JavaScript（无需构建）
- [JSZip](https://stuk.github.io/jszip/) 用于处理 ZIP 文件
- Google Fonts（Noto Sans SC、Space Grotesk、JetBrains Mono）

---

## License | 许可证

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

本项目基于 MIT 许可证开源 - 详见 [LICENSE](./LICENSE) 文件。

---

<div align="center">

*Star ⭐ this project if you find it helpful!*

*如果觉得有用，请给这个项目一个星星！*

</div>

<p align="center">
  <a href="#readme-top">Back to top | 返回顶部</a>
</p>
