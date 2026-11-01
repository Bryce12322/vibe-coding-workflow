# Vibe Coding 工作流

一个面向 Codex 的中文 skill，帮助你从产品想法出发，逐步明确问题与范围、设计体验、实现功能，并通过真实操作验收。

## 工作方式

根据项目需要灵活使用七个阶段：明确问题、收敛范围、梳理交互与可行性、确定 UI、逐步实现、验收打磨和交付。已有的决定和实现会被保留，小改动不必走完整流程。

新建或明显改造 UI 时需要安装 `frontend-design` skill；其他技能按任务和实际可用情况引入。详细流程见 [SKILL.md](SKILL.md)。

## 安装

将本仓库克隆或下载到 Codex 的技能目录，目录名保持为 `vibe-coding-workflow`：

```bash
git clone https://github.com/Bryce12322/vibe-coding-workflow.git ~/.codex/skills/vibe-coding-workflow
```

重新打开 Codex 后，在对话中输入：

```text
$vibe-coding-workflow 帮我把一个产品想法做成可用的小产品，先从最关键的问题开始。
```

也可以直接描述你想做的产品；能否自动触发取决于所用客户端和技能配置。

## 文件

- `SKILL.md`：工作流及阶段要求。
- `references/`：项目记录、技能路由和验收指南。
- `agents/openai.yaml`：Codex 的显示和调用配置。

## 方法参考

流程参考了 Shape Up、Addy Osmani、Anthropic、Emil Kowalski、Simon Willison 和 Linear 的公开资料，具体链接见 [SKILL.md](SKILL.md#方法来源)。
