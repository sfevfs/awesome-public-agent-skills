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
| Model Context Protocol Docs | MCP 官方文档，说明 MCP server、tools、resources、prompts、transports 和安全模型等基础概念。 | Documentation | [Open](https://modelcontextprotocol.io/docs/learn/server-concepts) |
| Official MCP Registry | MCP 官方 registry，用于发现公开 MCP servers，并提供标准化 metadata、安装和配置入口。 | Official registry | [Open](https://registry.modelcontextprotocol.io/) |
| MCP Registry Repository | MCP 官方 registry 的 GitHub 仓库，适合了解 MCP server metadata、发布流程和 registry 实现方式。 | Registry repository | [Open](https://github.com/modelcontextprotocol/registry) |
| MCP Reference Servers | Model Context Protocol 官方 reference servers，用于学习 MCP server 实现方式和 SDK 用法。 | Reference servers | [Open](https://github.com/modelcontextprotocol/servers) |
| GitHub MCP Registry | GitHub 的 MCP Registry，用于发现、安装和集成适合 Copilot、VS Code 和其他 MCP client 的服务器。 | MCP registry | [Open](https://github.com/mcp) |
| Docker MCP Catalog | Docker 维护的 MCP Catalog，收集经过打包和验证的 MCP servers，可通过 Docker Desktop / Docker Hub 使用。 | MCP catalog | [Open](https://mcp.docker.com/) |
| Docker MCP Registry | Docker 官方 MCP Registry 仓库，包含可被 Docker MCP Catalog、Docker Desktop MCP Toolkit 和 Docker Hub 使用的 server 定义。 | Registry repository | [Open](https://github.com/docker/mcp-registry) |
| Docker Hub MCP Namespace | Docker Hub 上的 MCP verified publisher namespace，包含 GitHub、AWS、数据库、监控等多类 MCP server 镜像。 | Docker MCP images | [Open](https://hub.docker.com/u/mcp) |
| Awesome MCP Servers | 大型 MCP servers 目录，收集 production-ready 和 experimental MCP servers，覆盖文件、数据库、API、浏览器和外部服务。 | Awesome list | [Open](https://github.com/punkpeye/awesome-mcp-servers) |
| MCPServers.org | MCP servers 目录，收集官方和社区 MCP servers，包括 GitHub、Google、Supabase、Playwright、Firecrawl、Context7 等。 | MCP directory | [Open](https://mcpservers.org/) |
| Glama MCP Registry | MCP server、client、tools 和 integrations 搜索目录，提供安全、兼容性和质量评分。 | MCP registry | [Open](https://glama.ai/mcp/servers) |
| PulseMCP | 每日更新的 MCP server directory，收集大量公开 MCP servers、clients、posts 和 ecosystem 资源。 | MCP directory | [Open](https://www.pulsemcp.com/servers) |
| Smithery | MCP server 搜索、部署和管理平台，用于发现并连接社区和官方 MCP servers。 | MCP registry / Deployment | [Open](https://smithery.ai/servers) |
| Smithery CLI MCP | Smithery 官方 MCP installer，可用于搜索、收集配置并安装 MCP servers。 | MCP installer | [Open](https://github.com/smithery-ai/smithery-cli-mcp) |
| GitHub MCP Server | GitHub 官方 MCP Server，让 agents 读取仓库、管理 Issues / PR、分析代码、处理 code scanning 和自动化工作流。 | Official MCP server | [Open](https://github.com/github/github-mcp-server) |
| Google MCP Servers | Google 官方 MCP servers 总入口，包含 Google MCP server 列表、部署到 Google Cloud 的指导和示例。 | Official MCP collection | [Open](https://github.com/google/mcp) |
| MCP Toolbox for Databases | Google 开源的 MCP Toolbox for Databases，用于让 AI agents、IDEs 和应用直接连接企业数据库。 | Database MCP server | [Open](https://github.com/googleapis/mcp-toolbox) |
| AWS MCP Servers | AWS Labs 维护的开源 MCP servers，面向 AWS 文档、架构建议、云开发、基础设施和 AWS 服务操作。 | Cloud MCP collection | [Open](https://github.com/awslabs/mcp) |
| AWS MCP Documentation | AWS MCP Servers 官方文档入口，介绍 AWS MCP servers 如何为 AI 应用提供 AWS 文档、上下文和最佳实践。 | Documentation | [Open](https://awslabs.github.io/mcp/) |
| Cloudflare MCP Server | Cloudflare 官方 MCP server，可通过 MCP client 使用自然语言操作 Cloudflare 账号和服务。 | Cloud / Edge MCP server | [Open](https://github.com/cloudflare/mcp) |
| Cloudflare Managed MCP Servers | Cloudflare 托管的远程 MCP servers，用于读取配置、管理服务和自动化 Cloudflare 账户操作。 | Managed MCP servers | [Open](https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/) |
| Supabase MCP Server | Supabase 社区/官方支持的 MCP server，让 AI assistants 管理 Supabase 表、配置、数据库查询和项目上下文。 | Database / Backend MCP server | [Open](https://github.com/supabase-community/supabase-mcp) |
| Supabase MCP Docs | Supabase MCP 官方文档，说明远程 MCP endpoint、本地开发 endpoint 和配置方式。 | Documentation | [Open](https://supabase.com/docs/guides/getting-started/mcp) |
| Stripe MCP | Stripe 官方 MCP server，可通过远程 MCP endpoint 或本地 npm 包访问客户、产品、支付等 Stripe API 工具。 | Payment MCP server | [Open](https://docs.stripe.com/mcp) |
| Stripe MCP Registry Entry | Stripe 在 GitHub MCP Registry 中的条目，说明 Stripe remote MCP server 和本地 `@stripe/mcp` 用法。 | MCP registry entry | [Open](https://github.com/mcp/com.stripe/mcp) |
| Atlassian Rovo MCP Server | Atlassian 官方远程 MCP server，用于将 Jira、Confluence 和 Rovo Search 上下文接入外部 AI clients。 | Project / Knowledge MCP server | [Open](https://www.atlassian.com/platform/remote-mcp-server) |
| Atlassian MCP Server Repository | Atlassian Rovo MCP Server 的 GitHub 仓库，可配合本地 MCP-compatible client 和 mcp-remote 使用。 | MCP server repository | [Open](https://github.com/atlassian/atlassian-mcp-server) |
| Notion MCP Server | Notion 官方 MCP server，支持 STDIO 和 Streamable HTTP transport，用于连接 Notion API。 | Productivity MCP server | [Open](https://github.com/makenotion/notion-mcp-server) |
| Notion MCP Client Integration Docs | Notion 官方 MCP client integration 文档，说明如何连接 Notion MCP server 和 OAuth discovery 流程。 | Documentation | [Open](https://github.com/makenotion/notion-cookbook/blob/main/docs/mcp-client-integration.md) |
| Playwright MCP | Microsoft 官方 Playwright MCP server，让 LLM 通过结构化 accessibility snapshots 与网页交互。 | Browser automation MCP server | [Open](https://github.com/microsoft/playwright-mcp) |
| Playwright MCP Docs | Playwright 官方 MCP 文档，说明如何在 VS Code、Cursor、Windsurf、Claude Desktop 等 MCP clients 中使用。 | Documentation | [Open](https://playwright.dev/docs/getting-started-mcp) |
| Context7 | Upstash 的 Context7 MCP server，为 AI coding tools 提供最新、版本相关的库文档和代码示例。 | Documentation MCP server | [Open](https://github.com/upstash/context7) |
| Context7 Website | Context7 官方网站，用于把最新文档和代码示例拉入 Cursor、Claude Code、Windsurf 等工具。 | Documentation tool | [Open](https://context7.com/) |
| DeepWiki MCP | Devin / Cognition 官方 DeepWiki MCP server，用于访问 GitHub repo 的 wiki、结构化文档和问答能力。 | Codebase context MCP server | [Open](https://cognition.ai/blog/deepwiki-mcp-server) |
| DeepWiki Docs | Devin 官方 DeepWiki 文档，说明 Public DeepWiki 和 DeepWiki MCP 的代码库文档与 Q&A 能力。 | Documentation | [Open](https://docs.devin.ai/work-with-devin/deepwiki) |
| E2B MCP Server | E2B 官方 MCP server，为 Claude Desktop 等 MCP client 提供安全 sandbox 中的代码执行能力。 | Code execution MCP server | [Open](https://github.com/e2b-dev/mcp-server) |
| E2B Custom MCP Servers | E2B 文档，说明如何在 E2B sandbox 中安全运行自定义 MCP servers。 | Sandbox / Security tool | [Open](https://e2b.dev/docs/mcp/custom-servers) |
| Exa MCP Server | Exa 官方 MCP server，为 AI assistants 提供 web search、code search、web crawling 和 company research。 | Search MCP server | [Open](https://github.com/exa-labs/exa-mcp-server) |
| Exa MCP Website | Exa MCP 官方页面，用于把 Exa 的搜索、代码搜索和研究能力接入 Claude、Cursor、VS Code 等 AI 工具。 | Search tool | [Open](https://exa.ai/mcp) |
| Brave Search MCP Server | Brave 官方 MCP server，集成 Brave Search API，提供 web、local、place、image、video、news 和 LLM context search。 | Search MCP server | [Open](https://github.com/brave/brave-search-mcp-server) |
| Firecrawl MCP Server | Firecrawl 官方 MCP server，为 Cursor、Claude 和其他 MCP clients 提供网页抓取、搜索、批处理和内容提取能力。 | Web scraping MCP server | [Open](https://github.com/firecrawl/firecrawl-mcp-server) |
| Firecrawl | Firecrawl 主仓库和平台，提供适合 AI agents 的搜索、抓取、网页解析和结构化数据提取能力。 | Web data tool | [Open](https://github.com/firecrawl/firecrawl) |
| Apify MCP Server | Apify 官方 MCP server，让 agents 使用 Apify Store 中的爬虫、scrapers、social media、maps、e-commerce 和自动化工具。 | Web automation MCP server | [Open](https://github.com/apify/apify-mcp-server) |
| Apify MCP Servers | Apify MCP server 集合，用于把 Apify Actors 和 ready-built tools 接入 AI assistants。 | MCP server collection | [Open](https://github.com/apify/mcp-servers) |
| Zapier MCP | Zapier 官方 MCP，用于把 Claude、ChatGPT、Cursor 等 AI clients 连接到 Zapier 的应用集成和自动化动作。 | Automation MCP server | [Open](https://docs.zapier.com/mcp/home) |
| Zapier MCP Repository | Zapier MCP GitHub 仓库，用于把 AI assistants 连接到 Slack、Google Sheets、Gmail、Asana、GitHub、HubSpot 等服务。 | Automation MCP server | [Open](https://github.com/zapier/zapier-mcp) |
| Pipedream MCP Server | Pipedream 官方 MCP server，提供 3,000+ apps/APIs 和 10,000+ pre-built tools，并处理 OAuth 与凭据存储。 | Automation MCP server | [Open](https://pipedream.com/docs/connect/mcp) |
| Pipedream MCP Server App | Pipedream MCP 配置入口，用于连接 Pipedream 账户到 Cursor、Claude、Windsurf 等 AI tools。 | MCP endpoint | [Open](https://mcp.pipedream.com/app/pipedream) |
| Composio MCP | Composio 的 MCP 和 direct API 工具平台，用于把 AI agents 连接到外部应用、认证和跨平台操作。 | Agent tool platform | [Open](https://composio.dev/toolkits/composio) |
| Composio SDK | Composio SDK 仓库，提供 toolkits、tool search、context management、authentication 和 sandboxed workbench。 | Agent tool SDK | [Open](https://github.com/composiohq/composio) |
| PostHog MCP | PostHog 官方 MCP server，用于让 AI agents 和工具直接操作 PostHog 产品、feature flags、experiments 和 analytics。 | Analytics MCP server | [Open](https://posthog.com/docs/model-context-protocol) |
| PostHog MCP Repository | PostHog MCP GitHub 仓库，包含安装方式和迁移说明。 | MCP server repository | [Open](https://github.com/PostHog/mcp) |
| Elastic MCP Server | Elastic 官方 Elasticsearch MCP server，让 AI agents 通过 MCP 查询、分析和检索 Elasticsearch indices。 | Search / Observability MCP server | [Open](https://github.com/elastic/mcp-server-elasticsearch) |
| MiniMax MCP | MiniMax 官方 MCP server，用于接入 Text-to-Speech、image generation、video generation 和 voice cloning API。 | Media generation MCP server | [Open](https://github.com/minimax-ai/minimax-mcp) |
| MiniMax Search MCP | MiniMax Search MCP server，提供 web search、browsing 和 image analysis 等 coding-plan 相关能力。 | Search / Vision MCP server | [Open](https://github.com/MiniMax-AI/minimax_search) |
| XcodeBuildMCP | 面向 iOS/macOS 开发的 MCP server 和 CLI，让 AI agents 构建、测试、调试和部署 Xcode 项目。 | iOS / macOS MCP server | [Open](https://github.com/getsentry/XcodeBuildMCP) |
| XcodeBuildMCP Website | XcodeBuildMCP 官方网站，介绍其 Xcode 自动化、模拟器、测试和部署能力。 | Documentation | [Open](https://www.xcodebuildmcp.com/) |
| Slack MCP Plugin | Slack 官方插件配置，用于让 Cursor IDE 和 Claude Code agents 搜索消息、发送通信、管理 canvases 等。 | Slack agent plugin | [Open](https://github.com/slackapi/slack-mcp-plugin) |
| MCP Atlassian | 社区高质量 Atlassian MCP server，支持 Jira 和 Confluence Cloud 以及 Server/Data Center。 | Jira / Confluence MCP server | [Open](https://github.com/sooperset/mcp-atlassian) |
| Awesome Remote MCP Servers | 远程 MCP server 列表，收集 Stripe、Supabase、Square、ThoughtSpot 等可通过远程 URL 连接的 MCP servers。 | Remote MCP list | [Open](https://github.com/jaw9c/awesome-remote-mcp-servers/) |
| Agent Package Manager | 面向 AGENTS.md、Agent Skills 和 MCP servers 的包管理工具，支持安装到 Copilot、Cursor、Claude、Codex、Gemini 等 agent。 | Agent package manager | [Open](https://awesome-copilot.github.com/tools/) |

## Cloud / DevOps Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Google Skills | Google 官方 Agent Skills 仓库，覆盖 Google Cloud、AlloyDB、BigQuery、Cloud Run、Cloud SQL、Firebase、Gemini API、GKE 等。 | Official cloud skills | [Open](https://github.com/google/skills) |
| Microsoft Azure Agent Skills | Microsoft 官方 Azure Agent Skills，面向 Azure 云开发、架构、排障、安全、配置和最佳实践。 | Official Azure skills | [Open](https://github.com/MicrosoftDocs/Agent-Skills) |
| Azure Agent Skills Docs | Microsoft Learn 上的 Azure Agent Skills 文档，说明 Azure skills 的用途、结构和使用方式。 | Documentation | [Open](https://learn.microsoft.com/en-us/training/support/agent-skills) |
| Microsoft Skills | Microsoft 面向 Azure SDKs、Microsoft AI Foundry、M365 agents、AGENTS.md 和 MCP 配置的 skills 仓库。 | Microsoft cloud / SDK skills | [Open](https://github.com/microsoft/skills) |
| Agent Toolkit for AWS | AWS 推荐的新一代 Agent Toolkit，用于让 AI coding agents 更可靠地架构、部署和操作 AWS。 | AWS agent toolkit | [Open](https://github.com/aws/agent-toolkit-for-aws) |
| Agent Plugins for AWS | AWS Labs 的 agent plugins，帮助 AI coding agents 在 AWS 上做架构建议、部署和运维操作。 | AWS agent plugins | [Open](https://github.com/awslabs/agent-plugins) |
| MCP Servers for AWS | AWS Labs 开源 MCP servers，为 AI applications 提供 AWS 文档、上下文、最佳实践和云服务工具。 | AWS MCP servers | [Open](https://github.com/awslabs/mcp) |
| AWS MCP Documentation | AWS MCP Servers 官方文档入口，用于了解 AWS MCP server 的用途、安装和使用方式。 | Documentation | [Open](https://awslabs.github.io/mcp/) |
| Cloudflare Skills | Cloudflare 官方 Agent Skills，面向 Workers、Pages、Agents SDK、Durable Objects 和 Cloudflare Developer Platform。 | Cloudflare skills | [Open](https://github.com/cloudflare/skills) |
| Cloudflare MCP Server | Cloudflare 官方 MCP server，用于通过 AI clients 操作 Cloudflare 账户、服务和边缘平台资源。 | Cloud MCP server | [Open](https://github.com/cloudflare/mcp) |
| Cloudflare Managed MCP Servers | Cloudflare 托管 MCP servers，用于让 AI agents 查询配置、管理资源和执行 Cloudflare 平台任务。 | Managed MCP servers | [Open](https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/) |
| Vercel Agent Skills | Vercel 官方 agent skills，面向 AI coding agents，包含部署、React、Next.js、Web 设计和前端工程实践。 | Deployment / Frontend cloud skills | [Open](https://github.com/vercel-labs/agent-skills) |
| Vercel Skills Docs | Vercel 官方 Agent Skills 文档，说明如何安装和使用 Vercel skills，以及支持哪些 agent。 | Documentation | [Open](https://vercel.com/docs/agent-resources/skills) |
| Netlify Context and Tools | Netlify 官方 context-and-tools 仓库，包含 Netlify skills、Claude Code plugin 和 Cursor rules。 | Netlify deployment skills | [Open](https://github.com/netlify/context-and-tools) |
| Netlify Deployment Skill | OpenAI Skills 中的 Netlify deployment skill，用于检测项目配置、链接站点并部署到 Netlify。 | Deployment skill | [Open](https://github.com/openai/skills/blob/main/skills/.curated/netlify-deploy/SKILL.md) |
| Railway Skills | Railway 官方 agent skills，用于项目、服务、数据库、部署、变量、网络、域名、日志和故障排查。 | Railway cloud skills | [Open](https://github.com/railwayapp/railway-skills) |
| Railway Agent Skills Docs | Railway 官方 Agent Skills 文档，说明 `use-railway` skill 的安装、支持工具和工作流覆盖范围。 | Documentation | [Open](https://docs.railway.com/ai/agent-skills) |
| DigitalOcean App Platform Skills | DigitalOcean App Platform 官方 skills，面向部署、迁移、网络、数据库配置和生产故障排查。 | DigitalOcean deployment skills | [Open](https://github.com/digitalocean-labs/do-app-platform-skills) |
| DigitalOcean App Platform Skills Blog | DigitalOcean 官方介绍 App Platform Skills 的文章，说明这些 skills 如何帮助 AI assistants 生成生产可用部署配置。 | Announcement / Guide | [Open](https://www.digitalocean.com/blog/deploy-smarter-with-ai-app-platform-skills-on-digitalocean) |
| HashiCorp Agent Skills | HashiCorp 官方 Agent Skills，面向 Terraform、Packer、HCL、模块开发、provider 开发、测试和镜像构建。 | IaC / Terraform / Packer skills | [Open](https://github.com/hashicorp/agent-skills) |
| HashiCorp Agent Skills Blog | HashiCorp 官方介绍 Agent Skills 的文章，说明 Terraform、Packer 和基础设施工作流中的使用场景。 | Announcement / Guide | [Open](https://www.hashicorp.com/en/blog/introducing-hashicorp-agent-skills) |
| Pulumi Agent Skills | Pulumi 官方 Agent Skills，面向 Pulumi IaC、迁移、secret 管理、代码转换和高质量 Pulumi 程序编写。 | IaC skills | [Open](https://github.com/pulumi/agent-skills) |
| Pulumi Agent Skills Docs | Pulumi 官方文档，列出 migration 和 authoring 两类 skills，包括 Terraform、CloudFormation、CDK、ARM/Bicep 到 Pulumi 的迁移。 | Documentation | [Open](https://www.pulumi.com/docs/ai/skills/) |
| Terramate Agent Skills | Terramate 官方 agent skills，面向 Terraform/OpenTofu/Terramate 栈管理、编排、CI/CD、drift 和 Cloud 集成。 | IaC / Stack management skills | [Open](https://github.com/terramate-io/agent-skills) |
| Terraform & OpenTofu Skill | Terraform / OpenTofu skill，覆盖测试、模块开发、远程 state、锁、迁移、CI/CD 和生产模式。 | Terraform / OpenTofu skill | [Open](https://github.com/antonbabenko/terraform-skill) |
| FluxCD Agent Skills | FluxCD 相关 agent skills，帮助 AI agents 处理 GitOps 工程和 Kubernetes 集群排障。 | GitOps / Kubernetes skills | [Open](https://github.com/fluxcd/agent-skills) |
| GitOps Cluster Debug | FluxCD agent skill 中的 GitOps 集群排障 skill，用于检查 Flux 资源状态、controller logs、依赖链和安装健康状态。 | GitOps debugging skill | [Open](https://github.com/fluxcd/agent-skills/blob/main/skills/gitops-cluster-debug/SKILL.md) |
| KubeShark Kubernetes Skill | 面向 Claude Code 和 Codex 的 Kubernetes skill，用于生成和审查更安全的 Kubernetes、Helm、Kustomize 配置。 | Kubernetes skill | [Open](https://github.com/LukasNiessen/kubernetes-skill) |
| Terminal Skills | 面向终端和 Kubernetes 的公开 Agent Skills，适合 DevOps 命令行操作和 Kubernetes 相关工作流。 | Terminal / Kubernetes skills | [Open](https://github.com/chaterm/terminal-skills) |
| Dash0 Agent Skills | Dash0 的 OpenTelemetry skills，面向 instrumentation、Collector 配置、语义约定、OTTL 和可观测性工作流。 | Observability skills | [Open](https://github.com/dash0hq/agent-skills) |
| Elastic Agent Skills | Elastic 官方 Agent Skills，面向 Elasticsearch、搜索、可观测性和 Elastic 平台相关工作流。 | Search / Observability skills | [Open](https://github.com/elastic/agent-skills) |
| Elastic MCP Server | Elastic 官方 Elasticsearch MCP server，让 agents 通过 MCP 查询、检索和分析 Elasticsearch indices。 | Observability / Search MCP server | [Open](https://github.com/elastic/mcp-server-elasticsearch) |
| Docker MCP Catalog | Docker MCP Catalog 收集经过打包的 verified MCP servers，适合 DevOps 环境中本地运行和管理 MCP servers。 | MCP catalog / DevOps tool | [Open](https://docs.docker.com/ai/mcp-catalog-and-toolkit/catalog/) |
| Docker MCP Registry | Docker 官方 MCP Registry 仓库，包含可用于 Docker MCP Catalog 和 Docker Desktop MCP Toolkit 的 server 定义。 | MCP registry | [Open](https://github.com/docker/mcp-registry) |
| Docker Agent | Docker Engineering 的 AI Agent Builder and Runtime，可用于创建、运行、打包和分发 agent 工作流。 | Agent runtime / DevOps tool | [Open](https://github.com/docker/docker-agent) |
| Docker Development Skill | Docker image development skill，覆盖 Dockerfile 最佳实践、CI 测试模式和 Docker Compose 编排。 | Docker skill | [Open](https://github.com/netresearch/docker-development-skill) |
| DevOps Skills for Claude Code and Codex | DevOps skill pack，包含生产配置生成器、验证器和 Kubernetes 集群排障 skill。 | DevOps skill pack | [Open](https://github.com/akin-ozer/cc-devops-skills) |
| Cloud / DevOps Workflow Bundle | Cloud / DevOps workflow bundle，覆盖 AWS、Azure、GCP、Kubernetes、Terraform、CI/CD、监控和云原生开发。 | Workflow bundle | [Open](https://github.com/christophacham/agent-skills-library/blob/main/skills/devops/cloud-devops/SKILL.md) |
| Awesome DevOps Skills | 自动整理的 DevOps 和 Cloud-Native Skills / MCP 仓库索引，适合继续发现更多 DevOps 相关项目。 | Awesome list / Index | [Open](https://github.com/derisk-ai/awesome-devops-skills) |
| DevOps & CI/CD Skills Marketplace | Claude Code DevOps & CI/CD skills 分类页，收集部署、CI/CD、监控和基础设施相关 skills。 | Skill marketplace category | [Open](https://claudemarketplaces.com/skills/category/devops) |
| Deployment & DevOps Agent Skills | MCPMarket 的 deployment & devops agent skills 分类，适合发现部署、CI/CD 和运维类 skills。 | Skill directory category | [Open](https://mcpmarket.com/tools/skills/categories/deployment-devops) |

## Coding / Software Engineering Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Addy Osmani Agent Skills | 面向 AI coding agents 的生产级软件工程 skills，覆盖需求澄清、计划、实现、测试、审查和发布等完整工程流程。 | Engineering workflow skills | [Open](https://github.com/addyosmani/agent-skills) |
| Matt Pocock Skills | 面向真实软件工程场景的 agent skills，强调工程基本功、可控流程和实际项目开发，而不是简单 vibe coding。 | Engineering skills | [Open](https://github.com/mattpocock/skills) |
| Systango Agent Skill Library | 生产级 engineering skills 集合，用于让 AI coding agents 遵循 senior engineer 的工作流、质量门禁和最佳实践。 | Engineering skill library | [Open](https://github.com/SystangoTechnologies/agent-skill-library) |
| Swell Coding Skills | 面向软件工程的 Anthropic-style skills，覆盖 TDD、Code Review、架构、GitHub Issues 项目管理和语言约定。 | Software engineering skills | [Open](https://github.com/swell-agents/coding-skills) |
| Solid Skills | 面向 AI coding agents 的 SOLID、TDD、clean code 和专业软件设计 skills。 | Clean code / Design skills | [Open](https://github.com/ramziddin/solid-skills) |
| Armory | 面向认真使用 AI 的开发者的生产级 coding agent skills，包含 TDD、安全、调试和开发流程。 | Engineering skill pack | [Open](https://github.com/Mathews-Tom/armory) |
| Agent QA | 面向 Codex、Claude Code 等 coding agents 的 QA skill pack，包含自然语言 Web/移动端测试编写、结果分诊和调试修复三类 skills，并提供 33-tool MCP 接口；当前 FSL-1.1-ALv2 为 source-available。 | QA skill pack / MCP tool | [Open](https://github.com/vostride/agent-qa) |
| Hypergiant Agent Skills | 面向 AI coding agents 的 skill 集合，包含 skill 管理、Next.js 最佳实践和安全模式等工程能力。 | Coding agent skills | [Open](https://github.com/gohypergiant/agent-skills) |
| Softaworks Agent Toolkit | AI coding agent skills 集合，可用于 Claude Code、Claude.ai 或手动加载 `SKILL.md` 内容。 | Coding agent toolkit | [Open](https://github.com/softaworks/agent-toolkit) |
| Iliaal AI Skills | 紧凑、偏工程决策的 coding agent skills，覆盖 React、Next.js、Node.js backend、测试和项目结构。 | Opinionated coding skills | [Open](https://github.com/iliaal/ai-skills) |
| Claude Software Skills | 面向 Claude Code 的 55 个模块化软件开发 skills，覆盖架构、开发、测试、部署等环节。 | Claude Code software skills | [Open](https://github.com/miles990/claude-software-skills) |
| Geekswamp Agent Skills | 可复用 Codex engineering skills，包含 Go 测试、Flutter 测试、changelog 和 Conventional Commit message 生成。 | Codex engineering skills | [Open](https://github.com/geekswamp/agent-skills) |
| Yansir Agent Skills | 面向 coding agents 的实用技能集合，包括项目接手、重构、简化设计、重新思考方案和发布 skill。 | Engineering workflow skills | [Open](https://github.com/yansircc/agent-skills) |
| Adeonir Agent Skills | 个人维护的 AI coding agent skills，覆盖调试循环、Git helpers、PR summaries、项目索引和代码审查。 | Engineering helper skills | [Open](https://github.com/adeonir/agents-skills) |
| LLl0k0laD Agent Skills | 用结构化 workflow 和工程最佳实践增强 AI coding agents，偏向可靠 Web 应用开发。 | Web engineering skills | [Open](https://github.com/LLl0k0laD/agent-skills) |
| Meta Agent Skills | 用于标准化和自动化软件工程流程的 meta-agent skills 框架。 | Meta engineering skills | [Open](https://github.com/yu-iskw/meta-agent-skills) |
| Agent Toolkit | 面向 AI coding agents 的 production-ready skills 和 agents，覆盖 plan、build、test、debug、ship。 | Coding agent toolkit | [Open](https://github.com/jvalin17/agent-toolkit) |
| Claude Skills Marketplace | Claude Code software engineering workflow skills，覆盖 Git automation、testing 和 code review。 | Claude Code skills marketplace | [Open](https://github.com/mhattingpete/claude-skills-marketplace) |
| Wshobson Agents Skills | Claude plugin ecosystem 文档中包含大量 specialized skills，适合查找软件工程、语言、框架和工具类能力。 | Claude plugin / Skill ecosystem | [Open](https://github.com/wshobson/agents) |
| AbsolutelySkilled | 开放式 AI Agent Skills registry，包含 requirements、planning、execution、verification、TDD、lint、typecheck 和 build checks。 | Skill registry | [Open](https://github.com/AbsolutelySkilled/AbsolutelySkilled) |
| Vercel Agent Skills | Vercel 官方 AI coding agent skills，包含 React / Next.js 性能、Web 设计、组件组合和前端工程最佳实践。 | Frontend engineering skills | [Open](https://github.com/vercel-labs/agent-skills) |
| Vercel React Best Practices | React 和 Next.js 性能优化 skill，适合编写、审查和重构 React / Next.js 代码。 | React / Next.js skill | [Open](https://github.com/vercel-labs/agent-skills/blob/main/skills/react-best-practices/SKILL.md) |
| Vercel Next Skills | Next.js Agent Skills，覆盖 Next.js 16、Cache Components、PPR、升级和 Next.js 工程最佳实践。 | Next.js skills | [Open](https://github.com/vercel-labs/next-skills) |
| Next.js 16 Agent Skills | 面向 AI coding agents 的 Next.js、Prisma、AI SDK、Auth.js 等现代 Web 开发 skills。 | Next.js / Full-stack skills | [Open](https://github.com/gocallum/nextjs16-agent-skills) |
| Agent Skills Hub | 跨平台 agent skills hub，包含 Angular 等 framework skills，可用于 OpenClaw、Claude Code、Gemini、Cursor、Antigravity 等。 | Framework skill hub | [Open](https://github.com/agent-skills-hub/agent-skills-hub) |
| Angular Agent Kit | 面向 Angular 的 AI agent skills，包含 Angular 模板优化、结构化 skill 文件和多 agent 兼容支持。 | Angular skills | [Open](https://github.com/sajeetharan/angular-agent-kit) |
| Angular Agent Skills | Angular 多版本支持和迁移相关 agent skills，适合 Angular 项目升级和组件模式迁移。 | Angular skills | [Open](https://github.com/araujomartin/angular-agent-skills) |
| Gemini Angular Architect Skill | Gemini agent skill 中的 Angular architect skill，用于 Angular 架构、组件和工程模式。 | Angular architecture skill | [Open](https://github.com/saeed-vayghan/gemini-agent-skills/blob/master/.gemini/skills/angular-architect/SKILL.md) |
| Clerk Skills | Clerk 官方 skills，帮助 AI coding agents 正确集成 Clerk 认证和用户管理，覆盖 Next.js、React、Vue、Nuxt、Astro、TanStack 等。 | Authentication skills | [Open](https://github.com/clerk/skills) |
| Auth0 Agent Skills | Auth0 官方 agent skills，帮助 coding assistants 正确实现 Auth0 登录、认证和多框架集成。 | Authentication skills | [Open](https://github.com/auth0/agent-skills) |
| Auth0 Quickstart Skill | Auth0 quickstart skill，可根据技术栈路由到 React、Next.js、Vue、Nuxt、Angular、Express、FastAPI、ASP.NET Core、React Native、Expo 等认证流程。 | Authentication quickstart skill | [Open](https://github.com/auth0/agent-skills/blob/main/plugins/auth0/skills/auth0-quickstart/SKILL.md) |
| Laravel Agent Skills | Laravel 官方 agent skills，可作为 Claude Code 和 Cursor 插件使用，面向 Laravel、Laravel Cloud 和 Nightwatch。 | Laravel skills | [Open](https://github.com/laravel/agent-skills) |
| Expo Skills | Expo 官方 AI agent skills，用于构建、部署、升级和调试 Expo / React Native 应用。 | Expo / React Native skills | [Open](https://github.com/expo/skills) |
| Flutter Skills | Flutter 团队维护的 Agent Skills，用于 Flutter app 开发、布局、导航、测试和常见工程工作流。 | Flutter skills | [Open](https://github.com/flutter/skills) |
| Dart / Flutter Dash Skills | Dart 与 Flutter ecosystem 的 Agent Skills，每个 skill 使用 `SKILL.md` 定义何时和如何被使用。 | Dart / Flutter skills | [Open](https://github.com/kevmoo/dash_skills) |
| Flutter AI Rules | Flutter AI skills / rules，适合 Cursor、Copilot、Antigravity 等工具使用，覆盖 Flutter 架构、BLoC、测试和项目约定。 | Flutter skills / Rules | [Open](https://github.com/evanca/flutter-ai-rules) |
| Agent Skills Library | 大型 agent skills library，包含移动端、Flutter、DevOps、后端、前端等多个领域 skills。 | Multi-domain skill library | [Open](https://github.com/christophacham/agent-skills-library) |
| Agent Skills Standard | 面向多 framework / language 的 agent skills standard 示例库，包含 Flutter testing、Retrofit networking 等 skills。 | Framework skill library | [Open](https://github.com/HoangNguyen0403/agent-skills-standard) |
| Supabase Agent Skills | Supabase 官方 agent skills，帮助 AI coding agents 正确使用 Supabase、Postgres、RLS、Edge Functions 和数据库工作流。 | Backend / Database skills | [Open](https://github.com/supabase/agent-skills) |
| Stripe AI Skills | Stripe AI 仓库中的 skills，用于构建、修改和审查 Stripe 集成，包括支付、订阅、marketplaces 和安全 key handling。 | Payment integration skills | [Open](https://github.com/stripe/ai) |
| Stripe Best Practices Skill | Stripe best practices skill，适合构建、修改或审查 Stripe 支付和 billing 集成。 | Stripe integration skill | [Open](https://github.com/stripe/ai/blob/main/skills/stripe-best-practices/SKILL.md) |
| Remotion Skills | Remotion 官方 skills，用于 React programmatic video / animation 项目中的最佳实践和代码生成。 | React video skills | [Open](https://github.com/remotion-dev/skills) |
| Remotion Best Practices Skill | Remotion best practices skill，适合处理 Remotion 代码、视频生成、React composition 和 animation。 | Remotion coding skill | [Open](https://github.com/remotion-dev/skills/blob/main/skills/remotion/SKILL.md) |
| Hookdeck Agent Skills | Hookdeck agent skills，帮助 coding agents 处理 webhook、event gateway、本地测试和事件驱动架构。 | Webhook / Event skills | [Open](https://github.com/hookdeck/agent-skills) |
| Hookdeck Webhook Skills | Webhook skills，提供 Express、Next.js、FastAPI 等场景下的签名验证、事件处理、重试和调试示例。 | Webhook skills | [Open](https://github.com/hookdeck/webhook-skills) |
| BjornMelin Dev Skills | 面向 AI coding agents 的 reusable dev skills，覆盖 AI SDK、Codex、LangGraph、Supabase、Docker、Vitest、pytest、Streamlit、Zod 等。 | Developer skill library | [Open](https://github.com/BjornMelin/dev-skills) |
| Docker Development Skill | Docker image development skill，覆盖 Dockerfile 最佳实践、CI 测试模式和 Docker Compose 编排。 | Docker engineering skill | [Open](https://github.com/netresearch/docker-development-skill) |
| AGENTS.md | 面向 AI coding agents 的开放 Markdown 指令格式，用于提供项目结构、构建命令、测试流程和代码风格。 | Coding agent instruction standard | [Open](https://agents.md/) |
| AGENTS.md Generator Skill | 生成和维护 AGENTS.md 文件的 Agent Skill，支持 Claude Code、Cursor、GitHub Copilot 和其他兼容 agents。 | AGENTS.md skill | [Open](https://github.com/netresearch/agents-skill) |
| SkillKit | 用于在 Claude Code、Cursor、Codex、Copilot 等 40+ agent 之间安装、转换和共享 portable skills 的工具。 | Skill installer / Converter | [Open](https://github.com/rohitg00/skillkit) |
| OpenSkills | 通用 SKILL.md installer / loader，把 Anthropic-style skills 带到 Claude Code、Cursor、Windsurf、Aider、Codex 等 agent。 | Skill installer / Loader | [Open](https://github.com/numman-ali/openskills) |
| Oh My Skills | Codex、Claude Code、Gemini 等工具可用的 skills 集合，包含 Supabase、Payload CMS 等工程场景。 | Multi-agent skill collection | [Open](https://github.com/akillness/oh-my-skills) |
| Awesome Cursor Skills | Cursor skills 合集，收集可放入 `.cursor/skills/` 的 `SKILL.md` 文件，用于工程 workflow 和项目脚手架。 | Cursor skills list | [Open](https://github.com/spencerpauly/awesome-cursor-skills) |
| Windsurf Agents | Windsurf agent skills、workflows 和自动化脚本集合，面向 Windsurf / Cascade 开发工作流。 | Windsurf skills / Workflows | [Open](https://github.com/zenmindhacker/windsurf-agents) |
| Hoodini AI Agents Skills | 面向 Claude Code、GitHub Copilot、Cursor、Windsurf、Cline、Aider、Continue.dev 等 coding agents 的技能集合。 | Multi-agent coding skills | [Open](https://github.com/hoodini/ai-agents-skills) |
| Kodu Awesome Agent Skills | 面向软件工程的 Agent Skills 列表，由 Kodus 工程团队维护，适合继续发现更多 coding skills。 | Software engineering skill index | [Open](https://github.com/kodustech/awesome-agent-skills) |
| Awesome Agent Skills by VoltAgent | 大型 Agent Skills 索引，包含官方和社区工程 skills，可按 coding、framework、DevOps 等方向继续筛选。 | Skill index | [Open](https://github.com/VoltAgent/awesome-agent-skills) |

## Data / Research / Document Skills

| Name | 简单描述 | 类型 | 链接 |
|---|---|---|---|
| Anthropic Document Skills | Anthropic 官方 skills 中的文档处理集合，包含 Word、PDF、PowerPoint、Excel 和协作文档相关能力。 | Document skill library | [Open](https://github.com/anthropics/skills/tree/main/skills) |
| Anthropic DOCX | 创建、读取、编辑和分析 Microsoft Word `.docx` 文档，适合报告、合同、论文草稿和正式文档处理。 | Word document skill | [Open](https://github.com/anthropics/skills/tree/main/skills/docx) |
| Anthropic PDF | 读取、提取、合并、拆分、旋转、加水印、填写表单和处理 PDF 文件。 | PDF skill | [Open](https://github.com/anthropics/skills/tree/main/skills/pdf) |
| Anthropic PPTX | 创建、编辑、读取和组合 PowerPoint `.pptx` 演示文稿。 | Presentation skill | [Open](https://github.com/anthropics/skills/tree/main/skills/pptx) |
| Anthropic XLSX | 创建、编辑、读取和分析 Excel `.xlsx` 表格，适合数据分析、公式、图表和财务模型。 | Spreadsheet skill | [Open](https://github.com/anthropics/skills/tree/main/skills/xlsx) |
| Anthropic Document Coauthoring | 结构化协作文档写作 skill，用于文档共创、上下文收集、内容迭代和读者测试。 | Writing / Document skill | [Open](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) |
| Anthropic Internal Comms | 用于内部沟通、公告、团队更新、邮件和组织内信息表达。 | Communication writing skill | [Open](https://github.com/anthropics/skills/tree/main/skills/internal-comms) |
| OpenAI Skills | OpenAI / Codex 官方 skills catalog，包含 PDF、Jupyter、Notion、截图、语音、转录等数据和文档相关 skills。 | Codex skill catalog | [Open](https://github.com/openai/skills) |
| OpenAI PDF | OpenAI curated PDF skill，用于读取、创建、检查和处理 PDF，强调渲染预览和版面检查。 | PDF skill | [Open](https://github.com/openai/skills/blob/main/skills/.curated/pdf/SKILL.md) |
| OpenAI Jupyter Notebook | OpenAI curated Jupyter Notebook skill，适合数据探索、分析、实验记录和可复现 notebook 工作流。 | Notebook / Data analysis skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/jupyter-notebook) |
| OpenAI Notion Knowledge Capture | 将信息整理进 Notion 知识库，适合研究笔记、资料沉淀和结构化知识管理。 | Knowledge management skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/notion-knowledge-capture) |
| OpenAI Notion Meeting Intelligence | 面向会议纪要、行动项、总结和团队知识沉淀的 Notion workflow skill。 | Meeting / Knowledge skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/notion-meeting-intelligence) |
| OpenAI Notion Research Documentation | 面向研究资料整理、调研文档、分析记录和知识库写入的 Notion skill。 | Research documentation skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/notion-research-documentation) |
| OpenAI Screenshot | 用于截图分析、界面检查、视觉证据整理和基于图像的工作流记录。 | Screenshot / Visual evidence skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/screenshot) |
| OpenAI Speech | 面向语音生成、音频输出和 speech workflow 的 OpenAI curated skill。 | Speech skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/speech) |
| OpenAI Transcribe | 面向音频转录、会议记录、访谈整理和语音资料处理的 OpenAI curated skill。 | Transcription skill | [Open](https://github.com/openai/skills/tree/main/skills/.curated/transcribe) |
| Codex Datasets and Reports | OpenAI Codex 数据分析用例，面向清洗数据、探索假设、建模、可视化和生成可复用报告。 | Data analysis guide | [Open](https://developers.openai.com/codex/use-cases/datasets-and-reports) |
| Skywork Skills | Skywork Agent Skills for AI office suites，包含 AI PPT、Document、Excel、Search/DeepResearch、Image 和 Music。 | Office / Research skill library | [Open](https://github.com/SkyworkAI/Skywork-Skills) |
| Skywork Doc | 从 prompts 和参考文件生成专业文档，支持 docx、pdf、html、markdown，并可结合网页搜索补充资料。 | Document generation skill | [Open](https://github.com/SkyworkAI/Skywork-Skills/tree/main/skywork-doc) |
| Skywork PPT | 生成、模仿和编辑 PowerPoint，可从主题创建，也可用现有 `.pptx` 作为风格模板。 | Presentation skill | [Open](https://github.com/SkyworkAI/Skywork-Skills/tree/main/skywork-ppt) |
| Skywork Excel | 创建 Excel 文件、写入数据、公式和图表，分析已有表格，并生成 HTML 分析报告。 | Spreadsheet / Data analysis skill | [Open](https://github.com/SkyworkAI/Skywork-Skills/tree/main/skywork-excel) |
| Skywork Search | 面向实时信息检索、研究、事实核查和内容生成的 AI-powered web search skill。 | Search / DeepResearch skill | [Open](https://github.com/SkyworkAI/Skywork-Skills/tree/main/skywork-search) |
| MiniMax Skills | MiniMax AI 团队的 skills 集合，包含文档、PDF、Excel、PPT、视觉分析和多模态工具能力。 | Multimodal / Document skill library | [Open](https://github.com/MiniMax-AI/skills) |
| MiniMax DOCX | 面向 Word 文档创建、读取、编辑和结构化处理的 MiniMax skill。 | Word document skill | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/minimax-docx) |
| MiniMax PDF | 面向 PDF 读取、生成、提取和复杂 PDF 处理的 MiniMax skill。 | PDF skill | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/minimax-pdf) |
| MiniMax XLSX | 读取、分析、创建和编辑 Excel / CSV / TSV 文件，支持公式、格式和表格数据验证。 | Spreadsheet / Data skill | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/minimax-xlsx) |
| MiniMax PPTX Generator | 用于生成 PowerPoint 演示文稿，适合报告、研究展示和汇报材料。 | Presentation skill | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/pptx-generator) |
| MiniMax Vision Analysis | 面向图像、截图、视觉材料和多模态信息分析的 MiniMax skill。 | Vision analysis skill | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/vision-analysis) |
| MiniMax Multimodal Toolkit | MiniMax 多模态工具 skill，可作为图像、文档、视觉和多媒体工作流的扩展能力。 | Multimodal toolkit | [Open](https://github.com/MiniMax-AI/skills/tree/main/skills/minimax-multimodal-toolkit) |
| Univer Skills | Univer 官方 spreadsheet automation skills，面向 Claude Code、Codex 和 Cursor 的 workbook 自动化工作流。 | Spreadsheet automation skills | [Open](https://github.com/dream-num/skills) |
| Univer CLI | workbook-native skill，用于表格检查、导入导出、公式审查、有限范围编辑和验证优先的电子表格处理。 | Spreadsheet CLI skill | [Open](https://github.com/dream-num/skills/tree/main/skills/univer-cli) |
| Univer SIT | Git-shaped workbook repo workflow，用于表格版本历史、review session、diff、blame、push/pull 和协作交付。 | Spreadsheet collaboration skill | [Open](https://github.com/dream-num/skills/tree/main/skills/sit) |
| Scientific Agent Skills | K-Dense-AI 的科学研究 skills 集合，覆盖科学数据库、Python 科学包、文献综述、数据分析、写作和科研图表。 | Scientific research skill library | [Open](https://github.com/K-Dense-AI/scientific-agent-skills) |
| Scientific Literature Review | 面向系统性文献综述、meta-analysis、研究综合和跨数据库学术检索的 scientific skill。 | Literature review skill | [Open](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/scientific-skills/literature-review) |
| InternScience Awesome Scientific Skills | 面向科学研究的 Agent Skills 开放合集，适合作为继续发现科研 skills 的入口。 | Scientific skills index | [Open](https://github.com/InternScience/Awesome-Scientific-Skills) |
| Agent Research Skills | 覆盖学术论文完整生命周期的 Claude Code skills，从文献搜索到论文写作、图表、引用、审稿和 slides。 | Academic research skill library | [Open](https://github.com/lingzhi227/agent-research-skills) |
| Deep Research | 6 阶段系统性文献调查 skill，覆盖 frontier survey、deep dive、代码检索、综合和报告生成。 | Deep research skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/deep-research) |
| Literature Search | 多源学术检索 skill，支持 Semantic Scholar、arXiv、OpenAlex、CrossRef 等来源。 | Academic search skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/literature-search) |
| Literature Review | 多视角文献综述 skill，通过专家 persona 组织 grounded literature review。 | Literature review skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/literature-review) |
| Idea Generation | 生成和评分研究想法，关注 interestingness、feasibility 和 novelty。 | Research ideation skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/idea-generation) |
| Novelty Assessment | 通过多轮文献搜索和 harsh-critic 视角评估研究想法的新颖性。 | Novelty assessment skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/novelty-assessment) |
| Research Planning | 设计研究计划、任务依赖图和实验推进路线。 | Research planning skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/research-planning) |
| Data Analysis | 统计分析 skill，包含统计摘要、p-value 格式化和多轮代码审查流程。 | Statistical analysis skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/data-analysis) |
| Paper Writing Section | 面向论文各章节的写作 skill，包含 section-specific guidance 和两轮 refinement。 | Academic writing skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/paper-writing-section) |
| Related Work Writing | 面向 Related Work 的写作 skill，强调主题组织、对比关系和文献定位。 | Academic writing skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/related-work-writing) |
| Survey Generation | 通过 RAG-based subsection writing 和 citation validation 生成完整 survey paper。 | Survey writing skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/survey-generation) |
| Figure Generation | 生成 publication-quality matplotlib figures，并通过反馈循环改进图表质量。 | Scientific visualization skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/figure-generation) |
| Table Generation | 将 JSON / CSV 结果转换成 LaTeX booktabs 表格，支持 bold-best、显著性标记和多数据集结果。 | Research table skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/table-generation) |
| Citation Management | BibTeX harvesting、citation validation、去重和自动修复引用问题。 | Citation management skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/citation-management) |
| LaTeX Formatting | 针对 ICML、ICLR、NeurIPS、AAAI、ACL 等会议模板进行 LaTeX 格式检查和修复。 | LaTeX formatting skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/latex-formatting) |
| Paper Compilation | pdflatex + bibtex 编译 pipeline，包含自动修复错误的循环。 | Paper compilation skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/paper-compilation) |
| Self Review | 使用多 persona 自动审稿，按 NeurIPS 风格生成 review、reflection 和 meta-review。 | Paper review skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/self-review) |
| Paper Revision | 将 reviewer concerns 映射到论文部分，进行有针对性的修改并验证改进效果。 | Paper revision skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/paper-revision) |
| Rebuttal Writing | 面向审稿意见的逐点 rebuttal 写作，强调证据支撑和回应结构。 | Rebuttal writing skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/rebuttal-writing) |
| Slide Generation | 从论文生成 Beamer slides，提取论文元素、生成幻灯片骨架并简化内容。 | Research presentation skill | [Open](https://github.com/lingzhi227/agent-research-skills/tree/main/skills/slide-generation) |
| Research Paper Review | BESSER-PEARL 的 research-paper-review skill，用于论文评审、方法分析、关键发现提取、数值一致性检查和创新性评估。 | Research paper review skill | [Open](https://github.com/BESSER-PEARL/agent-skills/blob/main/research-paper-review/SKILL.md) |
| Academic Research Skills | 面向 Claude Code 的学术研究 skills，包含 deep research、quick review、lit-review、fact-check、systematic-review 等模式。 | Academic research skills | [Open](https://github.com/Imbad0202/academic-research-skills) |
| Research Paper Writing Skills | 面向科研论文写作的 skills，适合摘要、引言、方法、实验、结论、段落逻辑和投稿前自查。 | Academic writing skills | [Open](https://github.com/Master-cai/Research-Paper-Writing-Skills) |
| Agent Papers CLI | Agent-driven deep research workflow，包含面向科研工作流的 Claude Code skills 和 slash commands。 | Deep research CLI / Skills | [Open](https://github.com/collaborative-deep-research/agent-papers-cli) |
| Hermes Research Paper Writing Pipeline | NousResearch Hermes Agent 中的 research paper writing pipeline，覆盖实验设计、执行、分析、写作、审稿和投稿。 | Research writing pipeline | [Open](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/skills/bundled/research/research-research-paper-writing.md) |
| Eigent Agent Skills | 包含 PDF、DOCX 等 reusable AI agent skills，适合文档提取、编辑、OCR 和 office workflow。 | Document skill library | [Open](https://github.com/eigent-ai/agent-skills) |
| Nymbo Skills | 收集高质量 agent skills，其中 document processing 部分包含 PDF、DOCX、PPTX、XLSX。 | Skill library / Document skills | [Open](https://github.com/Nymbo/Skills) |
| FAR Skill | 文件分析和读取 skill，支持 PDF、Word、Excel、PowerPoint、图像 OCR 和多格式内容提取。 | File analysis skill | [Open](https://github.com/mr-kelly/far/blob/master/skills/far/SKILL.md) |
| Working with Spreadsheets | 面向 Excel、财务模型、公式、格式和数据分析的 spreadsheet skill。 | Spreadsheet / Financial modeling skill | [Open](https://github.com/mjunaidca/mjs-agent-skills/blob/main/.claude/skills/working-with-spreadsheets/SKILL.md) |
| Google Workspace CLI | Google Workspace CLI，可作为 Gmail、Drive、Calendar、Docs、Sheets、Slides、Forms、Keep 等办公数据 workflow 的入口。 | Workspace / Productivity tool | [Open](https://github.com/googleworkspace/cli) |
| Notion MCP Server | Notion 官方 MCP server，用于连接 Notion API，适合知识库、文档和团队资料管理。 | Knowledge management MCP server | [Open](https://github.com/makenotion/notion-mcp-server) |
| Exa MCP Server | Exa 官方 MCP server，提供 web search、code search、web crawling 和 company research。 | Search / Research MCP server | [Open](https://github.com/exa-labs/exa-mcp-server) |
| Brave Search MCP Server | Brave Search MCP server，提供网页、本地、图片、视频、新闻和 LLM context search。 | Search MCP server | [Open](https://github.com/brave/brave-search-mcp-server) |
| Firecrawl MCP Server | Firecrawl MCP server，提供网页抓取、搜索、批处理和结构化内容提取。 | Web data extraction MCP server | [Open](https://github.com/firecrawl/firecrawl-mcp-server) |
| Apify MCP Server | Apify MCP server，让 agents 使用 Apify Store 中的 crawlers、scrapers、social media、maps 和 e-commerce 工具。 | Web automation / Data extraction MCP server | [Open](https://github.com/apify/apify-mcp-server) |
| DeepWiki MCP | DeepWiki MCP server，用于访问 GitHub repo 的 wiki、结构化文档和代码库问答。 | Codebase documentation MCP server | [Open](https://cognition.ai/blog/deepwiki-mcp-server) |
| Context7 | 为 AI coding tools 提供最新、版本相关的库文档和代码示例，可用于技术文档检索。 | Documentation MCP server | [Open](https://github.com/upstash/context7) |

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
