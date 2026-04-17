# Skill 总览

本仓库用于沉淀常用 skill 的分类与使用说明，便于统一查阅与复用。

## 快速导航

- 分类总结：[`skill.md`](./skill.md)

## Skill 列表（功能 + 安装方法）

| Skill | 主要功能 | 安装方法 |
|---|---|---|
| `openai-docs` | 用于 OpenAI 产品/API 的官方文档检索、模型选型、GPT-5.4 升级与 Prompt 升级指引。 | 系统内置可直接使用；如需在其他环境复用，建议通过 `skill-installer` 从仓库安装。 |
| `skill-creator` | 用于创建或更新 skill，把经验流程沉淀成可复用能力。 | 系统内置可直接使用；如需在其他环境复用，建议通过 `skill-installer` 从仓库安装。 |
| `skill-installer` | 用于将 skill 安装到 `$CODEX_HOME/skills`，支持精选列表和 GitHub 仓库来源。 | 系统内置可直接使用；用于安装其他 skill（包括私有仓库来源）。 |

## 安装示例（通用）

```bash
# 在 Codex 中调用 skill-installer，按提示从 curated list 或 GitHub 仓库安装
$skill-installer
```

> 注：不同 Codex 环境的安装入口名称可能略有差异，但目标路径一致为 `$CODEX_HOME/skills`。

