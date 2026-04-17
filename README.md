# Skill 总览

本仓库用于沉淀常用 skill 的分类、功能说明与安装方法，方便团队统一复用。

## 目录

- [快速导航](#快速导航)
- [Skill 功能总览](#skill-功能总览)
- [安装与使用](#安装与使用)
- [版本记录](#版本记录)

## 快速导航

- 分类总结文档：[`skill.md`](./skill.md)

## Skill 功能总览

| Skill | 功能定位 | 典型场景 | 安装方式 |
|---|---|---|---|
| `openai-docs` | OpenAI 官方文档检索、模型选型、GPT-5.4 升级与 Prompt 升级参考。 | 需要最新、可引用、官方来源的 OpenAI 技术信息。 | 常见为系统内置；也可通过 `skill-installer` 从仓库安装。 |
| `skill-creator` | 创建或更新 skill，将流程沉淀为可复用能力。 | 把团队经验标准化，形成可复用模板和执行步骤。 | 常见为系统内置；也可通过 `skill-installer` 从仓库安装。 |
| `skill-installer` | 将 skill 安装到 `$CODEX_HOME/skills`，支持 curated list 与 GitHub 仓库来源。 | 快速安装第三方 skill，或分发私有 skill。 | 系统内置能力；用于安装其他 skill。 |

## 安装与使用

### 通用安装步骤

```bash
# 在 Codex 环境调用安装能力
$skill-installer
```

### 从 GitHub 仓库安装（示例思路）

```bash
# 1) 选择 GitHub 仓库来源
# 2) 输入目标仓库地址
# 3) 安装到 $CODEX_HOME/skills
```

> 注：不同 Codex 环境中命令入口名称可能略有差异，但安装目标目录通常是 `$CODEX_HOME/skills`。

## 版本记录

- `v0.1.0`：初始化总览页，包含 3 个核心 skill 的功能与安装说明。
- `v0.2.0`：升级为文档化首页，新增目录锚点、安装示例与版本记录。

