<div align="right">
  <a href="#-中文">🇨🇳 中文</a> | <a href="#-english">🇬🇧 English</a>
</div>

---

# PromptVault v1.1

**Prompt 版本管理工具 / Prompt Version Management Tool**

轻量、离线可用、双模操作（浏览器 UI + AI Agent 对话管理）。

Lightweight, offline-capable, dual-mode operation (Browser UI + AI Agent conversation).

![Version](https://img.shields.io/badge/version-1.1-brightgreen)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-success)
![PWA](https://img.shields.io/badge/PWA-ready-orange)
![i18n](https://img.shields.io/badge/i18n-zh%2Fen-blue)

---

## 🇨🇳 中文

### v1.1 新增功能

| 功能 | 说明 |
|------|------|
| 🤖 AI 辅助修改 | 调用已配置 API，由 LLM 根据优化方向自动改进 prompt 内容 |
| 📜 测试历史 | 历史测试结果持久化保存，可折叠查看、重新浏览、导出 HTML/MD |
| 📋 一键复制 | 编辑区一键复制当前 prompt 内容到剪贴板 |
| 📤 测试结果导出 | 测试结果支持导出为 HTML / Markdown 文件 |
| 🔄 版本选择测试 | 运行测试时可选择任意历史版本作为 system prompt |

### 完整功能

| 功能 | 说明 |
|------|------|
| 📋 Prompt 库管理 | 创建、编辑、搜索、删除 prompt |
| 🔄 版本控制 | 多版本管理，自动递增版本号，预览历史版本 |
| 📊 版本对比 | 行级 diff，高亮显示新增/删除内容 |
| 🧪 实时测试 | 选择版本 + 输入测试问题，调用真实 API 验证 prompt 效果 |
| 🤖 AI 辅助修改 | 输入优化方向，LLM 自动改进 prompt（使用内置专家提示词） |
| 📜 测试历史 | 测试结果持久化，支持折叠查看与导出 |
| ⚙️ API 配置 | OpenAI 兼容格式（支持 DeepSeek、通义千问、MiniMax 等） |
| ↔️ 中英文切换 | 一键切换界面语言 |
| 🌗 深色/浅色主题 | 双主题切换 |
| 📦 数据导入/导出 | JSON 完整备份 / Markdown 导出 |
| 📱 PWA 支持 | 可安装为独立应用，离线可用 |

### 快速使用

**浏览器模式** — 直接访问：[https://marjorychase6-star.github.io/promptvault/](https://marjorychase6-star.github.io/promptvault/)

**Agent 模式（Coding Agent）** — 将 `skills/SKILL.md` 添加为 Agent 的 skill，即可通过对话管理所有 prompt 操作。

### 技术栈

- 纯 HTML/CSS/JavaScript（单文件，无框架依赖）
- PWA（Service Worker + Manifest）
- 本地存储（localStorage）
- i18n 中英文国际化

---

## 🇬🇧 English

### What's New in v1.1

| Feature | Description |
|---------|-------------|
| 🤖 AI Assist | Use configured API to auto-improve prompts via LLM with built-in expert prompt engineering prompt |
| 📜 Test History | Persistent test result history, collapsible review, re-view and export HTML/MD |
| 📋 Copy Button | One-click copy current prompt content to clipboard from the editor |
| 📤 Export Results | Test results exportable as HTML / Markdown files |
| 🔄 Version Select for Test | Choose any historical version as system prompt when running tests |

### Full Features

| Feature | Description |
|---------|-------------|
| 📋 Prompt Library | Create, edit, search, delete prompts |
| 🔄 Version Control | Multi-version management, auto-increment, preview history |
| 📊 Diff Comparison | Line-level diff with added/removed highlighting |
| 🧪 Real-time Testing | Select version + enter test question, call real API |
| 🤖 AI Assist | Enter optimization direction, LLM auto-improves prompt (built-in expert prompt) |
| 📜 Test History | Persistent results with collapsible review and export |
| ⚙️ API Config | OpenAI compatible (DeepSeek, Qwen, MiniMax, etc.) |
| ↔️ Language Switch | One-click Chinese/English toggle |
| 🌗 Dark/Light Theme | Dual theme support |
| 📦 Import/Export | JSON full backup / Markdown export |
| 📱 PWA Support | Installable as standalone app, offline-ready |

### Quick Start

**Browser Mode** — Visit: [https://marjorychase6-star.github.io/promptvault/](https://marjorychase6-star.github.io/promptvault/)

**Agent Mode (Coding Agent)** — Add `skills/SKILL.md` as your agent's skill to manage all prompt operations via conversation.

### Tech Stack

- Pure HTML/CSS/JavaScript (single file, no framework)
- PWA (Service Worker + Manifest)
- localStorage persistence
- i18n Chinese/English

### Change Log

**v1.1** (2026-05-12)
- AI Assist: LLM-powered prompt optimization with built-in expert prompt engineering prompt
- Test History: persistent history with collapsible review, click-to-view, HTML/MD export
- Copy button, result export (HTML/MD), version select for testing
- UI refinements: button layout, editor header restructuring

**v1.0** (2026-05-10)
- Initial release: prompt library, version control, diff comparison, mock testing
- API configuration, PWA support, i18n zh/en, dark/light themes
- JSON import/export, Markdown export

---

## 许可 / License

MIT
