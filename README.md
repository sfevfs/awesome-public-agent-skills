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
| VoltAgent Awesome Agent Skills | 大型 Agent Skills 索引，收集官方团队和社区贡献的 skills，兼容 Claude Code、Codex、Gemini CLI、Cursor 等。 | Awesome list / Skill index | [Open](https://github.com/VoltAgent/awesome-agent-skills) |
| Heilcheng Awesome Agent Skills | 社区维护的 Agent Skills 列表，重点收集真实工程团队使用的 skills，并支持 Claude、Copilot、Codex、Cursor 等。 | Community awesome list | [Open](https://github.com/heilcheng/awesome-agent-skills) |
| JackyST0 Awesome Agent Skills | 精选 AI Agent Skills 列表，适用于 Cursor、Claude Code、GitHub Copilot 等 AI 编程工具，并提供在线搜索和安装脚本。 | Skill index / Search tool | [Open](https://github.com/JackyST0/awesome-agent-skills) |
| Hoodini AI Agents Skills | 面向 Claude Code、Copilot、Cursor、Windsurf、Cline、Aider、Continue.dev 等 coding agents 的技能集合。 | Coding agent skills | [Open](https://github.com/hoodini/ai-agents-skills) |
| Composio Awesome Claude Skills | Claude Skills、资源和工具列表，包含文档、开发、数据、研究、写作、自动化等方向。 | Claude skills awesome list | [Open](https://github.com/ComposioHQ/awesome-claude-skills) |
| Karan Awesome Claude Skills | 社区整理的 Claude / Agent Skills 列表，强调可复用 skill、工具、资源和安全检查。 | Claude skills awesome list | [Open](https://github.com/karanb192/awesome-claude-skills) |
| BehiSecc Awesome Claude Skills | Claude Skills 分类索引，覆盖文档、开发、数据分析、研究、写作、协作、安全和自动化等方向。 | Claude skills awesome list | [Open](https://github.com/BehiSecc/awesome-claude-skills) |
| Travis Awesome Claude Skills | 面向 Claude AI workflows，尤其是 Claude Code 的 skills、资源和工具合集。 | Claude skills awesome list | [Open](https://github.com/travisvn/awesome-claude-skills) |
| SkillCreator Awesome Agent Skills | SkillCreator.ai 整理的 Claude Skills、资源和工具列表，基于 Composio awesome-claude-skills 扩展。 | Claude skills awesome list | [Open](https://github.com/skillcreatorai/Awesome-Agent-Skills) |
| Skillmatic Awesome Agent Skills | 面向 Agent Skills 概念和生态的资源索引，收集 skill 标准、工具和社区资源。 | Agent skills resource list | [Open](https://github.com/skillmatic-ai/awesome-agent-skills) |
| CommandCodeAI Agent Skills | 面向 coding agent workflow 定制的 skills、资源和工具合集。 | Coding agent skills list | [Open](https://github.com/CommandCodeAI/agent-skills) |
| Kodu Awesome Agent Skills | 面向 Claude Code、Codex、Cursor 等 AI coding agents 的 Agent Skills 列表。 | Coding agent skills list | [Open](https://github.com/kodustech/awesome-agent-skills) |
| H4vzz Awesome AI Agent Skills | 提供 70+ ready-to-use skills，面向真实任务中的 AI agent 能力增强。 | Ready-to-use skill collection | [Open](https://github.com/h4vzz/awesome-ai-agent-skills) |
| SIRFU3G0 Awesome Agent Skills | AI coding agent skills、工具和教程集合，用于增强 Claude、Codex、Copilot 等 agent 的能力。 | Coding agent resources | [Open](https://github.com/SIRFU3G0/awesome-agent-skills) |
| Alireza Claude Skills | 大型 Claude Code skills / agent plugins 集合，包含工程、产品、营销、项目管理、商业、金融等多个 skill 包。 | Claude Code skills marketplace | [Open](https://github.com/alirezarezvani/claude-skills) |
| Daymade Claude Code Skills | Claude Code skills marketplace，包含 production-ready skills，并支持通过 Claude Code plugin marketplace 安装。 | Claude Code plugin marketplace | [Open](https://github.com/daymade/claude-code-skills) |
| Netresearch Claude Code Marketplace | Netresearch 维护的 Claude Code / AI-assisted development Agent Skills marketplace。 | Claude Code plugin marketplace | [Open](https://github.com/netresearch/claude-code-marketplace) |
| Obra Superpowers Marketplace | Claude Code plugin marketplace，包含 TDD、调试、协作、计划执行和 Claude Code 插件开发相关 skills。 | Claude Code plugin marketplace | [Open](https://github.com/obra/superpowers-marketplace) |
| Jimmc414 Claude Code Plugin Marketplace | 社区 Claude Code plugin marketplace，收集 skills、agents、commands 和 hooks。 | Claude Code plugin marketplace | [Open](https://github.com/jimmc414/claude-code-plugin-marketplace) |
| Lttr Claude Marketplace | 个人维护的 Claude Code plugin marketplace，用于分发 Claude Code extensions / plugins。 | Claude Code plugin marketplace | [Open](https://github.com/lttr/claude-marketplace) |
| N Skills | 面向 AI agents 的 curated plugin marketplace，可配合 Claude Code、Codex 和 OpenSkills 使用。 | Skill marketplace | [Open](https://github.com/numman-ali/n-skills) |
| OpenSkills | 通用 SKILL.md installer / loader，把 Anthropic-style skills 带到 Claude Code、Cursor、Windsurf、Aider、Codex 等 agent。 | Skill installer / Loader | [Open](https://github.com/numman-ali/openskills) |
| AbsolutelySkilled | 开放式 AI Agent Skills registry，收集 production-ready skills，面向 Claude Code、Gemini CLI、OpenAI Codex、Cursor 等。 | Public skill registry | [Open](https://github.com/AbsolutelySkilled/AbsolutelySkilled) |
| LobeHub Skills Marketplace | 面向 Claude Code、Codex CLI、ChatGPT、Cursor、OpenClaw 等 agent 的公开 skills marketplace。 | Public skill marketplace | [Open](https://lobehub.com/skills) |
| AwesomeSkills.dev | 面向 Claude Code、OpenAI Codex、Cursor 等 agent 的 skills directory，收集官方和社区 skill packs。 | Skill directory | [Open](https://www.awesomeskills.dev/en) |
| SkillsLLM | 开源 AI skills marketplace，按 AI Agents、MCP Servers、Code Generation、DevOps 等类别索引 skills。 | Skill marketplace / Directory | [Open](https://skillsllm.com/) |
| ClawHub | OpenClaw 的公开 skill registry，用于发布、搜索和版本管理基于 `SKILL.md` 的 text-based agent skills。 | OpenClaw skill registry | [Open](https://github.com/openclaw/clawhub) |
| Diversio Agent Skills Marketplace | 基于 open Agent Skills standard 的 marketplace metadata 仓库，用于组织和分发 agent skills。 | Skill marketplace metadata | [Open](https://github.com/DiversioTeam/agent-skills-marketplace) |
| Awesome Claude Code | Claude Code 生态大型资源合集，包含 skills、hooks、slash commands、agent orchestrators、apps 和 plugins。 | Claude Code ecosystem list | [Open](https://github.com/hesreallyhim/awesome-claude-code) |
| GetBindu Awesome Claude Code and Skills | Claude skills、agents、tools 和开发工作流资源集合，覆盖 coding、安全、营销和专业领域。 | Claude skills resource list | [Open](https://github.com/GetBindu/awesome-claude-code-and-skills) |
| CodeAlive Awesome Agent Skills | CodeAlive 早期的 general-purpose agent skills 集合；仓库已归档，适合作为历史参考。 | Archived skill collection | [Open](https://github.com/CodeAlive-AI/awesome-agent-skills) |

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
