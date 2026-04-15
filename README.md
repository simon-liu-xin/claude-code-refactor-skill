# 🚀 Simon 大型代码库重构 Skill — Claude Code

> **专为 Claude Code 打造的 3M+ 行级代码重构交互式指南。**

[![GitHub stars](https://img.shields.io/github/stars/simon-liu-xin/claude-code-refactor-skill?style=for-the-badge&color=2563eb)](https://github.com/simon-liu-xin/claude-code-refactor-skill)
[![License](https://img.shields.io/github/license/simon-liu-xin/claude-code-refactor-skill?style=for-the-badge)](LICENSE)
[![Single File](https://img.shields.io/badge/Single_File-Portable-success?style=for-the-badge&logo=html5)](index.html)

---
<img width="1105" height="736" alt="image" src="https://github.com/user-attachments/assets/1fc8f610-a651-48bb-b058-8c77696c807d" />

## 💡 为什么需要这个工具？

在面对数百万行代码的遗留系统（Legacy Code）时，直接使用 AI 进行重构往往会遇到：
- **上下文爆炸**：AI 读取了太多无关文件导致“断片”。
- **不敢动旧代码**：缺乏测试保护，重构即线上故障。
- **缺乏系统性**：东改西改，没有形成长效的治理机制。

**Simon-Refactor-Skill** 将复杂的重构工程拆解为 **4 个阶段、12 个标准步骤**，并提供开箱即用的 Claude Code 提示词（Prompts）和子智能体（Sub-agents）配置。

---

## 🌟 核心特性

- 🛠 **交互式任务卡座**：实时记录重构进度，标记已完成步骤。
- 🤖 **经过验证的 Prompts**：针对降低圈复杂度、消除重复代码等场景深度优化。
- 📦 **零依赖单文件**：无需安装，双击 `index.html` 即可在浏览器中使用。
- 🛡 **安全优先**：内置特征化测试（Characterization Test）与 Git 安全基线策略。
- ⚡ **并行策略**：指导如何利用 Git Worktrees 与 Claude 实例并行重构。

---

## 🔗 立即使用

**👉 [点击此处查看在线演示 (GitHub Pages)](https://simon-liu-xin.github.io/claude-code-refactor-skill/)**

或者克隆到本地：
```bash
git clone https://github.com/simon-liu-xin/claude-code-refactor-skill.git
open index.html
