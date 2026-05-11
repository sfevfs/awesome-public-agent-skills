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
| Agent Skills Specification | Agent Skills 开放格式与规范入口，用于了解 `SKILL.md`、目录结构、元数据和可移植 skill 的基本标准。 | Specification / Standard | [Open](https://github.com/agentskills) |
| Anthropic Skills | Anthropic 公开的 Agent Skills 示例仓库，包含文档、表格、PDF、PPT、网页测试、MCP 构建、前端设计等 skills。 | Skill library | [Open](https://github.com/anthropics/skills) |
| OpenAI Skills | OpenAI / Codex skills 目录，包含文档、PDF、表格、截图、语音、Sora、Playwright、安全审查、部署等 skills。 | Skill library | [Open](https://github.com/openai/skills) |
| Microsoft Skills | Microsoft 面向 Azure SDKs、Microsoft Foundry、M365 agents、AGENTS.md、MCP 配置和 coding agents 的 skills 仓库。 | Skill library / MCP config | [Open](https://github.com/microsoft/skills) |
| Google Skills | Google 官方 Agent Skills 仓库，覆盖 Google Cloud、BigQuery、Cloud Run、Cloud SQL、Firebase、Gemini API、GKE 等。 | Skill library | [Open](https://github.com/google/skills) |
| GitHub Awesome Copilot Skills | GitHub 组织下的 Copilot agents、instructions、skills、hooks、workflows 和插件集合，适合 GitHub Copilot skill 生态。 | GitHub Copilot skills | [Open](https://github.com/github/awesome-copilot) |
| Vercel Agent Skills | Vercel 官方 agent skills 集合，面向 AI coding agents，包含 React、Next.js、组件组合、缓存、升级和 Web 设计规范。 | Skill library | [Open](https://github.com/vercel-labs/agent-skills) |
| Cloudflare Skills | Cloudflare 官方 skills，面向 Workers、Pages、Agents SDK、Durable Objects、Wrangler、AI、存储和边缘部署。 | Cloud / Edge skills | [Open](https://github.com/cloudflare/skills) |
| Supabase Agent Skills | Supabase 官方 agent skills，帮助 AI agents 更准确地使用 Supabase、Postgres、RLS、Edge Functions 和相关开发流程。 | Database / Backend skills | [Open](https://github.com/supabase/agent-skills) |
| Hugging Face Skills | Hugging Face 官方 AI/ML skills，面向模型训练、数据集、评估、Gradio、Spaces、Hub 操作和 ML 工作流。 | ML / AI skills | [Open](https://github.com/huggingface/skills) |
| Google Workspace CLI | Google Workspace CLI 仓库，包含面向 Gmail、Drive、Calendar、Docs、Sheets、Slides、Forms、Keep 等服务的 agent skills。 | Productivity / CLI skills | [Open](https://github.com/googleworkspace/cli) |
| Expo Skills | Expo 官方 AI agent skills，用于构建、部署、调试 Expo 和 React Native 应用。 | Mobile development skills | [Open](https://github.com/expo/skills) |
| Flutter Skills | Flutter 团队维护的 Agent Skills，用于 Flutter app 开发、架构、导航、测试和常见工作流。 | Mobile development skills | [Open](https://github.com/flutter/skills) |
| Elastic Agent Skills | Elastic 官方 Agent Skills，帮助 AI coding agents 使用 Elastic 平台、搜索、可观测性和安全相关能力。 | Search / Observability skills | [Open](https://github.com/elastic/agent-skills) |
| Redis Agent Skills | Redis 官方 agent skills，面向 Redis 数据结构、查询、向量搜索、缓存和性能优化。 | Database skills | [Open](https://github.com/redis/agent-skills) |
| Browserbase Skills | Browserbase 官方 skills，面向浏览器自动化、Web 访问和 agent browser workflows。 | Browser automation skills | [Open](https://github.com/browserbase/skills) |
| ClickHouse Agent Skills | ClickHouse 官方 Agent Skills，用于 ClickHouse、chDB、本地开发、云部署、架构建议和查询最佳实践。 | Database / Analytics skills | [Open](https://github.com/ClickHouse/agent-skills) |
| Laravel Agent Skills | Laravel 官方 agent skills，面向 Laravel、Laravel Cloud、Nightwatch，以及 Claude Code / Cursor 插件使用。 | Web framework skills | [Open](https://github.com/laravel/agent-skills) |
| Ably Agent Skills | Ably 官方 agent skills，面向实时消息、CLI 调试、SDK 使用、认证、通道状态和常见集成问题。 | Realtime API skills | [Open](https://github.com/ably/agent-skills) |
| LaunchDarkly Agent Skills | LaunchDarkly 公开 agent skills 仓库，用于 feature flags、release 管理和 LaunchDarkly 相关工作流。 | Feature flag skills | [Open](https://github.com/launchdarkly/agent-skills) |
| DeepSource Skills | DeepSource 官方 skills，面向代码质量、静态分析、自动审查和工程质量工作流。 | Code quality skills | [Open](https://github.com/DeepSourceCorp/skills) |
| MATLAB Skills | MATLAB 官方 skills，面向 MATLAB 编程、工程计算和 AI coding agents 使用 MATLAB 的工作流。 | Scientific computing skills | [Open](https://github.com/matlab/skills) |
| TMS Software Skills | TMS Software 官方 Agent Skills，面向其产品和库的 API、约定、代码生成和开发模式。 | Framework / SDK skills | [Open](https://github.com/tmssoftware/skills) |
| HasData Agent Skills | HasData 官方 skills，面向 SERP API、网页抓取、公开 Web 数据提取、异步爬取和数据采集流程。 | Web data skills | [Open](https://github.com/HasData/agent-skills) |
| Bagisto Agent Skills | Bagisto 官方 agent skills，面向电商包开发、支付、物流、主题、产品类型和 Pest 测试。 | E-commerce skills | [Open](https://github.com/bagisto/agent-skills) |
| Artillery Agent Skills | Artillery 官方 agent skills，面向负载测试、性能测试和相关测试自动化工作流。 | Testing / Performance skills | [Open](https://github.com/artilleryio/agent-skills) |
| Stripe AI / Skills | Stripe 的 AI 相关公开仓库，其中包含面向 Stripe 集成、支付、billing 和 API 升级的 skill 内容。 | Payment / API skills | [Open](https://github.com/stripe/ai) |
| Cloudflare Agent Skills Discovery RFC | Cloudflare 关于通过 `.well-known` URI 发现 Agent Skills 的公开 RFC，不是普通 skill 库，但适合放作官方标准参考。 | Discovery / RFC | [Open](https://github.com/cloudflare/agent-skills-discovery-rfc) |

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
