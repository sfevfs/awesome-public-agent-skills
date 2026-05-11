# Awesome Public Agent Skills

A curated index of public AI agent skills, skill libraries, MCP servers, tool packs, and workflow templates.

本项目用于收集 GitHub 和公开网页上可复用的 AI Agent Skills。这里的 “skills” 不只包括已经封装好的智能体能力包，也包括可用于智能体的 MCP servers、工具集合、工作流模板和领域能力库。

## Contents

- [官方 Agent Skills 仓库](#官方-agent-skills-仓库)
- [社区 Agent Skills 合集](#社区-agent-skills-合集)
- [Claude / Anthropic Skills](#claude--anthropic-skills)
- [Copilot / Coding Agent Skills](#copilot--coding-agent-skills)
- [MCP Servers / Agent Tools](#mcp-servers--agent-tools)
- [Cloud / DevOps Skills](#cloud--devops-skills)
- [Coding / Software Engineering Skills](#coding--software-engineering-skills)
- [Data / Research / Document Skills](#data--research--document-skills)
- [安全与使用提示](#安全与使用提示)

---

## 官方 Agent Skills 仓库

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Anthropic Skills | Anthropic 公开的 Claude Skills 示例仓库，包含创意、技术任务、企业工作流、文档处理等 skills。 | Skill library | [Open](https://github.com/anthropics/skills) |
| Vercel Agent Skills | Vercel 官方 agent skills 集合，面向 AI coding agents，包含 React / Next.js 最佳实践等技能。 | Skill library | [Open](https://github.com/vercel-labs/agent-skills) |
| Google Skills | Google 官方 Agent Skills 仓库，面向 Google Cloud、Firebase、Gemini API、BigQuery、GKE 等技术。 | Skill library | [Open](https://github.com/google/skills) |
| Microsoft Skills | Microsoft 面向 Azure SDKs 和 Microsoft AI Foundry 的 agent skills、custom agents、AGENTS.md 模板和 MCP 配置。 | Skill library / MCP config | [Open](https://github.com/microsoft/skills) |

## 社区 Agent Skills 合集

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| VoltAgent Awesome Agent Skills | 社区维护的大型 Agent Skills 索引，收集官方团队和社区贡献的 agent skills。 | Awesome list | [Open](https://github.com/VoltAgent/awesome-agent-skills) |
| AI Agents Skills | 面向 Claude Code、GitHub Copilot、Cursor、Windsurf、Cline、Aider、Continue.dev 等 coding agents 的技能集合。 | Skill collection | [Open](https://github.com/hoodini/ai-agents-skills) |
| Awesome Claude Skills | Composio 维护的 Claude Skills、资源和工具列表，适合了解 Claude skill 生态。 | Awesome list | [Open](https://github.com/ComposioHQ/awesome-claude-skills) |

## Claude / Anthropic Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Anthropic Skills | Claude Skills 官方示例仓库，包含 `SKILL.md`、参考文件、脚本和复杂任务示例。 | Skill library | [Open](https://github.com/anthropics/skills) |
| Document Skills in Anthropic Skills | Anthropic Skills 仓库中包含 docx、pdf、pptx、xlsx 等文档创建与编辑能力示例。 | Document skill | [Open](https://github.com/anthropics/skills/tree/main/skills) |

## Copilot / Coding Agent Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Microsoft Skills | 面向 Azure SDKs、Microsoft AI Foundry 和 AI coding agents 的 skills、custom agents、AGENTS.md 模板和 MCP 配置。 | Coding agent skills | [Open](https://github.com/microsoft/skills) |
| Vercel Agent Skills | 面向 AI coding agents 的技能集合，适合收集前端、React、Next.js 和工程实践类 skills。 | Coding agent skills | [Open](https://github.com/vercel-labs/agent-skills) |
| AI Agents Skills | 面向多种 coding agents 的技能集合，支持 Claude Code、Copilot、Cursor、Windsurf、Cline、Aider 等。 | Coding agent skills | [Open](https://github.com/hoodini/ai-agents-skills) |

## MCP Servers / Agent Tools

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| GitHub MCP Server | GitHub 官方 MCP Server，让 AI agents 读取仓库、管理 Issues / PR、分析代码、处理工作流和自动化 GitHub 任务。 | MCP server | [Open](https://github.com/github/github-mcp-server) |
| Awesome MCP Servers | 大型 MCP servers 目录，收集可供 AI agents 连接文件系统、数据库、API、浏览器和外部服务的 MCP servers。 | MCP server list | [Open](https://github.com/punkpeye/awesome-mcp-servers) |

## Cloud / DevOps Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Google Skills | Google Cloud 官方 Agent Skills，覆盖 AlloyDB、BigQuery、Cloud Run、Cloud SQL、Firebase、Gemini API、GKE 等。 | Cloud skills | [Open](https://github.com/google/skills) |
| Microsoft Skills | 面向 Azure SDKs 和 Microsoft AI Foundry 的 agent skills 与 MCP 配置。 | Cloud skills | [Open](https://github.com/microsoft/skills) |

## Coding / Software Engineering Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Vercel React Best Practices Skill | Vercel Agent Skills 中的 React / Next.js 性能优化技能，适合 AI coding agent 做前端开发和代码审查。 | Coding skill | [Open](https://github.com/vercel-labs/agent-skills) |
| GitHub MCP Server | 让智能体管理仓库、Issues、PR、CI/CD、releases 和项目结构，适合软件工程自动化任务。 | MCP server | [Open](https://github.com/github/github-mcp-server) |

## Data / Research / Document Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Anthropic Document Skills | Anthropic Skills 中的文档处理 skills，可作为复杂文档生成、编辑和转换能力的参考。 | Document skill | [Open](https://github.com/anthropics/skills/tree/main/skills) |
| Awesome MCP Servers | 可以从该列表中筛选数据库、文件系统、搜索、浏览器、知识库和数据分析相关 MCP servers。 | MCP server list | [Open](https://github.com/punkpeye/awesome-mcp-servers) |

## 安全与使用提示

第三方 agent skills、MCP servers 和工具包在使用前都需要检查代码、依赖、权限和许可证。

建议记录以下信息：

| 字段 | 说明 |
|---|---|
| Name | skill 或工具名称 |
| Source | GitHub / 官方网站 / 文档页面 |
| Type | Skill / MCP server / Tool / Workflow / Template |
| Agent support | 支持 Claude、Copilot、Cursor、Gemini CLI、Codex CLI 等哪些 agent |
| License | MIT / Apache-2.0 / Unknown |
| Last update | 最近更新时间 |
| Risk note | 是否会访问本地文件、执行命令、调用外部 API、处理凭据 |
