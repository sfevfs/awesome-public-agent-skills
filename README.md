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
| Anthropic Skills Repository | Anthropic 官方 Agent Skills 示例仓库，包含 Claude 可动态加载的 instructions、scripts 和 resources。 | Official skill library | [Open](https://github.com/anthropics/skills) |
| Anthropic Agent Skills Specification | Anthropic 仓库中的 Agent Skills 规范，说明 `SKILL.md`、frontmatter、目录结构和 skill 格式。 | Specification | [Open](https://github.com/anthropics/skills/tree/main/spec) |
| Anthropic Skill Template | Anthropic 官方 skill 模板，可作为创建新 `SKILL.md` skill 的起点。 | Skill template | [Open](https://github.com/anthropics/skills/tree/main/template) |
| Agent Skills API Docs | Claude Platform 的 Agent Skills 文档，说明 skills 如何加载、触发、在 API 中使用，以及安全注意事项。 | Documentation | [Open](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) |
| Claude Code Skills Docs | Claude Code 官方 skills 文档，说明如何创建、管理、分享和调用 Claude Code skills。 | Documentation | [Open](https://code.claude.com/docs/en/skills) |
| What are Skills? | Claude Help Center 中对 Skills 的官方解释，说明 Anthropic Skills、Custom Skills、Organization Skills 和 Partner Skills 的区别。 | Documentation | [Open](https://support.claude.com/en/articles/12512176-what-are-skills) |
| Use Skills in Claude | Claude Help Center 中的 Skills 使用说明，包含启用、发现、上传、分享和使用 Anthropic built-in skills 的流程。 | Documentation | [Open](https://support.claude.com/en/articles/12512180-use-skills-in-claude) |
| How to Create Custom Skills | Claude Help Center 中的自定义 Skills 创建指南，适合学习如何打包和上传自己的 Claude skill。 | Documentation | [Open](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) |
| Equipping Agents with Agent Skills | Anthropic 工程博客，解释 Agent Skills 的设计思想、progressive disclosure、`SKILL.md` 结构和最佳实践。 | Engineering article | [Open](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) |
| Claude Code Plugins Directory | Anthropic 官方 Claude Code Plugins 目录，其中 plugin 可以包含 commands、agents、skills 和 MCP 配置。 | Plugin directory | [Open](https://github.com/anthropics/claude-plugins-official) |
| Claude Code Bundled Skills | Claude Code 内置 bundled skills，包括 `/simplify`、`/batch`、`/debug`、`/loop` 和 `/claude-api`。 | Built-in Claude Code skills | [Open](https://code.claude.com/docs/en/skills#bundled-skills) |
| Claude Code Skill Development | Anthropic Claude Code 仓库中的 skill-development skill，用于指导创建、改进和组织 Claude Code plugin skills。 | Skill development | [Open](https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/skill-development) |
| Algorithmic Art | Anthropic 示例 skill，用于生成算法艺术、创意图形和程序化视觉作品。 | Creative skill | [Open](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) |
| Brand Guidelines | Anthropic 示例 skill，用于按照品牌规范生成文档、展示材料和视觉内容。 | Branding skill | [Open](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines) |
| Canvas Design | Anthropic 示例 skill，用于 Claude Canvas / design 场景中的布局、视觉设计和设计稿生成。 | Design skill | [Open](https://github.com/anthropics/skills/tree/main/skills/canvas-design) |
| Claude API | Anthropic 示例 skill，用于构建、调试和优化 Claude API / Anthropic SDK 应用。 | API development skill | [Open](https://github.com/anthropics/skills/tree/main/skills/claude-api) |
| Document Coauthoring | Anthropic 示例 skill，用于结构化协作文档写作、上下文收集、内容迭代和读者测试。 | Writing / Docs skill | [Open](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) |
| DOCX | Anthropic 文档处理 skill，用于创建、读取、编辑和转换 Microsoft Word `.docx` 文件。 | Document skill | [Open](https://github.com/anthropics/skills/tree/main/skills/docx) |
| Frontend Design | Anthropic 示例 skill，用于前端界面、视觉风格、组件布局和 Web UI 设计。 | Frontend / Design skill | [Open](https://github.com/anthropics/skills/tree/main/skills/frontend-design) |
| Internal Comms | Anthropic 示例 skill，用于内部沟通、公告、邮件、团队更新和组织内信息表达。 | Communication skill | [Open](https://github.com/anthropics/skills/tree/main/skills/internal-comms) |
| MCP Builder | Anthropic 示例 skill，用于构建 MCP servers、设计工具接口和连接外部系统。 | MCP development skill | [Open](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) |
| PDF | Anthropic 文档处理 skill，用于 PDF 读取、处理、表单填写、合并、拆分和内容提取。 | Document skill | [Open](https://github.com/anthropics/skills/tree/main/skills/pdf) |
| PPTX | Anthropic 文档处理 skill，用于创建、读取、编辑和组合 PowerPoint `.pptx` 演示文稿。 | Presentation skill | [Open](https://github.com/anthropics/skills/tree/main/skills/pptx) |
| Skill Creator | Anthropic 示例 skill，用于帮助创建、改进、组织和优化新的 Agent Skills。 | Skill authoring skill | [Open](https://github.com/anthropics/skills/tree/main/skills/skill-creator) |
| Slack GIF Creator | Anthropic 示例 skill，用于生成适合 Slack 使用的 GIF、动图和轻量视觉内容。 | Creative / Communication skill | [Open](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator) |
| Theme Factory | Anthropic 示例 skill，用于生成主题、色彩方案、视觉风格和可复用设计系统。 | Design system skill | [Open](https://github.com/anthropics/skills/tree/main/skills/theme-factory) |
| Web Artifacts Builder | Anthropic 示例 skill，用于构建 Claude artifacts、Web 原型、交互式页面和可视化内容。 | Web artifact skill | [Open](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) |
| Webapp Testing | Anthropic 示例 skill，用于测试 Web 应用、检查交互流程、定位 UI 问题和验证网页行为。 | Testing skill | [Open](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) |
| XLSX | Anthropic 文档处理 skill，用于创建、读取、编辑和分析 Excel `.xlsx` 表格文件。 | Spreadsheet skill | [Open](https://github.com/anthropics/skills/tree/main/skills/xlsx) |

## Copilot / Coding Agent Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| GitHub Awesome Copilot | GitHub 组织下的 Copilot 资源集合，包含 agents、instructions、skills、plugins、hooks、workflows 和 cookbook。 | Copilot ecosystem | [Open](https://github.com/github/awesome-copilot) |
| Awesome Copilot Skills Directory | GitHub Awesome Copilot 的 skills 页面，可搜索和下载 Copilot agent skills。 | Copilot skills directory | [Open](https://awesome-copilot.github.com/skills/) |
| GitHub Copilot Agent Skills Announcement | GitHub Copilot 支持 Agent Skills 的官方更新说明，解释 skills 如何被 Copilot 自动加载。 | Official announcement | [Open](https://github.blog/changelog/2025-12-18-github-copilot-now-supports-agent-skills/) |
| VS Code Agent Skills Docs | VS Code / Copilot 官方文档，说明如何使用 `.github/skills/`、共享 skills 和扩展贡献 skills。 | Documentation | [Open](https://code.visualstudio.com/docs/copilot/customization/agent-skills) |
| GitHub Copilot Agent Skills Guidelines | GitHub Awesome Copilot 中的 Agent Skills 编写指南，用于创建高质量、可移植的 Copilot skills。 | Skill authoring guide | [Open](https://github.com/github/awesome-copilot/blob/main/instructions/agent-skills.instructions.md) |
| Suggest Awesome GitHub Copilot Skills | 用于分析当前仓库并推荐适合安装的 GitHub Awesome Copilot skills。 | Copilot recommendation skill | [Open](https://github.com/github/awesome-copilot/blob/main/skills/suggest-awesome-github-copilot-skills/SKILL.md) |
| OpenAI Skills | OpenAI / Codex 官方 skills catalog，收集 Codex 可使用和分发的 Agent Skills。 | Codex skill catalog | [Open](https://github.com/openai/skills) |
| OpenAI Codex Agent Skills Docs | OpenAI Codex 官方文档，说明 skills 的创建、存放位置、触发方式和分发方式。 | Codex documentation | [Open](https://developers.openai.com/codex/skills) |
| Reusable Codex Skills Guide | OpenAI Codex use case 文档，说明如何把重复工作流保存为 Codex skills。 | Codex workflow guide | [Open](https://developers.openai.com/codex/use-cases/reusable-codex-skills) |
| Anthropic Claude Code Plugins | Claude Code 官方插件目录，包含 code review、feature development、frontend design、PR review、plugin development 等 coding workflow。 | Claude Code plugins | [Open](https://github.com/anthropics/claude-code/tree/main/plugins) |
| Claude Code Skill Development | Anthropic Claude Code 中的 skill-development skill，用于指导创建和改进 Claude Code plugin skills。 | Skill development | [Open](https://github.com/anthropics/claude-code/tree/main/plugins/plugin-dev/skills/skill-development) |
| Claude Code Plugin Marketplace Docs | Claude Code 官方文档，说明如何创建、发布和分发包含 skills、agents、hooks、MCP servers 的 plugin marketplace。 | Marketplace docs | [Open](https://code.claude.com/docs/en/plugin-marketplaces) |
| Vercel Agent Skills | Vercel 官方 AI coding agent skills，包含 React / Next.js 性能、Web 设计、React Native 等工程实践。 | Frontend coding skills | [Open](https://github.com/vercel-labs/agent-skills) |
| Vercel Skills CLI | Vercel 的 `npx skills` 工具，用于向 Claude Code、Codex、Cursor、Copilot 等多种 agent 安装和管理 skills。 | Skill installer / CLI | [Open](https://github.com/vercel-labs/skills) |
| Vercel Agent Skills Docs | Vercel 官方 Agent Skills 文档，整理 React、Next.js、deployment、Slack app 等 coding agent skills。 | Documentation / Skill directory | [Open](https://vercel.com/docs/agent-resources/skills) |
| Microsoft Skills | Microsoft 面向 Azure SDKs、Microsoft AI Foundry、M365 agents、AGENTS.md、MCP 配置和 AI coding agents 的 skills 仓库。 | Microsoft coding skills | [Open](https://github.com/microsoft/skills) |
| Google Skills | Google 官方 Agent Skills，覆盖 Google Cloud、Firebase、Gemini API、GKE、BigQuery 等，可用于 coding agents 获取产品级开发指令。 | Google Cloud coding skills | [Open](https://github.com/google/skills) |
| Flutter Skills | Flutter 团队维护的 Agent Skills，面向 Flutter app 开发、布局、导航、JSON、测试和常见工程流程。 | Flutter coding skills | [Open](https://github.com/flutter/skills) |
| Dart / Flutter Dash Skills | Dart 与 Flutter 相关 agent skills，适合 AI coding agents 处理 Dart / Flutter 项目。 | Dart / Flutter skills | [Open](https://github.com/kevmoo/dash_skills) |
| Expo Skills | Expo 官方 AI agent skills，用于构建、部署、调试 Expo 和 React Native 应用。 | Mobile coding skills | [Open](https://github.com/expo/skills) |
| Addy Osmani Agent Skills | 面向 AI coding agents 的生产级工程 skills，覆盖 spec、plan、build、test、review、ship 等开发生命周期。 | Engineering workflow skills | [Open](https://github.com/addyosmani/agent-skills) |
| Agent Skill Creator | 将任意 workflow 转成可安装到 Claude Code、Copilot、Cursor、Windsurf、Codex、Gemini、Kiro 等工具的 Agent Skill。 | Skill creator / Generator | [Open](https://github.com/FrancyJGLisboa/agent-skill-creator) |
| Tech Leads Club Agent Skills | 面向专业 AI coding agents 的安全验证 skill registry，支持 Antigravity、Claude Code、Cursor、Copilot 等。 | Validated skill registry | [Open](https://github.com/tech-leads-club/agent-skills) |
| AGENTS.md | 面向 AI coding agents 的开放 Markdown 指令格式，用于提供项目结构、构建命令、测试流程和代码风格。 | Coding agent instruction standard | [Open](https://agents.md/) |
| AGENTS.md Generator Skill | 生成和维护 AGENTS.md 文件的 Agent Skill，支持 Claude Code、Cursor、GitHub Copilot 和其他兼容 agents。 | AGENTS.md skill | [Open](https://github.com/netresearch/agent-rules-skill) |
| Awesome Cursor Skills | Cursor skills 合集，收集可放入 `.cursor/skills/` 的 `SKILL.md` 文件，用于工程 workflow 和项目脚手架。 | Cursor skills list | [Open](https://github.com/spencerpauly/awesome-cursor-skills) |
| Cursor Skills Notes | Cursor Agent Skills 说明文档，解释 Cursor skills 的目录结构、触发方式和使用场景。 | Cursor skills docs | [Open](https://github.com/hutchic/.cursor/blob/main/docs/cursor-skills.md) |
| Windsurf Agents | Windsurf agent skills、workflows 和自动化脚本集合，面向 Windsurf / Cascade 开发工作流。 | Windsurf skills / Workflows | [Open](https://github.com/zenmindhacker/windsurf-agents) |
| Hoodini AI Agents Skills | 面向 Claude Code、GitHub Copilot、Cursor、Windsurf、Cline、Aider、Continue.dev 等 coding agents 的技能集合。 | Multi-agent coding skills | [Open](https://github.com/hoodini/ai-agents-skills) |
| VoltAgent Awesome Agent Skills | 大型 Agent Skills 索引，兼容 Claude Code、Codex、Gemini CLI、Cursor 等，可筛选 coding agent skills。 | Skill index | [Open](https://github.com/VoltAgent/awesome-agent-skills) |
| Kodu Awesome Agent Skills | 面向 Claude Code、Codex、Cursor 等 AI coding agents 的 Agent Skills 列表。 | Coding agent skills list | [Open](https://github.com/kodustech/awesome-agent-skills) |
| Alireza Claude Skills | 大型 Claude Code skills / agent plugins 集合，包含软件工程、架构、测试、代码质量、DevOps 等技能包。 | Claude Code skills marketplace | [Open](https://github.com/alirezarezvani/claude-skills) |
| Daymade Claude Code Skills | Claude Code skills marketplace，包含 production-ready development workflow skills。 | Claude Code skills marketplace | [Open](https://github.com/daymade/claude-code-skills) |
| Netresearch Claude Code Marketplace | Netresearch 维护的 Claude Code / AI-assisted development Agent Skills marketplace。 | Claude Code plugin marketplace | [Open](https://github.com/netresearch/claude-code-marketplace) |
| Obra Superpowers Marketplace | Claude Code plugin marketplace，包含 TDD、调试、协作、计划执行和 Claude Code 插件开发相关 skills。 | Claude Code plugin marketplace | [Open](https://github.com/obra/superpowers-marketplace) |
| N Skills | 面向 AI agents 的 curated plugin marketplace，可配合 Claude Code、Codex 和 OpenSkills 使用。 | Skill marketplace | [Open](https://github.com/numman-ali/n-skills) |
| OpenSkills | 通用 SKILL.md installer / loader，把 Anthropic-style skills 带到 Claude Code、Cursor、Windsurf、Aider、Codex 等 agent。 | Skill installer / Loader | [Open](https://github.com/numman-ali/openskills) |
| Skill Seekers | 将框架文档或代码库转换成可用于 Cursor、Windsurf、Claude Code 等工具的规则 / skills。 | Skill / Rules generator | [Open](https://github.com/yusufkaraaslan/Skill_Seekers) |
| AgentRC / AI Readiness Skills | GitHub Awesome Copilot 中的 AI readiness skills，用于评估 repo 的 AI tooling readiness 并生成 Copilot instructions。 | Copilot readiness skills | [Open](https://awesome-copilot.github.com/skills/) |
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
