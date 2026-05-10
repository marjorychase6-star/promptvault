# PromptVault

**Prompt 版本管理工具** — 轻量、离线可用、双模操作（浏览器 UI + AI Agent 对话管理）。

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-success)
![PWA](https://img.shields.io/badge/PWA-ready-orange)
![i18n](https://img.shields.io/badge/i18n-zh%2Fen-blue)

---

## 功能

| 功能 | 说明 |
|------|------|
| 📋 Prompt 库管理 | 创建、编辑、搜索、删除 prompt |
| 🔄 版本控制 | 多版本管理，自动递增版本号，预览历史版本 |
| 📊 版本对比 | 行级 diff，高亮显示新增/删除内容 |
| 🧪 实时测试 | 选择版本 + 输入测试问题，调用真实 API 验证 prompt 效果 |
| ⚙️ API 配置 | OpenAI 兼容格式（支持 DeepSeek、通义千问、MiniMax 等） |
| ↔️ 中英文切换 | 一键切换界面语言 |
| 🌗 深色/浅色主题 | 双主题切换 |
| 📦 数据导入/导出 | JSON 完整备份 / Markdown 导出 |
| 📱 PWA 支持 | 可安装为独立应用，离线可用 |

## 快速使用

### 浏览器模式

直接访问：**[https://marjorychase6-star.github.io/promptvault/](https://marjorychase6-star.github.io/promptvault/)**

### Agent 模式（Coding Agent）

将 `skills/SKILL.md` 添加为 Agent 的 skill，即可通过对话管理所有 prompt 操作，支持创建、版本控制、diff 对比、导出等功能。

## 技术栈

- 纯 HTML/CSS/JavaScript（单文件，无框架依赖）
- PWA (Service Worker + Manifest)
- 本地存储 (localStorage)
- i18n 中英文国际化
- 兼容 PWA 安装

## 许可

MIT
