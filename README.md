<div align="center">

# 🧠 OpenAI Codex 教程中文版

### 让中文开发者把 Codex 的 CLI / IDE / App / Cloud 全栈用进真实项目

> 💎 **不是官方文档的翻译，而是为中文新手重写的双路径教程：理解篇负责心智模型，官方篇负责事实基准——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/codex)
[![章节](https://img.shields.io/badge/章节-136_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/codex)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![事实基准](https://img.shields.io/badge/事实基准-OpenAI_官方文档-412991?style=for-the-badge)](https://developers.openai.com/codex)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/codex)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **官方文档不缺，中文版翻译也不缺，缺的是「能让中文新手真的读下去并用起来」的版本。**
>
> 这份教程基于 OpenAI 官方文档、`openai/codex` 仓库源码和发布记录重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 12 篇 **从原理到实战** 帮你建立心智模型，10 个分组的 **官方教程中文版** 覆盖 CLI / IDE / App / Cloud / 团队 / 实战场景全栈细节。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/codex) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/codex/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/codex/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/openai-codex-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 OpenAI Codex 学习入口 —— 一站把 CLI、IDE、App、Cloud 四种产品形态 × 心智模型 × 实战场景全讲透。

这是《AI 编程教程中文版》里的 OpenAI Codex 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/codex) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解 Codex 为什么需要审批与沙箱、上下文从哪里来 | **12 篇** | [开始 →](https://aiworkflowtutorials.com/docs/codex/understanding) |
| 📚 **官方教程中文版** | 想直接查 CLI / IDE / App / Cloud 命令、配置、价格与团队落地 | **124 篇** | [开始 →](https://aiworkflowtutorials.com/docs/codex/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：不是机翻，每篇按"先讲场景再讲原理"的顺序，避免官方文档跳跃式叙述
- 🧭 **四种产品形态全覆盖**：CLI / IDE 插件 / 桌面 App / 云端环境，告诉你在什么场景该用哪一种
- 📐 **第一性原理优先**：审批、沙箱、上下文工程、模型成本，先讲清"它为什么这样工作"再讲"怎么用"
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读官方教程中文版的「**新手必读 + 产品入口**」搞清楚 CLI / IDE / App / Cloud 的差异
2. 再读从原理到实战 **01-06**，建立 Codex 怎么读上下文、怎么完成一次任务、为什么要审批的心智模型
3. 回到真实项目，用一个小改动练习"先 plan 再 apply 再 verify"的闭环
4. 最后进入 **MCP / Skills / 模型成本控制 / 团队协作 / 云端环境**，把工具沉淀成可复用工作流

### 🧠 从原理到实战（12 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | Codex 是什么 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/what-is-codex) |
| 02 | 一次任务是怎么完成的 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/how-a-task-completes) |
| 03 | Codex 看到的上下文从哪里来 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/context-engineering) |
| 04 | 为什么 AGENTS.md 能改变 Codex 行为 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/agents-md-guide) |
| 05 | Codex 为什么需要审批和沙箱 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/sandbox-approval) |
| 06 | App、IDE、CLI、Cloud 怎么选 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/cli-app-ide-cloud) |
| 07 | 如何让 Codex 调用工具和访问数据 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/mcp-tools-guide) |
| 08 | Skills、Subagents、Hooks 解决什么问题 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/skills-subagents-hooks) |
| 09 | 如何控制模型、速度、成本和质量 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/model-cost-speed) |
| 10 | 团队协作和生产环境怎么落地 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/team-production) |
| 11 | 从理解到实战场景 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/from-theory-to-practice) |
| 12 | 一句话复盘 Codex 全貌 | [阅读 →](https://aiworkflowtutorials.com/docs/codex/understanding/complete-overview) |

### 📚 官方教程中文版（10 个分组 · 124 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **新手必读** | 第一次跑通 Codex 的最少必要操作 | 5 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/00-getting-started) |
| 🟦 **产品入口** | CLI / IDE / App / Cloud 四种形态选型与上手 | 25 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/01-products) |
| 🟡 **规则、安全与配置** | AGENTS.md / 沙箱 / 审批 / 配置文件 | 15 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/02-config-security) |
| 🟠 **扩展能力** | MCP / Skills / Subagents / Hooks | 10 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/03-extensions) |
| 🟣 **模型、价格与效率** | 选模型 / 控成本 / 提速度 | 6 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/04-model-pricing) |
| 🔵 **云端与远程环境** | Codex Cloud / 远程容器 / CI 集成 | 3 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/05-cloud-remote) |
| 🟤 **团队与集成** | 团队权限 / Slack / GitHub / 审计 | 14 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/06-team-integration) |
| 🟢 **学习路线** | 新手 / 进阶 / 团队 / 生产四条路径 | 6 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/07-learning-paths) |
| 🟧 **实战场景** | 重构 / 测试 / 调试 / 文档 / Code Review 全场景 | 37 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/08-scenarios) |
| ⚙️ **版本与迁移** | 历次重大版本变化与迁移要点 | 3 | [开始 →](https://aiworkflowtutorials.com/docs/codex/official/09-versions) |

### 💡 第一次在项目里用 Codex CLI

```text
你（对 Codex CLI）：

  我在 ~/projects/{repo}，先读 README、AGENTS.md（如果有）、package.json、tsconfig，
  告诉我这个项目是干什么的，主要模块怎么分工。
  接着提出三个最小的可改进点（每条不超过 1 行），
  我选一个之后你再写改动方案，我审批后再让沙箱里执行。
```

> 🎯 **重点是「先读、再说、审批、再执行」四步走**——AGENTS.md 是 Codex 行为的稳定锚点，先建立项目规则比逐个 prompt 微调更可控。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：OpenAI 文档结构调整 / `openai/codex` 仓发布的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/openai-codex-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + 真实项目里的 AGENTS.md / Skill / 配置模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
