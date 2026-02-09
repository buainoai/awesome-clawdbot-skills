<div align="center">

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="social" src="https://github.com/user-attachments/assets/fac18063-135d-4235-a015-a251f29d90f3" />
</a>

<br/>
<br/>

<div align="center">
    <strong>精选的 Clawdbot 技能合集 - 565+ 个社区构建的技能，分类整理便于发现</strong>
    <br />
    <strong>A collection of 565+ community-built skills for Clawdbot, categorized for easy discovery</strong>
    <br />
    <br />
    <a href="https://github.com/VoltAgent/awesome-clawdbot-skills">📖 原始项目 Original Project</a> |
    <a href="https://moltskills.org">🌐 在线浏览 Browse Online</a> |
    <a href="README_en.md">🌐 English Version</a> |
    <a href="关于本项目.md">ℹ️ 关于本项目</a>
    <br />
    <br />
</div>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a> 

![Skills Count](https://img.shields.io/badge/skills-565+-blue?style=flat-square)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-clawdbot-skills?label=Last%20update&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![GitHub forks](https://img.shields.io/github/forks/VoltAgent/awesome-clawdbot-skills?style=social)](https://github.com/VoltAgent/awesome-claude-skills/network/members)
</div>

# 超棒的 Clawdbot 技能 Awesome Clawdbot Skills

Clawdbot 是一款本地运行的 AI 助手，直接在您的设备上操作。Skills 扩展其功能，使其能够与外部服务交互、自动化工作流程并执行专门任务。本合集帮助您发现并安装适合需求的 Skills。

此列表中的技能来源于 ClawdHub（Clawdbot 的公共技能注册中心），并进行了分类以便于查找。

这些技能遵循Anthropic开发的Agent Skill规范，该规范是AI编码助手的开放标准。

## 安装

### ClawdHub 命令行界面 (CLI)

```bash
npx clawdhub@latest install <skill-slug>
```

### 手动安装

将技能文件夹复制到以下任一位置：

| 位置 | 路径 |
|------|------|
| 全局 | `~/.clawdbot/skills/` |
| 工作区 | `<project>/skills/` |

优先级：工作区 > 本地 > 内置


## 目录

- [Web & Frontend Development](#web--frontend-development) (17)
- [Coding Agents & IDEs](#coding-agents--ides) (16)
- [Git & GitHub](#git--github) (9)
- [DevOps & Cloud](#devops--cloud) (35)
- [Browser & Automation](#browser--automation) (8)
- [Image & Video Generation](#image--video-generation) (9)
- [Apple Apps & Services](#apple-apps--services) (11)
- [Search & Research](#search--research) (12)
- [Clawdbot Tools](#clawdbot-tools) (13)
- [CLI Utilities](#cli-utilities) (37)
- [Marketing & Sales](#marketing--sales) (36)
- [Productivity & Tasks](#productivity--tasks) (33)
- [AI & LLMs](#ai--llms) (31)
- [Finance & Crypto](#finance--crypto) (30)
- [Media & Streaming](#media--streaming) (27)
- [Notes & PKM](#notes--pkm) (26)
- [iOS & macOS Development](#ios--macos-development) (13)
- [Transportation](#transportation) (25)
- [Personal Development](#personal-development) (22)
- [Health & Fitness](#health--fitness) (21)
- [Communication](#communication) (19)
- [Speech & Transcription](#speech--transcription) (17)
- [Smart Home & IoT](#smart-home--iot) (16)
- [Shopping & E-commerce](#shopping--e-commerce) (16)
- [Calendar & Scheduling](#calendar--scheduling) (14)
- [PDF & Documents](#pdf--documents) (12)
- [Self-Hosted & Automation](#self-hosted--automation) (9)
- [News & RSS](#news--rss) (8)
- [Bookmarks & Reading](#bookmarks--reading) (7)
- [Weather](#weather) (5)
- [Security & Passwords](#security--passwords) (3)



<a href="https://github.com/VoltAgent/voltagent">
<img width="1390" height="296" alt="social" src="https://github.com/user-attachments/assets/4c40affa-8e20-443a-9ec5-1abb6679b170" />
</a>

## 网页与前端开发

- [discord](https://github.com/clawdbot/skills/tree/main/skills/steipete/discord/SKILL.md) - 当需要通过 Clawdbot 使用 discord 工具控制 Discord（发送消息、添加表情反应）时使用。
- [frontend-design](https://github.com/clawdbot/skills/tree/main/skills/steipete/frontend-design/SKILL.md) - 创建具有高设计质量的独特生产级前端界面。
- [linux-service-triage](https://github.com/clawdbot/skills/tree/main/skills/kowl64/linux-service-triage/SKILL.md) - 通过日志、systemd/PM2 和文件权限诊断常见的 Linux 服务问题。
- [miniflux-news](https://github.com/clawdbot/skills/tree/main/skills/hartlco/miniflux-news/SKILL.md) - 从 Miniflux 实例中获取并分类最新未读的 RSS/新闻条目。
- [pinak-frontend-guru](https://github.com/clawdbot/skills/tree/main/skills/sharanga10/pinak-frontend-guru/SKILL.md) - 资深UI/UX及React性能审计专家（PinakBot角色）。
- [remotion-best-practices](https://github.com/clawdbot/skills/tree/main/skills/am-will/remotion-best-practices/SKILL.md) - Remotion 的最佳实践 —— 使用 React 进行视频创作。
- [remotion-server](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/remotion-server/SKILL.md) - 使用 Remotion 进行无头视频渲染。适用于任何 Linux 服务器，无需 Mac 或图形界面。
- [slack](https://github.com/clawdbot/skills/tree/main/skills/steipete/slack/SKILL.md) - 当需要通过 Clawdbot 使用 slack 工具控制 Slack 时使用。
- [ui-audit](https://github.com/clawdbot/skills/tree/main/skills/tommygeoco/ui-audit/SKILL.md) - 用于自动化UI审核的AI技能。根据验证过的用户体验原则评估界面。
- [ui-skills](https://github.com/clawdbot/skills/tree/main/skills/correctroadh/ui-skills/SKILL.md) - 构建更优代理接口的明确约束。
- [ux-audit](https://github.com/clawdbot/skills/tree/main/skills/tommygeoco/ux-audit/SKILL.md) - 用于自动化设计审核的AI技能。根据经过验证的UX原则评估界面。
- [ux-decisions](https://github.com/clawdbot/skills/tree/main/skills/tommygeoco/ux-decisions/SKILL.md) - 由 Tommy Geoco 创建的 Making UX Decisions 框架（uxdecisions.com）中的 AI 技能。
- [vercel-react-best-practices](https://github.com/clawdbot/skills/tree/main/skills/sharanga10/vercel-react-best-practices/SKILL.md) - Vercel 工程团队提供的 React 和 Next.js 性能优化指南。
- [web-design-guidelines](https://github.com/clawdbot/skills/tree/main/skills/sharanga10/web-design-guidelines/SKILL.md) - 审查UI代码，确保符合Web Interface Guidelines规范。

## 编码代理与集成开发环境（IDEs）

- [agentlens](https://github.com/clawdbot/skills/tree/main/skills/nguyenphutrong/agentlens/SKILL.md) - 使用 agentlens 分层文档浏览和理解代码库。
- [claude-team](https://github.com/clawdbot/skills/tree/main/skills/jalehman/claude-team/SKILL.md) - 通过 claude-team MCP 服务器，使用 iTerm2 协同管理多个 Claude Code 工作节点。
- [codex-account-switcher](https://github.com/clawdbot/skills/tree/main/skills/odrobnik/codex-account-switcher/SKILL.md) - 管理多个 OpenAI Codex 账户。捕获当前登录令牌。
- [codex-monitor](https://github.com/clawdbot/skills/tree/main/skills/odrobnik/codex-monitor/SKILL.md) - 浏览存储在 ~/.codex/sessions 中的 OpenAI Codex 会话日志。
- [codex-orchestration](https://github.com/clawdbot/skills/tree/main/skills/shanelindsay/codex-orchestration/SKILL.md) - Codex 的通用编排工具。
- [codex-quota](https://github.com/clawdbot/skills/tree/main/skills/odrobnik/codex-quota/SKILL.md) - 使用本地会话日志检查 OpenAI Codex CLI 的速率限制状态（日常/每周配额）。
- [codexmonitor](https://github.com/clawdbot/skills/tree/main/skills/odrobnik/codexmonitor/SKILL.md) - 列出/检查/监控本地 OpenAI Codex 会话（CLI + VS Code）
- [coding-agent](https://github.com/clawdbot/skills/tree/main/skills/steipete/coding-agent/SKILL.md) - 运行 Codex CLI、Claude Code、OpenCode 或 Pi Coding Agent。
- [cursor-agent](https://github.com/clawdbot/skills/tree/main/skills/swiftlysingh/cursor-agent/SKILL.md) - Cursor CLI 代理的全面使用技能。
- [factory-ai](https://github.com/clawdbot/skills/tree/main/skills/mitchellbernstein/factory-ai/SKILL.md) - 使用 Factory AI 的 droid CLI 进行软件工程任务。
- [model-usage](https://github.com/clawdbot/skills/tree/main/skills/steipete/model-usage/SKILL.md) - 使用 CodexBar CLI 本地成本使用功能，汇总 Codex 各模型的使用情况。
- [opencode-acp-control](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/opencode-acp-control/SKILL.md) - 通过 Agent Client Protocol (ACP) 直接控制 OpenCode。
- [perry-coding-agents](https://github.com/clawdbot/skills/tree/main/skills/gricha/perry-coding-agents/SKILL.md) - 将编码任务分配到 Perry 工作区的 OpenCode 或 Claude Code。
- [perry-workspaces](https://github.com/clawdbot/skills/tree/main/skills/gricha/perry-workspaces/SKILL.md) - 使用 Claude Code 在您的 tailnet 上创建和管理独立的 Docker 工作区。
- [prompt-log](https://github.com/clawdbot/skills/tree/main/skills/thesash/prompt-log/SKILL.md) - 从AI编码会话日志（Clawdbot、Claude Code、Codex）中提取对话记录。

## Git 与 GitHub

- [conventional-commits](https://github.com/clawdbot/skills/tree/main/skills/bastos/conventional-commits/SKILL.md) - 使用 Conventional Commits 规范格式化提交信息。
- [deepwiki](https://github.com/clawdbot/skills/tree/main/skills/arun-8687/deepwiki/SKILL.md) - 查询 DeepWiki MCP 服务器以获取 GitHub 仓库文档和 wiki 结构。
- [deepwork-tracker](https://github.com/clawdbot/skills/tree/main/skills/adunne09/deepwork-tracker/SKILL.md) - 本地跟踪深度工作会话（开始/停止/状态）
- [deploy-agent](https://github.com/clawdbot/skills/tree/main/skills/sherajdev/deploy-agent/SKILL.md) - 用于全栈应用的多步骤部署代理。
- [github](https://github.com/clawdbot/skills/tree/main/skills/steipete/github/SKILL.md) - 使用 `gh` CLI 与 GitHub 进行交互。
- [github-pr](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/github-pr/SKILL.md) - 在本地获取、预览、合并并测试 GitHub PR。
- [gitload](https://github.com/clawdbot/skills/tree/main/skills/waldekmastykarz/gitload/SKILL.md) - 抱歉，您提供的内容为空，请提供需要翻译的英文描述。
- [pr-commit-workflow](https://github.com/clawdbot/skills/tree/main/skills/joshp123/pr-commit-workflow/SKILL.md) - 该技能应在创建提交或拉取请求时使用。
- [read-github](https://github.com/clawdbot/skills/tree/main/skills/am-will/read-github/SKILL.md) - 抱歉，您提供的内容为空，请提供需要翻译的英文描述。

## DevOps 与云计算

- [Azure CLI](https://github.com/clawdbot/skills/tree/main/skills/ddevaal/azure-cli/SKILL.md) - 通过命令行界面实现全面的 Azure 云平台管理。
- [cloudflare](https://github.com/clawdbot/skills/tree/main/skills/asleep123/wrangler/SKILL.md) - 使用 Wrangler CLI 管理 Cloudflare Workers、KV、D1、R2 及密钥。
- [coolify](https://github.com/clawdbot/skills/tree/main/skills/visiongeist/coolify/SKILL.md) - 通过 Coolify API 管理 Coolify 的部署、应用、数据库和服务。
- [digital-ocean](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/digital-ocean/SKILL.md) - 通过 DO API 管理 Digital Ocean 的 droplets、域名和基础设施。
- [dokploy](https://github.com/clawdbot/skills/tree/main/skills/joshuarileydev/dokploy/SKILL.md) - 通过 Dokploy API 管理 Dokploy 的部署、项目、应用和域名。
- [domain-dns-ops](https://github.com/clawdbot/skills/tree/main/skills/steipete/domain-dns-ops/SKILL.md) - 抱歉，您提供的内容为空，请提供需要翻译的英文描述。
- [domaindetails](https://github.com/clawdbot/skills/tree/main/skills/julianengel/domaindetails/SKILL.md) - 查询域名WHOIS/RDAP信息并检查市场列表。免费API，无需认证。
- [exa-plus](https://github.com/clawdbot/skills/tree/main/skills/jordyvandomselaar/exa-plus/SKILL.md) - 通过 Exa AI 进行神经网络网页搜索。搜索人物、公司、新闻、研究和代码。
- [exe-dev](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/exe-dev/SKILL.md) - 在 exe.dev 上管理持久化虚拟机。创建虚拟机，配置 HTTP 代理，分享访问权限。
- [hetzner](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/hetzner/SKILL.md) - 使用 hcloud CLI 管理 Hetzner Cloud 服务器。
- [hetzner-cloud](https://github.com/clawdbot/skills/tree/main/skills/pasogott/hetzner-cloud/SKILL.md) - Hetzner Cloud CLI 用于管理服务器、存储卷、防火墙、网络、DNS 和快照。
- [Joan Workflow](https://github.com/clawdbot/skills/tree/main/skills/donny-son/joan-workflow/SKILL.md) - 当用户询问“joan”、“pods”、“workspace”、“domain knowledge”时，应使用此技能。
- [komodo](https://github.com/clawdbot/skills/tree/main/skills/weird-aftertaste/komodo/SKILL.md) - 管理 Komodo 基础设施——服务器、Docker 部署、堆栈、构建及相关流程。
- [kubectl-skill](https://github.com/clawdbot/skills/tree/main/skills/ddevaal/kubectl/SKILL.md) - 通过 kubectl 命令执行和管理 Kubernetes 集群。
- [linearis](https://github.com/clawdbot/skills/tree/main/skills/whoisnnamdi/linearis/SKILL.md) - Linear.app 的命令行工具，用于问题跟踪。支持列出、创建和更新操作。
- [npm-proxy](https://github.com/clawdbot/skills/tree/main/skills/weird-aftertaste/npm-proxy/SKILL.md) - 管理 Nginx Proxy Manager (NPM) 的主机、证书和访问列表。
- [portainer](https://github.com/clawdbot/skills/tree/main/skills/asteinberger/portainer/SKILL.md) - 通过 Portainer API 控制 Docker 容器和堆栈。
- [premium-domains](https://github.com/clawdbot/skills/tree/main/skills/julianengel/premium-domains/SKILL.md) - 在 Afternic、Sedo、Atom、Dynadot、Namecheap、NameSilo 平台搜索优质域名出售。
- [private-connect](https://github.com/clawdbot/skills/tree/main/skills/dantelex/private-connect/SKILL.md) - 通过名称从任何地点访问私有服务，无需VPN或SSH隧道。
- [proxmox](https://github.com/clawdbot/skills/tree/main/skills/weird-aftertaste/proxmox/SKILL.md) - 通过 REST API 管理 Proxmox VE 集群。
- [proxmox-full](https://github.com/clawdbot/skills/tree/main/skills/msarheed/proxmox-full/SKILL.md) - 完整的 Proxmox VE 管理功能——创建、克隆、启动和停止虚拟机。
- [Send Me My Files - R2 upload with short lived signed urls](https://github.com/clawdbot/skills/tree/main/skills/julianengel/r2-upload/SKILL.md) - 将文件上传至 Cloudflare R2、AWS S3 或任何兼容 S3 的存储服务。
- [servicenow-agent](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/servicenow-agent/SKILL.md) - 对 ServiceNow 表、附件、聚合的只读 CLI 访问。
- [servicenow-docs](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/servicenow-docs/SKILL.md) - 搜索并检索 ServiceNow 文档及发行说明。
- [supabase](https://github.com/clawdbot/skills/tree/main/skills/stopmoclay/supabase/SKILL.md) - 连接到 Supabase 进行数据库操作、向量搜索和存储。
- [sysadmin-toolbox](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/sysadmin-toolbox/SKILL.md) - 面向系统管理员、DevOps 和安全任务的工具发现及 Shell 一行命令参考。
- [tailscale](https://github.com/clawdbot/skills/tree/main/skills/jmagar/tailscale/SKILL.md) - 通过 CLI 和 API 管理 Tailscale tailnet。
- [tailscale-serve](https://github.com/clawdbot/skills/tree/main/skills/snopoke/tailscale-serve/SKILL.md) - tailscale-serve
- [tavily](https://github.com/clawdbot/skills/tree/main/skills/bert-builder/tavily/SKILL.md) - 使用 Tavily Search API 的 AI 优化网页搜索。
- [unraid](https://github.com/clawdbot/skills/tree/main/skills/jmagar/unraid/SKILL.md) - 通过 GraphQL API 查询和监控 Unraid 服务器。
- [uptime-kuma](https://github.com/clawdbot/skills/tree/main/skills/msarheed/uptime-kuma/SKILL.md) - 与 Uptime Kuma 监控服务器交互。
- [vercel](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/vercel/SKILL.md) - 通过完整的 CLI 参考部署应用程序和管理项目。
- [vercel-deploy](https://github.com/clawdbot/skills/tree/main/skills/sharanga10/vercel-deploy-claimable/SKILL.md) - 将应用程序和网站部署到 Vercel。
- [pi-admin](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/pi-admin/SKILL.md) - Raspberry Pi 系统管理。监控资源，管理服务，执行更新。

## 浏览器与自动化

- [Agent Browser](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/agent-browser/SKILL.md) - 一个基于 Rust 的高速无头浏览器自动化 CLI，带有 Node.js 回退功能，支持 AI 代理操作。
- [browsh](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/browsh/SKILL.md) - 一款现代文本浏览器。使用无头 Firefox 在终端中渲染网页。
- [browser-use](https://github.com/clawdbot/skills/tree/main/skills/shawnpana/browser-use/SKILL.md) - 基于云的浏览器自动化，支持托管会话和自主任务执行。
- [context7](https://github.com/clawdbot/skills/tree/main/skills/am-will/context7-api/SKILL.md) - 抱歉，您提供的内容不完整，请提供完整的英文描述以便翻译。
- [guru-mcp](https://github.com/clawdbot/skills/tree/main/skills/pvoo/guru-mcp/SKILL.md) - 通过 MCP 访问 Guru 知识库——提问 AI、搜索文档、创建草稿。
- [mcporter](https://github.com/clawdbot/skills/tree/main/skills/steipete/mcporter/SKILL.md) - 使用 mcporter CLI 直接列出、配置、认证并调用 MCP 服务器/工具（HTTP）。
- [verify-on-browser](https://github.com/clawdbot/skills/tree/main/skills/myestery/verify-on-browser/SKILL.md) - 通过 Chrome DevTools Protocol 控制浏览器 - 完整的 CDP 访问权限。

## 图像与视频生成

- [clinkding](https://github.com/clawdbot/skills/tree/main/skills/daveonkels/clinkding/SKILL.md) - 管理 linkding 书签 - 保存网址、搜索、标签、整理。
- [coloring-page](https://github.com/clawdbot/skills/tree/main/skills/borahm/coloring-page/SKILL.md) - 将上传的照片转换为可打印的黑白填色页。
- [comfy-cli](https://github.com/clawdbot/skills/tree/main/skills/johntheyoung/comfy-cli/SKILL.md) - 安装、管理并运行 ComfyUI 实例。
- [Excalidraw Flowchart](https://github.com/clawdbot/skills/tree/main/skills/swiftlysingh/excalidraw-flowchart/SKILL.md) - 根据描述创建 Excalidraw 流程图。
- [gamma](https://github.com/clawdbot/skills/tree/main/skills/stopmoclay/gamma/SKILL.md) - 使用 Gamma.app API 生成由 AI 驱动的演示文稿、文档和社交媒体帖子。
- [krea-api](https://github.com/clawdbot/skills/tree/main/skills/fossilizedcarlos/krea-api/SKILL.md) - 通过 Krea.ai API 生成图像（支持 Flux、Imagen、Ideogram、Seedream 等）。
- [meshy-ai](https://github.com/clawdbot/skills/tree/main/skills/sabatesduran/clawdbot-meshyai-skill/SKILL.md) - 使用 Meshy.ai REST API 生成资产：（1）文本转二维图像（Meshy Text to Image）
- [veo](https://github.com/clawdbot/skills/tree/main/skills/buddyh/veo/SKILL.md) - 使用 Google Veo（Veo 3.1 / Veo 3.0）生成视频。
- [video-frames](https://github.com/clawdbot/skills/tree/main/skills/steipete/video-frames/SKILL.md) - 使用 ffmpeg 从视频中提取帧或短片段。

## 苹果应用与服务

- [apple-contacts](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/apple-contacts/SKILL.md) - 从 macOS Contacts.app 中查找联系人。
- [apple-music](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/apple-music/SKILL.md) - 搜索 Apple Music，添加歌曲到库，管理播放列表，控制播放和 AirPlay。
- [apple-photos](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/apple-photos/SKILL.md) - 适用于 macOS 的 Apple Photos.app 集成。支持列出相册、浏览照片、按日期/人物/内容搜索。
- [get-focus-mode](https://github.com/clawdbot/skills/tree/main/skills/nickchristensen/get-focus-mode/SKILL.md) - 获取当前 macOS 的 Focus 模式。
- [healthkit-sync](https://github.com/clawdbot/skills/tree/main/skills/mneves75/healthkit-sync/SKILL.md) - iOS HealthKit 数据同步 CLI 命令及使用模式。
- [homebrew](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/homebrew/SKILL.md) - macOS 的 Homebrew 包管理器。用于搜索、安装、管理及排查软件包和 cask。
- [icloud-findmy](https://github.com/clawdbot/skills/tree/main/skills/liamnichols/icloud-findmy/SKILL.md) - 通过 iCloud 查询家庭设备的定位和电池状态。
- [media-backup](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/media-backup/SKILL.md) - 将 Clawdbot 对话中的媒体文件（照片、视频）归档到本地文件夹。
- [mole-mac-cleanup](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/mole-mac-cleanup/SKILL.md) - Mac 清理与优化工具，集成 CleanMyMac、AppCleaner 和 DaisyDisk 功能。
- [shortcuts-generator](https://github.com/clawdbot/skills/tree/main/skills/erik-agens/shortcuts-skill/SKILL.md) - 通过创建 plist 文件生成 macOS/iOS Shortcuts。



## 搜索与研究

- [brave-search](https://github.com/clawdbot/skills/tree/main/skills/steipete/brave-search/SKILL.md) - 通过 Brave Search API 进行网页搜索和内容提取。
- [brightdata](https://github.com/clawdbot/skills/tree/main/skills/meirkad/bright-data/SKILL.md) - 通过 Bright Data API 进行网页抓取和搜索。
- [clawdbot-logs](https://github.com/clawdbot/skills/tree/main/skills/satriapamudji/clawdbot-logs/SKILL.md) - 分析 Clawdbot 日志和诊断信息。用于用户询问机器人性能时。
- [exa](https://github.com/clawdbot/skills/tree/main/skills/fardeenxyz/exa/SKILL.md) - 通过 Exa AI API 实现神经网络网页搜索和代码上下文功能。需要 EXA_API_KEY。
- [kagi-search](https://github.com/clawdbot/skills/tree/main/skills/silversteez/kagi-search/SKILL.md) - 使用 Kagi Search API 进行网页搜索。适用于需要进行网页搜索时。
- [literature-review](https://github.com/clawdbot/skills/tree/main/skills/weird-aftertaste/literature-review/SKILL.md) - 协助撰写文献综述，通过搜索学术资源。
- [parallel](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/parallel/SKILL.md) - 通过 Parallel.ai API 实现高精度网页搜索与研究。
- [seo-audit](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/seo-audit/SKILL.md) - 当用户需要审计、审核或诊断其网站的SEO问题时。
- [spots](https://github.com/clawdbot/skills/tree/main/skills/foeken/spots/SKILL.md) - 基于网格扫描的全面 Google Places 搜索。
- [tavily](https://github.com/clawdbot/skills/tree/main/skills/arun-8687/tavily-search/SKILL.md) - 通过 Tavily API 实现的 AI 优化网页搜索。为 AI 代理返回简洁且相关的结果。
- [tweet-writer](https://github.com/clawdbot/skills/tree/main/skills/sanky369/tweet-writer/SKILL.md) - 撰写具有病毒传播力、说服力和吸引力的推文及推文线程。
- [web-search-plus](https://github.com/clawdbot/skills/tree/main/skills/robbyczgw-cla/web-search-plus/SKILL.md) - 具备智能自动路由的统一搜索技能。

## Clawdbot 工具

- [agent-browser](https://github.com/clawdbot/skills/tree/main/skills/matrixy/agent-browser-clawdbot/SKILL.md) - 针对AI代理优化的无头浏览器自动化CLI，支持无障碍树快照。
- [auto-updater](https://github.com/clawdbot/skills/tree/main/skills/maximeprades/auto-updater/SKILL.md) - 每天自动更新 Clawdbot 及所有已安装的技能。
- [claude-code-usage](https://github.com/clawdbot/skills/tree/main/skills/azaidi94/claude-code-usage/SKILL.md) - 检查 Claude Code OAuth 使用限制（会话和每周配额）。
- [claude-connect](https://github.com/clawdbot/skills/tree/main/skills/tunaissacoding/claude-connect/SKILL.md) - 即时将 Claude 连接到 Clawdbot，并保持全天候24/7在线。
- [clawd-modifier](https://github.com/clawdbot/skills/tree/main/skills/masonc15/clawd-modifier/SKILL.md) - 修改 Clawd，Claude Code 的吉祥物。当用户想要自定义 Clawd 时使用此技能。
- [clawdbot-documentation-expert](https://github.com/clawdbot/skills/tree/main/skills/janhcla/clawdbot-documentation-expert/SKILL.md) - clawdbot 文档专家
- [clawdbot-skill-update](https://github.com/clawdbot/skills/tree/main/skills/pasogott/clawdbot-skill-update/SKILL.md) - 支持动态工作区检测的全面备份、更新与恢复工作流程。
- [clawdbot-workspace-template-review](https://github.com/clawdbot/skills/tree/main/skills/xadenryan/clawdbot-skill-clawdbot-workspace-template-review/SKILL.md) - 将 Clawdbot 工作区与 Clawdbot 官方安装的模板（npm）进行比较。
- [clawddocs](https://github.com/clawdbot/skills/tree/main/skills/nicholasspisak/clawddocs/SKILL.md) - Clawdbot 文档专家，具备决策树导航、脚本搜索和文档获取功能。
- [clawdhub](https://github.com/clawdbot/skills/tree/main/skills/steipete/clawdhub/SKILL.md) - 使用 ClawdHub CLI 从 clawdhub.com 搜索、安装、更新和发布 agent 技能。
- [clawdlink](https://github.com/clawdbot/skills/tree/main/skills/davemorin/clawdlink/SKILL.md) - 加密的 Clawdbot 之间消息传递。
- [skills-audit](https://github.com/clawdbot/skills/tree/main/skills/morozred/skill-audit/SKILL.md) - 本地审计已安装的 agent 技能，检查安全和策略问题。
- [skills-search](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/skills-search/SKILL.md) - 通过 CLI 搜索 skills.sh 注册表。从 skills.sh 生态系统中查找并发现 agent 技能。

## 命令行工具

- [bible](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/bible-votd/SKILL.md) - 获取带有可分享图片的 Bible.com 每日金句。
- [camsnap](https://github.com/clawdbot/skills/tree/main/skills/steipete/camsnap/SKILL.md) - 从 RTSP/ONVIF 摄像头捕获帧或视频片段。
- [canvas-lms](https://github.com/clawdbot/skills/tree/main/skills/pranavkarthik10/canvas-lms/SKILL.md) - 访问 Canvas LMS（Instructure）以获取课程数据、作业、成绩和提交内容。
- [Cat Fact](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/catfact/SKILL.md) - 来自 catfact.ninja 的随机猫咪趣闻和品种信息（免费，无需 API 密钥）。
- [content-advisory](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/content-advisory/SKILL.md) - 查询电影和电视剧的详细内容分级（性/裸露、暴力/血腥）。
- [create-cli](https://github.com/clawdbot/skills/tree/main/skills/steipete/create-cli/SKILL.md) - 抱歉，您提供的内容为空，请提供需要翻译的英文描述。
- [data-reconciliation-exceptions](https://github.com/clawdbot/skills/tree/main/skills/kowl64/data-reconciliation-exceptions/SKILL.md) - 使用稳定标识符（工资编号、驾驶证、驾驶员卡）对数据源进行对账。
- [dilbert](https://github.com/clawdbot/skills/tree/main/skills/hjanuschka/dilbert/SKILL.md) - Dilbert 是一部由Scott Adams创作的美国漫画，主要讽刺职场文化和办公室生活。
- [dropbox](https://github.com/clawdbot/skills/tree/main/skills/ryanlisse/dropbox/SKILL.md) - Dropbox（云存储服务）
- [duckdb-en](https://github.com/clawdbot/skills/tree/main/skills/camelsprout/duckdb-cli-ai-skills/SKILL.md) - DuckDB CLI 专家，擅长 SQL 分析、数据处理及文件转换。
- [entr](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/entr/SKILL.md) - 在文件变更时运行任意命令。适用于监视文件并触发构建或测试。
- [gifgrep](https://github.com/clawdbot/skills/tree/main/skills/steipete/gifgrep/SKILL.md) - 通过 CLI/TUI 搜索 GIF 提供商，下载结果，并提取静态图像或图像合辑。
- [goplaces](https://github.com/clawdbot/skills/tree/main/skills/steipete/goplaces/SKILL.md) - 通过 goplaces CLI 使用 Google Places API (New) 进行文本搜索、地点详情查询和解析。
- [journal-to-post](https://github.com/clawdbot/skills/tree/main/skills/itsflow/journal-to-post/SKILL.md) - 将个人日记条目转换为可分享的社交媒体帖子。
- [jq](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/jq/SKILL.md) - 命令行 JSON 处理器。用于提取、过滤和转换 JSON。
- [local-places](https://github.com/clawdbot/skills/tree/main/skills/steipete/local-places/SKILL.md) - 通过本地主机上的 Google Places API 代理搜索地点（餐厅、咖啡馆等）。
- [native-app-performance](https://github.com/clawdbot/skills/tree/main/skills/steipete/native-app-performance/SKILL.md) - 通过 xctrace/Time Profiler 进行原生 macOS/iOS 应用性能分析。
- [office-quotes](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/office-quotes/SKILL.md) - 生成《The Office (US)》中的随机名言。
- [parcel-package-tracking](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/parcel-package-tracking/SKILL.md) - 通过 Parcel API 跟踪并添加配送信息。
- [peekaboo](https://github.com/clawdbot/skills/tree/main/skills/steipete/peekaboo/SKILL.md) - 使用 Peekaboo CLI 捕捉并自动化 macOS 界面操作。
- [portable-tools](https://github.com/clawdbot/skills/tree/main/skills/tunaissacoding/portable-tools/SKILL.md) - 构建跨设备工具，无需硬编码路径或账户名称。
- [post-at](https://github.com/clawdbot/skills/tree/main/skills/krausefx/post-at/SKILL.md) - 管理奥地利邮政（post.at）配送——列出包裹，检查配送状态。
- [process-watch](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/process-watch/SKILL.md) - 监控系统进程——CPU、内存、磁盘I/O、网络、打开的文件、端口。
- [sag](https://github.com/clawdbot/skills/tree/main/skills/steipete/sag/SKILL.md) - ElevenLabs 文本转语音，具备 mac 风格的 say 用户体验。
- [shorten](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/shorten/SKILL.md) - 使用 is.gd 缩短 URL（无需认证）。返回永久短链接。
- [simple-backup](https://github.com/clawdbot/skills/tree/main/skills/vacinc/simple-backup/SKILL.md) - 将代理大脑（workspace）和身体（state）备份到本地文件夹。
- [smalltalk](https://github.com/clawdbot/skills/tree/main/skills/johnmci/smalltalk/SKILL.md) - 与实时 Smalltalk 镜像（Cuis 或 Squeak）交互。
- [songsee](https://github.com/clawdbot/skills/tree/main/skills/steipete/songsee/SKILL.md) - 使用 songsee CLI 从音频生成频谱图和特征面板可视化。
- [steam](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/steam/SKILL.md) - 浏览、筛选并发现Steam库中的游戏。
- [sudoku](https://github.com/clawdbot/skills/tree/main/skills/odrobnik/sudoku/SKILL.md) - 获取 Sudoku 谜题并以 JSON 格式存储在工作区；按需渲染图像；显示谜题答案。
- [tldr](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/tldr/SKILL.md) - 简化版的 tldr-pages 手册页。用于快速了解 CLI 工具。
- [tmdb](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/tmdb/SKILL.md) - 通过 TMDb API 搜索电影/电视剧，获取演员阵容、评分、流媒体信息及个性化推荐。
- [tmux](https://github.com/clawdbot/skills/tree/main/skills/steipete/tmux/SKILL.md) - 通过发送按键和抓取面板输出，实现对交互式CLI的tmux会话远程控制。
- [track17](https://github.com/clawdbot/skills/tree/main/skills/tristanmanchester/track17/SKILL.md) - 通过17TRACK API跟踪包裹（本地SQLite数据库，轮询+可选Webhook接收）。
- [units](https://github.com/clawdbot/skills/tree/main/skills/asleep123/units/SKILL.md) - 使用 GNU Units 进行单位转换和计算。
- [voicenotes](https://github.com/clawdbot/skills/tree/main/skills/shawnhansen/voicenotes/SKILL.md) - 同步并访问来自 Voicenotes.com 的语音笔记。
- [xkcd](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/xkcd/SKILL.md) - 获取 xkcd 漫画——最新、随机、按编号或关键词搜索。

## iOS 与 macOS 开发

- [apple-docs](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/apple-docs/SKILL.md) - 查询 Apple 开发者文档、API 及 2014-2025 年的 WWDC 视频。
- [apple-docs-mcp](https://github.com/clawdbot/skills/tree/main/skills/janhcla/apple-docs-mcp/SKILL.md) - apple-docs-mcp
- [instruments-profiling](https://github.com/clawdbot/skills/tree/main/skills/steipete/instruments-profiling/SKILL.md) - 用于使用 Instruments/xctrace 对原生 macOS 或 iOS 应用进行性能分析时。
- [ios-simulator](https://github.com/clawdbot/skills/tree/main/skills/tristanmanchester/ios-simulator/SKILL.md) - 自动化 iOS Simulator 工作流程（simctl + idb）：创建/启动/擦除设备，安装/启动应用。
- [macos-spm-app-packaging](https://github.com/clawdbot/skills/tree/main/skills/dimillian/macos-spm-app-packaging/SKILL.md) - 无需 Xcode 项目即可搭建、构建和打包基于 SwiftPM 的 macOS 应用。
- [PagerKit](https://github.com/clawdbot/skills/tree/main/skills/szpakkamil/pagerkit/SKILL.md) - PagerKit 专家指导，SwiftUI 库，用于高级且可定制的基于页面的导航。
- [sfsymbol-generator](https://github.com/clawdbot/skills/tree/main/skills/svkozak/sfsymbol-generator/SKILL.md) - 从 SVG 生成 Xcode SF Symbol 资产目录 .symbolset。
- [swift-concurrency-expert](https://github.com/clawdbot/skills/tree/main/skills/steipete/swift-concurrency-expert/SKILL.md) - Swift Concurrency 审查与修正，适用于 Swift 6.2 及以上版本。
- [swiftui-empty-app-init](https://github.com/clawdbot/skills/tree/main/skills/ignaciocervino/swiftui-empty-app-init/SKILL.md) - 在当前目录初始化一个最简SwiftUI iOS应用，生成一个单一的 `.xcodeproj` 文件。
- [swiftui-liquid-glass](https://github.com/clawdbot/skills/tree/main/skills/steipete/swiftui-liquid-glass/SKILL.md) - 使用 iOS 26 及以上版本的 Liquid Glass API 实现、审查或改进 SwiftUI 功能。
- [swiftui-performance-audit](https://github.com/clawdbot/skills/tree/main/skills/steipete/swiftui-performance-audit/SKILL.md) - 通过代码审查和架构优化，审计并提升 SwiftUI 运行时性能。
- [swiftui-ui-patterns](https://github.com/clawdbot/skills/tree/main/skills/dimillian/swiftui-ui-patterns/SKILL.md) - 构建 SwiftUI 视图和组件的最佳实践及示例指导。
- [swiftui-view-refactor](https://github.com/clawdbot/skills/tree/main/skills/steipete/swiftui-view-refactor/SKILL.md) - 重构并审查 SwiftUI 视图文件，确保结构一致，采用依赖注入。


## 市场与销售

- [ab-test-setup](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/ab-test-setup/SKILL.md) - 当用户需要规划、设计或实施A/B测试或实验时。
- [apollo](https://github.com/clawdbot/skills/tree/main/skills/jhumanj/apollo/SKILL.md) - 与 Apollo.io REST API 交互（人员/组织信息丰富、搜索、列表管理）。
- [basecamp-cli](https://github.com/clawdbot/skills/tree/main/skills/emredoganer/basecamp-cli/SKILL.md) - 管理 Basecamp 项目、待办事项和消息（通过 bc3 API / 37signals Launchpad）。
- [bearblog](https://github.com/clawdbot/skills/tree/main/skills/azade-c/bearblog/SKILL.md) - 在 Bear Blog (bearblog.dev) 上创建和管理博客文章。
- [bird](https://github.com/clawdbot/skills/tree/main/skills/steipete/bird/SKILL.md) - X/Twitter CLI，用于通过 cookies 或 Sweetistics 进行阅读、搜索和发布。
- [bluesky](https://github.com/clawdbot/skills/tree/main/skills/jeffaf/bluesky/SKILL.md) - 通过 CLI 阅读、发布并与 Bluesky（AT Protocol）互动。
- [competitor-alternatives](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/competitor-alternatives/SKILL.md) - 当用户希望创建竞争对手比较页或替代方案页以进行SEO优化时。
- [copy-editing](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/copy-editing/SKILL.md) - 当用户想要编辑、审查或改进现有的营销文案时。
- [copywriting](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/copywriting/SKILL.md) - 当用户想要撰写、重写或改进营销文案时。
- [email-sequence](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/email-sequence/SKILL.md) - 当用户想要创建或优化电子邮件序列、滴灌活动或自动化邮件流程时。
- [form-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/form-cro/SKILL.md) - 当用户想要优化除注册/报名以外的任何表单——包括潜在客户收集表单。
- [free-tool-strategy](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/free-tool-strategy/SKILL.md) - 当用户想要规划、评估或构建一个免费工具时。
- [ga4](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/ga4/SKILL.md) - 通过 Analytics Data API 查询 Google Analytics 4 (GA4) 数据。
- [gong](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/gong/SKILL.md) - Gong API 用于搜索通话、转录内容和会话智能。
- [google-ads](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/google-ads/SKILL.md) - 查询、审计并优化 Google Ads 活动。
- [gsc](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/gsc/SKILL.md) - 查询 Google Search Console 获取 SEO 数据——搜索查询、热门页面、点击率提升机会。
- [hubspot](https://github.com/clawdbot/skills/tree/main/skills/kwall1/hubspot/SKILL.md) - HubSpot CRM 和 CMS API 集成，支持联系人、公司、交易、负责人及内容管理。
- [humanizer](https://github.com/clawdbot/skills/tree/main/skills/biostartechnology/humanizer/SKILL.md) - 抱歉，您提供的内容为空或不完整，请提供需要翻译的英文描述。
- [marketing-mode](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/marketing-mode/SKILL.md) - Marketing Mode整合了涵盖策略、心理学和内容的23项全面营销技能。
- [marketing-psychology](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/marketing-psychology/SKILL.md) - 当用户希望应用心理学原理和思维模型时。
- [marketing-skills](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/SKILL.md) - 简要说明：23个营销实战手册（涵盖CRO、SEO、文案、分析、实验、定价、产品发布、广告）。
- [otter](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/otter/SKILL.md) - Otter.ai 转录 CLI - 列出、搜索、下载并同步会议转录内容到 CRM。
- [paywall-upgrade-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/paywall-upgrade-cro/SKILL.md) - 当用户想要创建或优化应用内付费墙、升级界面、追加销售弹窗时。
- [pinch-to-post](https://github.com/clawdbot/skills/tree/main/skills/nickhamze/pinch-to-post/SKILL.md) - Clawdbot 的 WordPress 自动化。管理文章、页面、WooCommerce 产品、订单和库存。
- [popup-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/popup-cro/SKILL.md) - 当用户想要创建或优化弹出窗口、模态框、覆盖层、滑入窗口时。
- [pricing-strategy](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/pricing-strategy/SKILL.md) - 当用户需要有关定价决策、包装或货币化策略的帮助时。
- [programmatic-seo](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/programmatic-seo/SKILL.md) - 当用户希望通过模板和数据大规模创建以SEO为驱动的页面时。
- [reddit](https://github.com/clawdbot/skills/tree/main/skills/theglove44/reddit/SKILL.md) - 浏览、搜索、发布和管理 Reddit。
- [reddit-search](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/reddit-search/SKILL.md) - 在 Reddit 上搜索子版块并获取相关信息。
- [referral-program](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/referral-program/SKILL.md) - 当用户想要创建、优化或分析推荐计划或联盟计划时。
- [schema-markup](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/schema-markup/SKILL.md) - 当用户希望在其网站上添加、修复或优化 schema 标记和结构化数据时。
- [signup-flow-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/signup-flow-cro/SKILL.md) - 当用户希望优化注册、开户、账号创建或试用激活流程时。
- [solobuddy](https://github.com/clawdbot/skills/tree/main/skills/humanji7/solobuddy/SKILL.md) - 面向独立开发者的公开构建助手——内容工作流程与Twitter互动管理。
- [twenty-crm](https://github.com/clawdbot/skills/tree/main/skills/jhumanj/twenty-crm/SKILL.md) - 通过 REST/GraphQL 与 Twenty CRM（自托管版）进行交互。
- [typefully](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/typefully/SKILL.md) - 抱歉，您提供的内容不完整，请提供完整的英文描述以便翻译。
- [x-article-editor](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/x-article-editor/SKILL.md) - 简要说明：将主题或草稿转化为高互动性的X文章。第一步：最终复制粘贴文章内容。

## 生产力与任务

- [clawd-docs-v2](https://github.com/clawdbot/skills/tree/main/skills/aranej/clawd-docs-v2/SKILL.md) - Smart ClawdBot 文档访问，支持本地搜索索引、缓存片段及按需获取。
- [clickup-mcp](https://github.com/clawdbot/skills/tree/main/skills/pvoo/clickup-mcp/SKILL.md) - 通过官方 MCP 管理 ClickUp 的任务、文档、时间跟踪、评论、聊天和搜索。
- [dex](https://github.com/clawdbot/skills/tree/main/skills/gricha/dex/SKILL.md) - 用于异步/多步骤工作的任务跟踪。
- [dexcom](https://github.com/clawdbot/skills/tree/main/skills/chris-clem/dexcom/SKILL.md) - 通过 Dexcom G7/G6 CGM 监测血糖。
- [dexter](https://github.com/clawdbot/skills/tree/main/skills/igorhvr/dexter/SKILL.md) - 用于股票分析、财务报表、指标和价格的自主金融研究代理。
- [dvsa-tc-audit-readiness-operator-licence-uk](https://github.com/clawdbot/skills/tree/main/skills/kowl64/dvsa-tc-audit-readiness-operator-licence-uk/SKILL.md) - 构建DVSA/交通专员“展示我”审计准备清单和证据索引。
- [gno](https://github.com/clawdbot/skills/tree/main/skills/gmickel/gno/SKILL.md) - 搜索本地文档、文件、笔记和知识库。
- [jira](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/jira/SKILL.md) - 通过 jira-cli 管理 Jira 任务、看板、冲刺和项目。
- [linear](https://github.com/clawdbot/skills/tree/main/skills/manuelhettich/linear/SKILL.md) - 查询和管理 Linear 的问题、项目及团队工作流程。
- [morning-manifesto](https://github.com/clawdbot/skills/tree/main/skills/marcbickel/morning-manifesto/SKILL.md) - 每日晨间反思工作流程，任务同步至 Obsidian、Apple Reminders 和 Linear。
- [plan-my-day](https://github.com/clawdbot/skills/tree/main/skills/itsflow/plan-my-day/SKILL.md) - 生成一个能量优化的时间分块日计划。
- [prd](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/prd/SKILL.md) - 创建和管理产品需求文档（PRDs）。
- [prowlarr](https://github.com/clawdbot/skills/tree/main/skills/jmagar/prowlarr/SKILL.md) - 搜索索引器并管理 Prowlarr。用于用户请求“搜索”时。
- [qmd](https://github.com/clawdbot/skills/tree/main/skills/steipete/qmd/SKILL.md) - 本地搜索/索引 CLI（BM25 + 向量 + 重排序），支持 MCP 模式。
- [samsung-smart-tv](https://github.com/clawdbot/skills/tree/main/skills/regenrek/samsung-smartthings/SKILL.md) - 通过 SmartThings（OAuth 应用 + 设备控制）控制三星电视。
- [task](https://github.com/clawdbot/skills/tree/main/skills/amirbrooks/task/SKILL.md) - 通过 tool-dispatch 进行 Tasker docstore 任务管理。
- [task-tracker](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/task-tracker/SKILL.md) - 个人任务管理，包含每日站会和每周回顾。
- [things-mac](https://github.com/clawdbot/skills/tree/main/skills/steipete/things-mac/SKILL.md) - 通过 macOS 上的 `things` CLI 管理 Things 3（添加/更新项目和待办事项）。
- [ticktick](https://github.com/clawdbot/skills/tree/main/skills/manuelhettich/ticktick/SKILL.md) - 通过命令行使用OAuth2认证管理TickTick任务和项目，支持批量操作。
- [timesheet](https://github.com/clawdbot/skills/tree/main/skills/florianrauscha/timesheet/SKILL.md) - 使用 timesheet.io CLI 跟踪时间，管理项目和任务。
- [todo-tracker](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/todo-tracker/SKILL.md) - 持久化的TODO便签，用于跨会话跟踪任务。
- [todoist](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/todoist/SKILL.md) - 管理 Todoist 中的任务和项目。适用于用户询问任务、待办事项和提醒时。
- [topydo](https://github.com/clawdbot/skills/tree/main/skills/bastos/topydo/SKILL.md) - 使用 topydo CLI 管理 todo.txt 任务。支持添加、列出、完成、优先级设置和标签管理。
- [trello](https://github.com/clawdbot/skills/tree/main/skills/steipete/trello/SKILL.md) - 通过 Trello REST API 管理 Trello 看板、列表和卡片。
- [vikunja](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/vikunja/SKILL.md) - 在 Vikunja 中管理项目和任务，Vikunja 是一款开源的项目管理工具。
- [vikunja-fast](https://github.com/clawdbot/skills/tree/main/skills/tmigone/vikunja-fast/SKILL.md) - 管理 Vikunja 项目和任务（逾期/到期/今日），标记为完成。
- [web-perf](https://github.com/clawdbot/skills/tree/main/skills/elithrar/web-perf/SKILL.md) - 使用 Chrome DevTools MCP 分析网页性能。
- [withings-health](https://github.com/clawdbot/skills/tree/main/skills/hisxo/withings-health/SKILL.md) - 从Withings API获取健康数据，包括体重、身体成分（脂肪、肌肉、骨骼）。

## 人工智能与大型语言模型 (AI & LLMs)

- [antigravity-quota](https://github.com/clawdbot/skills/tree/main/skills/mukhtharcm/antigravity-quota/SKILL.md) - 检查 Claude 和 Gemini 模型的 Antigravity 账户配额。
- [ask-questions-if-underspecified](https://github.com/clawdbot/skills/tree/main/skills/lc0rp/ask-questions-if-underspecified/SKILL.md) - 在实施前明确需求。仅在明确调用时使用，避免自动执行。
- [claude-oauth-refresher](https://github.com/clawdbot/skills/tree/main/skills/tunaissacoding/claude-oauth-refresher/SKILL.md) - 保持您的 Claude 访问令牌全天候最新。
- [council](https://github.com/clawdbot/skills/tree/main/skills/emasoudy/council/SKILL.md) - 使用 Memory Bridge 进行 Council Chamber 编排。
- [de-ai-ify](https://github.com/clawdbot/skills/tree/main/skills/itsflow/de-ai-ify/SKILL.md) - 去除AI生成的术语，使文本更具人性化表达。
- [gemini](https://github.com/clawdbot/skills/tree/main/skills/steipete/gemini/SKILL.md) - Gemini CLI 用于一次性问答、摘要和生成。
- [gemini-computer-use](https://github.com/clawdbot/skills/tree/main/skills/am-will/gemini-computer-use/SKILL.md) - 构建并运行 Gemini 2.5 计算机，使用 Playwright 进行浏览器控制代理。
- [gemini-deep-research](https://github.com/clawdbot/skills/tree/main/skills/arun-8687/gemini-deep-research/SKILL.md) - 使用 Gemini Deep Research Agent 执行复杂的长时间研究任务。
- [gemini-stt](https://github.com/clawdbot/skills/tree/main/skills/araa47/gemini-stt/SKILL.md) - 使用 Google 的 Gemini API 或 Vertex AI 转录音频文件。
- [llm-council](https://github.com/clawdbot/skills/tree/main/skills/am-will/llm-council/SKILL.md) - 抱歉，您提供的内容为空，请提供需要翻译的英文描述。
- [lmstudio-subagents](https://github.com/clawdbot/skills/tree/main/skills/t-sinclair2500/lm-studio-subagents/SKILL.md) - 为代理配备在 LM Studio 中搜索并卸载任务到本地模型的能力。
- [minimax-usage](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/minimax-usage/SKILL.md) - 监控 Minimax Coding Plan 使用情况，确保不超出 API 限额。
- [model-router](https://github.com/clawdbot/skills/tree/main/skills/digitaladaption/model-router/SKILL.md) - 一个全面的AI模型路由系统，能够自动为任何任务选择最优模型。
- [nano-banana-pro](https://github.com/clawdbot/skills/tree/main/skills/steipete/nano-banana-pro/SKILL.md) - 使用 Nano Banana Pro（Gemini 3 Pro Image）生成/编辑图像。
- [openai-docs-skill](https://github.com/clawdbot/skills/tree/main/skills/am-will/openai-docs/SKILL.md) - 通过 CLI（curl/jq）使用 OpenAI Docs MCP 服务器查询 OpenAI 开发者文档。
- [openai-image-gen](https://github.com/clawdbot/skills/tree/main/skills/steipete/openai-image-gen/SKILL.md) - 通过 OpenAI Images API 批量生成图像。包含随机提示采样器和 `index.html` 图库。
- [openai-tts](https://github.com/clawdbot/skills/tree/main/skills/pors/openai-tts/SKILL.md) - 通过 OpenAI Audio Speech API 实现文本转语音。
- [openrouter-transcribe](https://github.com/clawdbot/skills/tree/main/skills/obviyus/openrouter-transcribe/SKILL.md) - 通过 OpenRouter 使用支持音频的模型（如 Gemini、GPT-4o-audio 等）转录音频文件。
- [oracle](https://github.com/clawdbot/skills/tree/main/skills/steipete/oracle/SKILL.md) - 使用 @steipete/oracle CLI 打包提示及相关文件。
- [perplexity](https://github.com/clawdbot/skills/tree/main/skills/zats/perplexity/SKILL.md) - 通过 Perplexity API 使用 AI 驱动的答案进行网络搜索。
- [personas](https://github.com/clawdbot/skills/tree/main/skills/robbyczgw-cla/personas/SKILL.md) - 按需转换为31种专业AI角色。
- [pi-orchestration](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/pi-orchestration/SKILL.md) - 使用 Pi Coding Agent 将多个 AI 模型（如 GLM、MiniMax 等）编排为工作节点。
- [recipe-to-list](https://github.com/clawdbot/skills/tree/main/skills/borahm/recipe-to-list/SKILL.md) - 将食谱转换为 Todoist 购物清单。
- [research](https://github.com/clawdbot/skills/tree/main/skills/pors/research/SKILL.md) - 通过 Gemini CLI 进行深度研究——在后台子代理中运行，避免消耗你的 Claude 代币。
- [screen-monitor](https://github.com/clawdbot/skills/tree/main/skills/emasoudy/screen-monitor/SKILL.md) - 双模式屏幕共享与分析。支持多模型（Gemini/Claude/Qwen3-VL）。
- [search-x](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/search-x/SKILL.md) - 使用 Grok 实时搜索 X/Twitter。查找带有引用的推文、趋势和讨论。
- [self-improvement](https://github.com/clawdbot/skills/tree/main/skills/pskoett/self-improving-agent/SKILL.md) - 捕捉学习内容、错误及修正，以实现持续改进。
- [smart-followups](https://github.com/clawdbot/skills/tree/main/skills/robbyczgw-cla/smart-followups/SKILL.md) - 在AI回复后生成上下文相关的后续建议。
- [xai](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/xai/SKILL.md) - 通过 xAI API 与 Grok 模型进行对话。支持 Grok-3、Grok-3-mini、vision 等多种模型。
- [manus](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/manus/SKILL.md) - 通过 Manus API 创建和管理 AI 代理任务。

## 金融与加密货币

- [analytics-tracking](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/analytics-tracking/SKILL.md) - 当用户希望设置、改进或审核分析跟踪与测量时。
- [api-credentials-hygiene](https://github.com/clawdbot/skills/tree/main/skills/kowl64/api-credentials-hygiene/SKILL.md) - 审计并强化API凭证管理（环境变量、隔离、轮换计划、最小权限）。
- [app-store-changelog](https://github.com/clawdbot/skills/tree/main/skills/dimillian/app-store-changelog/SKILL.md) - 通过收集信息创建面向用户的App Store发布说明。
- [blockchain_attestation](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/blockchain-attestation/SKILL.md) - 使用 Ethereum Attestation Service (EAS) 创建可验证的代理工作证明。
- [clawdbot-release-check](https://github.com/clawdbot/skills/tree/main/skills/pors/clawdbot-release-check/SKILL.md) - 检查新的 Clawdbot 版本发布，并在每个新版本发布时发送通知。
- [copilot-money](https://github.com/clawdbot/skills/tree/main/skills/jayhickey/copilot-money/SKILL.md) - 查询 Copilot Money 个人理财数据（账户、交易、净资产、持仓）。
- [create-content](https://github.com/clawdbot/skills/tree/main/skills/itsflow/create-content/SKILL.md) - 思维伙伴，将创意转化为平台优化内容。
- [crypto-price](https://github.com/clawdbot/skills/tree/main/skills/evgyur/crypto-price/SKILL.md) - 通过 CoinGecko API 获取加密货币代币价格并生成蜡烛图。
- [crypto-tracker](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/crypto-tracker/SKILL.md) - 通过 CoinGecko API 跟踪加密货币价格，设置提醒，并搜索币种。
- [harvey](https://github.com/clawdbot/skills/tree/main/skills/udiedrichsen/harvey/SKILL.md) - Harvey 是一个虚拟朋友和对话伙伴。
- [ibkr-trading](https://github.com/clawdbot/skills/tree/main/skills/flokiew/ibkr-trader/SKILL.md) - 通过 Client Portal API 实现 Interactive Brokers (IBKR) 交易自动化。
- [idea](https://github.com/clawdbot/skills/tree/main/skills/andrewjiang/idea/SKILL.md) - 启动后台 Claude 会话以探索和分析商业创意。
- [just-fucking-cancel](https://github.com/clawdbot/skills/tree/main/skills/chipagosfinest/just-fucking-cancel/SKILL.md) - 分析银行交易CSV文件，识别重复扣费，分类订阅服务。
- [kraken](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/kraken/SKILL.md) - Kraken
- [launch-strategy](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/launch-strategy/SKILL.md) - 当用户需要规划产品发布、功能公告或发布策略时。
- [marketing-ideas](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/marketing-ideas/SKILL.md) - 当用户需要针对其SaaS或软件产品的营销创意、灵感或策略时。
- [nordpool-fi](https://github.com/clawdbot/skills/tree/main/skills/ovaris/nordpool-fi/SKILL.md) - 芬兰的小时电价及最优电动汽车充电时间窗口计算（3小时、4小时、5小时）。
- [openssl](https://github.com/clawdbot/skills/tree/main/skills/asleep123/openssl/SKILL.md) - 使用 OpenSSL 生成安全的随机字符串、密码和加密令牌。
- [page-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/page-cro/SKILL.md) - 当用户希望优化、改进或提升任何营销页面的转化率时——包括。
- [plaid](https://github.com/clawdbot/skills/tree/main/skills/jverdi/plaid/SKILL.md) - plaid-cli 是一个用于与 plaid 金融平台交互的命令行工具。
- [polymarket](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/polymarket/SKILL.md) - 查询 Polymarket 预测市场——查看赔率、热门市场、搜索事件、跟踪价格。
- [portfolio-watcher](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/portfolio-watcher/SKILL.md) - 监控股票/加密货币持仓，获取价格提醒，跟踪投资组合表现。
- [publisher](https://github.com/clawdbot/skills/tree/main/skills/tunaissacoding/publisher/SKILL.md) - 让你的技能易于理解，令人无法忽视。
- [relationship-skills](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/relationship-skills/SKILL.md) - 通过沟通工具、冲突解决和建立联系的策略，提升人际关系。
- [solana-swaps](https://github.com/clawdbot/skills/tree/main/skills/imthatcarlos/solana-swaps/SKILL.md) - 通过 Jupiter 聚合器在 Solana 上进行代币交换并检查钱包余额。
- [solo-cli](https://github.com/clawdbot/skills/tree/main/skills/rursache/solo-cli/SKILL.md) - 通过CLI监控并操作SOLO.ro会计平台。
- [stock-analysis](https://github.com/clawdbot/skills/tree/main/skills/udiedrichsen/stock-analysis/SKILL.md) - 使用 Yahoo Finance 数据分析股票和加密货币。
- [swissweather](https://github.com/clawdbot/skills/tree/main/skills/xenofex7/swissweather/SKILL.md) - 获取来自MeteoSwiss（瑞士官方气象服务）的当前天气和天气预报。
- [yahoo-finance](https://github.com/clawdbot/skills/tree/main/skills/ajanraj/yahoo-finance/SKILL.md) - 获取股票价格、行情、基本面、收益、期权和分红信息。
- [ynab](https://github.com/clawdbot/skills/tree/main/skills/obviyus/ynab/SKILL.md) - 通过 CLI 管理 YNAB 预算、账户、类别和交易。

## 媒体与流媒体

- [apple-media](https://github.com/clawdbot/skills/tree/main/skills/aaronn/apple-media/SKILL.md) - 通过 pyatv 控制 Apple TV、HomePod 及 AirPlay 设备（扫描、流媒体、播放、音量调节）。
- [blucli](https://github.com/clawdbot/skills/tree/main/skills/steipete/blucli/SKILL.md) - BluOS CLI (blu) 用于设备发现、播放、分组和音量控制。
- [chill-institute](https://github.com/clawdbot/skills/tree/main/skills/baanish/chill-institute/SKILL.md) - 使用 chill.institute（网页界面）搜索内容，然后点击“send to put.io”（最佳配合使用）。
- [chromecast](https://github.com/clawdbot/skills/tree/main/skills/morozred/chromecast-control/SKILL.md) - 控制本地网络中的 Chromecast 设备——发现设备、投射媒体、控制播放。
- [lastfm](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/lastfm/SKILL.md) - 访问 Last.fm 听歌历史、音乐统计和发现功能。
- [overseerr](https://github.com/clawdbot/skills/tree/main/skills/j1philli/overseerr/SKILL.md) - 通过 Overseerr API 请求电影/电视剧并监控请求状态（适用于稳定版 Overseerr）。
- [pet](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/pet/SKILL.md) - 简单的命令行代码片段管理工具。用于保存和复用复杂命令。
- [plex](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/plex/SKILL.md) - 控制 Plex Media Server —— 浏览库、搜索、播放媒体、管理播放。
- [pocket-casts](https://github.com/clawdbot/skills/tree/main/skills/manuelhettich/pocket-casts-yt/SKILL.md) - 下载YouTube视频并上传至Pocket Casts Files以供离线观看。
- [putio](https://github.com/clawdbot/skills/tree/main/skills/baanish/putio/SKILL.md) - 通过 kaput CLI 管理 put.io 账户（传输、文件、搜索）— 扬起主帆。
- [qbittorrent](https://github.com/clawdbot/skills/tree/main/skills/jmagar/qbittorrent/SKILL.md) - 使用 qBittorrent 管理种子。适用于用户请求“列出种子”、“添加种子”等操作。
- [radarr](https://github.com/clawdbot/skills/tree/main/skills/jordyvandomselaar/radarr/SKILL.md) - 搜索并添加电影到 Radarr。支持合集和添加时搜索选项。
- [roku](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/roku/SKILL.md) - 通过 python-roku 提供的 CLI 接口控制 Roku 设备。
- [sabnzbd](https://github.com/clawdbot/skills/tree/main/skills/jmagar/sabnzbd/SKILL.md) - 使用 SABnzbd 管理 Usenet 下载。适用于用户请求“检查 SABnzbd”或“列出 NZB 队列”时。
- [sonarr](https://github.com/clawdbot/skills/tree/main/skills/jordyvandomselaar/sonarr/SKILL.md) - 搜索并添加电视剧到 Sonarr。支持监控选项和添加时搜索功能。
- [sonoscli](https://github.com/clawdbot/skills/tree/main/skills/steipete/sonoscli/SKILL.md) - 控制 Sonos 扬声器（发现/状态/播放/音量/分组）。
- [spotify](https://github.com/clawdbot/skills/tree/main/skills/2mawi2/spotify/SKILL.md) - 在 macOS 上控制 Spotify 播放。播放/暂停、切换曲目、调节音量。
- [spotify-applescript](https://github.com/clawdbot/skills/tree/main/skills/andrewjiang/spotify-applescript/SKILL.md) - 通过 AppleScript 控制 Spotify 桌面应用。
- [spotify-history](https://github.com/clawdbot/skills/tree/main/skills/braydoncoyer/spotify-history/SKILL.md) - 访问 Spotify 听歌历史、热门艺术家/曲目。
- [spotify-player](https://github.com/clawdbot/skills/tree/main/skills/steipete/spotify-player/SKILL.md) - 通过 spogo（首选）或 spotify_player 实现终端 Spotify 播放/搜索功能。
- [spotify-web-api](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/spotify-web-api/SKILL.md) - 通过 Web API 控制 Spotify - 播放、历史记录、热门曲目、搜索。
- [summarize](https://github.com/clawdbot/skills/tree/main/skills/steipete/summarize/SKILL.md) - 使用 summarize CLI 对 URL 或文件进行摘要（支持网页、PDF、图片、音频、YouTube）。
- [thinking-partner](https://github.com/clawdbot/skills/tree/main/skills/itsflow/thinking-partner/SKILL.md) - 通过提问共同探索复杂问题的协作思维伙伴。
- [trakt](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/trakt/SKILL.md) - 通过 trakt.tv 跟踪并查看您关注的电影和电视剧。
- [video-transcript-downloader](https://github.com/clawdbot/skills/tree/main/skills/steipete/video-transcript-downloader/SKILL.md) - 从YouTube下载视频、音频、字幕及清晰的段落式转录文本。
- [youtube-instant-article](https://github.com/clawdbot/skills/tree/main/skills/viticci/youtube-instant-article/SKILL.md) - 将YouTube视频转换为带有视觉幻灯片的Telegraph Instant View文章。
- [youtube-watcher](https://github.com/clawdbot/skills/tree/main/skills/michaelgathara/youtube-watcher/SKILL.md) - 从YouTube视频获取并读取字幕。

## 笔记与个人知识管理（PKM）

- [apple-mail](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/apple-mail/SKILL.md) - 适用于 macOS 的 Apple Mail.app 集成。支持读取收件箱、搜索邮件、发送邮件和回复邮件。
- [apple-notes](https://github.com/clawdbot/skills/tree/main/skills/steipete/apple-notes/SKILL.md) - 通过 macOS 上的 `memo` CLI 管理 Apple Notes（创建、查看、编辑、删除、搜索、移动）。
- [bear-notes](https://github.com/clawdbot/skills/tree/main/skills/steipete/bear-notes/SKILL.md) - 通过 grizzly CLI 创建、搜索和管理 Bear 笔记。
- [better-notion](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/better-notion/SKILL.md) - 支持对 Notion 页面、数据库和区块的完整 CRUD 操作，包括创建、读取、更新、删除、搜索和查询。
- [bookstack](https://github.com/clawdbot/skills/tree/main/skills/xenofex7/bookstack/SKILL.md) - BookStack Wiki 与文档 API 集成。
- [calctl](https://github.com/clawdbot/skills/tree/main/skills/rainbat/calctl/SKILL.md) - 通过 icalBuddy 和 AppleScript CLI 管理 Apple Calendar 事件。
- [craft](https://github.com/clawdbot/skills/tree/main/skills/noah-ribaudo/craft/SKILL.md) - 通过 CLI 管理 Craft 笔记、文档和任务。
- [fizzy-cli](https://github.com/clawdbot/skills/tree/main/skills/tobiasbischoff/fizzy-cli/SKILL.md) - 使用 fizzy-cli 工具进行身份验证，并管理 Fizzy 看板、卡片、评论和标签。
- [gkeep](https://github.com/clawdbot/skills/tree/main/skills/vacinc/gkeep/SKILL.md) - 通过 gkeepapi 访问 Google Keep 笔记。支持列出、搜索、创建和管理笔记。
- [granola](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/granola-notes/SKILL.md) - 访问 Granola AI 会议记录 - 支持 CSV 导入及共享笔记获取。
- [nb](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/nb/SKILL.md) - 使用 nb CLI 管理笔记、书签和笔记本。
- [Notebook](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/notebook/SKILL.md) - 本地优先的个人知识库，用于跟踪想法、项目、任务和习惯。
- [notectl](https://github.com/clawdbot/skills/tree/main/skills/rainbat/notectl/SKILL.md) - 通过 AppleScript CLI 管理 Apple Notes。
- [notion](https://github.com/clawdbot/skills/tree/main/skills/steipete/notion/SKILL.md) - Notion API 用于创建和管理页面、数据库及区块。
- [obsidian](https://github.com/clawdbot/skills/tree/main/skills/steipete/obsidian/SKILL.md) - 操作 Obsidian vault（纯 Markdown 笔记）并通过 obsidian-cli 实现自动化。
- [obsidian-conversation-backup](https://github.com/clawdbot/skills/tree/main/skills/laserducktales/obsidian-conversation-backup/SKILL.md) - Obsidian 自动对话备份系统，支持增量快照和按小时分段。
- [obsidian-daily](https://github.com/clawdbot/skills/tree/main/skills/bastos/obsidian-daily/SKILL.md) - 通过 obsidian-cli 管理 Obsidian 每日笔记。
- [onboarding-cro](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/onboarding-cro/SKILL.md) - 当用户希望优化注册后引导、用户激活和首次使用体验时。
- [purelymail](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/purelymail/SKILL.md) - 为 Clawdbot 代理设置并测试 PurelyMail 邮件功能。
- [resend](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/resend/SKILL.md) - 通过 Resend API 管理接收的（入站）邮件及附件。
- [second-brain](https://github.com/clawdbot/skills/tree/main/skills/christinetyip/second-brain/SKILL.md) - 由 Ensue 驱动的个人知识库，用于捕捉和检索理解内容。
- [shared-memory](https://github.com/clawdbot/skills/tree/main/skills/christinetyip/shared-memory/SKILL.md) - 与其他用户共享记忆和状态。
- [skillcraft](https://github.com/clawdbot/skills/tree/main/skills/jmz1/skillcraft/SKILL.md) - 创建、设计并打包 Clawdbot 技能。
- [sports-ticker](https://github.com/clawdbot/skills/tree/main/skills/robbyczgw-cla/sports-ticker/SKILL.md) - 提供足球、NFL、NBA、NHL、MLB、F1 等多项体育赛事的实时提醒。

## 运输

- [anachb](https://github.com/clawdbot/skills/tree/main/skills/manmal/a-nach-b/SKILL.md) - 奥地利公共交通（VOR AnachB），覆盖全奥地利。
- [charger](https://github.com/clawdbot/skills/tree/main/skills/borahm/charger/SKILL.md) - 通过 Google Places 检查电动车充电器的可用性（收藏夹、附近搜索）。
- [flight-tracker](https://github.com/clawdbot/skills/tree/main/skills/xenofex7/flight-tracker/SKILL.md) - 航班跟踪与调度。按区域和呼号实时跟踪航班动态。
- [flights](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/flights/SKILL.md) - 跟踪航班状态、延误情况及搜索航线。使用 FlightAware 数据。
- [gotrain](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/gotrain/SKILL.md) - MTA系统列车发车信息（纽约地铁、长岛铁路、Metro-North）。
- [incident-pcn-evidence-appeal-corrective-actions-uk](https://github.com/clawdbot/skills/tree/main/skills/kowl64/incident-pcn-evidence-appeal-corrective-actions-uk/SKILL.md) - 构建包含时间线、申诉草稿和纠正措施的事故/PCN证据包。
- [mbta](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/mbta/SKILL.md) - 波士顿地区地铁、公交、通勤铁路及渡轮的实时MBTA交通预测。
- [oebb-scotty](https://github.com/clawdbot/skills/tree/main/skills/manmal/oebb-scotty/SKILL.md) - 奥地利铁路出行规划工具（ÖBB Scotty）。
- [openerz](https://github.com/clawdbot/skills/tree/main/skills/mbjoern/erz-entsorgung-recycling-zurich/SKILL.md) - 通过 OpenERZ API 获取苏黎世的垃圾收集日历。
- [railil](https://github.com/clawdbot/skills/tree/main/skills/lirantal/railil/SKILL.md) - 使用 railil CLI 查询 Israel Rail 火车时刻表。
- [rejseplanen](https://github.com/clawdbot/skills/tree/main/skills/bjarkehs/rejseplanen/SKILL.md) - 通过 Rejseplanen API 查询丹麦公共交通的出发、到达及行程规划信息。
- [skanetrafiken](https://github.com/clawdbot/skills/tree/main/skills/rezkam/skanetrafiken/SKILL.md) - Skåne公共交通出行规划器（Skånetrafiken）。规划包含实时延误信息的公交/火车行程。
- [swiss-geo](https://github.com/clawdbot/skills/tree/main/skills/mbjoern/swiss-geo-and-tourism-assistant/SKILL.md) - 瑞士地理数据、兴趣点（POIs）及旅游信息。地点/地址搜索，高程查询。
- [swiss-phone-directory](https://github.com/clawdbot/skills/tree/main/skills/xenofex7/swiss-phone-directory/SKILL.md) - 通过 search.ch API 进行瑞士电话号码查询。
- [swiss-transport](https://github.com/clawdbot/skills/tree/main/skills/xenofex7/swiss-transport/SKILL.md) - 瑞士公共交通实时信息。
- [tachograph-infringement-triage-root-cause-uk](https://github.com/clawdbot/skills/tree/main/skills/kowl64/tachograph-infringement-triage-root-cause-uk/SKILL.md) - 对行车记录仪违规行为进行分类，识别常见模式。
- [tesla](https://github.com/clawdbot/skills/tree/main/skills/mvanhorn/tesla/SKILL.md) - 控制您的Tesla车辆——锁定/解锁、空调、位置、充电状态等功能。
- [tesla-commands](https://github.com/clawdbot/skills/tree/main/skills/ovaris/tesla-commands/SKILL.md) - 通过 MyTeslaMate API 控制您的 Tesla。支持多车辆账户和空调控制。
- [tessie](https://github.com/clawdbot/skills/tree/main/skills/baanish/tessie/SKILL.md) - tessie
- [tfl-journey-disruption](https://github.com/clawdbot/skills/tree/main/skills/diegopetrucci/transport-for-london-journey-disruption/SKILL.md) - 根据起点/终点/时间规划TfL行程，支持解析位置（优先使用邮编）。
- [transport-investigation-acas-aligned-pack](https://github.com/clawdbot/skills/tree/main/skills/kowl64/transport-investigation-acas-aligned-pack/SKILL.md) - 生成符合ACAS标准的调查邀请措辞、中立问题集和证据记录。
- [trimet](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/trimet/SKILL.md) - 获取波特兰公共交通信息，包括到站时间、行程规划和通知。
- [virus-monitor](https://github.com/clawdbot/skills/tree/main/skills/pasogott/virus-monitor/SKILL.md) - 维也纳病毒监测（污水 + Sentinel）。
- [wienerlinien](https://github.com/clawdbot/skills/tree/main/skills/hjanuschka/wienerlinien/SKILL.md) - 维也纳公共交通（Wiener Linien）实时数据。

## 个人发展

- [daily-review](https://github.com/clawdbot/skills/tree/main/skills/henrino3/daily-review/SKILL.md) - 全面的每日绩效评估，包含沟通跟踪与会议分析。
- [drivers-hours-wtd-infringement-coach-uk](https://github.com/clawdbot/skills/tree/main/skills/kowl64/drivers-hours-wtd-infringement-coach-uk/SKILL.md) - 生成一页面向司机的转速表/WTD违规通知，包括纠正措施和复查日期。
- [graphiti](https://github.com/clawdbot/skills/tree/main/skills/emasoudy/graphiti/SKILL.md) - 通过 Graphiti API 进行知识图谱操作。
- [morning-routine](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/morning-routine/SKILL.md) - 通过习惯清单、时间管理和连胜追踪，打造高效的晨间例行程序。
- [munger-observer](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/munger-observer/SKILL.md) - 每日智慧回顾，将Charlie Munger的思维模型应用于您的工作和思考。
- [night-routine](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/night-routine/SKILL.md) - 建立一个包含放松习惯、睡前准备和次日计划的高效夜间休息流程。
- [overcome-problem](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/overcome-problem/SKILL.md) - 通过结构化思维、行动计划和进度跟踪，分解任何问题。
- [procrastination-buster](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/procrastination-buster/SKILL.md) - 通过任务拆解、两分钟启动法和责任追踪来克服拖延。
- [quit-alcohol](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-alcohol/SKILL.md) - 通过无酒精连续天数、渴望管理和康复里程碑来跟踪戒酒进程。
- [quit-caffeine](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-caffeine/SKILL.md) - 通过戒断追踪、逐步减少计划和能量里程碑，帮助减少或戒除咖啡因。
- [quit-overspending](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-overspending/SKILL.md) - 通过消费连胜、冲动追踪和储蓄里程碑打破冲动购物习惯。
- [quit-porn](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-porn/SKILL.md) - 通过记录连续天数、管理冲动和设定恢复里程碑，帮助摆脱色情成瘾。
- [quit-smoking](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-smoking/SKILL.md) - 通过无烟追踪、渴望支持和健康恢复时间表，帮助戒烟。
- [quit-vaping](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-vaping/SKILL.md) - 通过无尼古丁连续记录、戒断工具和健康里程碑，帮助戒除电子烟。
- [quit-weed](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/quit-weed/SKILL.md) - 通过记录连续天数和提供渴望支持，帮助您进行耐受性休息或戒除大麻。
- [self-love-confidence](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/self-love-confidence/SKILL.md) - 通过肯定语、胜利记录和内心批评管理，建立自爱与自信。
- [social-media-detox](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/social-media-detox/SKILL.md) - 通过无屏连续使用、冲动追踪和数字健康管理，帮助戒除社交媒体成瘾。
- [stress-relief](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/stress-relief/SKILL.md) - 通过快速技巧、压力记录和恢复工具管理压力。
- [study-habits](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/study-habits/SKILL.md) - 通过间隔重复、主动回忆和会话跟踪，建立高效的学习习惯。
- [therapy-mode](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/therapy-mode/SKILL.md) - 综合AI辅助治疗支持框架。
- [weekly-synthesis](https://github.com/clawdbot/skills/tree/main/skills/itsflow/weekly-synthesis/SKILL.md) - 对本周工作与思考进行全面总结。

## 健康与健身

- [coach](https://github.com/clawdbot/skills/tree/main/skills/shiv19/clawd-coach/SKILL.md) - 创建个性化的铁人三项、马拉松和超长耐力训练计划。
- [endurance-coach](https://github.com/clawdbot/skills/tree/main/skills/shiv19/endurance-coach/SKILL.md) - 创建个性化的铁人三项、马拉松和超长耐力训练计划。
- [fitbit](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/fitbit/SKILL.md) - 查询 Fitbit 健康数据，包括睡眠、心率、活动、血氧饱和度（SpO2）和呼吸频率。
- [fitbit-analytics](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/fitbit-analytics/SKILL.md) - Fitbit 健康与健身数据集成。
- [hevy](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/hevy/SKILL.md) - 从 Hevy 查询锻炼数据，包括锻炼、计划、动作和历史记录。
- [huckleberry](https://github.com/clawdbot/skills/tree/main/skills/jayhickey/huckleberry/SKILL.md) - 通过 Huckleberry CLI 跟踪婴儿的睡眠、喂养、尿布和成长情况。
- [muscle-gain](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/muscle-gain/SKILL.md) - 通过重量进展、蛋白质摄入跟踪和力量里程碑监测肌肉增长。
- [oura](https://github.com/clawdbot/skills/tree/main/skills/ruhrpotter/oura/SKILL.md) - oura
- [oura-analytics](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/oura-analytics/SKILL.md) - Oura Ring 数据集成与分析。
- [pregnancy-tracker](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/pregnancy-tracker/SKILL.md) - 通过每周更新、症状记录和里程碑倒计时，跟踪孕期进程。
- [ranked-gym](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/ranked-gym/SKILL.md) - 通过XP、等级、成就和锻炼连胜，让你的健身课程更具游戏化体验。
- [strava](https://github.com/clawdbot/skills/tree/main/skills/bohdanpodvirnyi/strava/SKILL.md) - 使用 Strava API 加载并分析 Strava 活动、统计数据和训练记录。
- [testosterone-optimization](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/testosterone-optimization/SKILL.md) - 通过睡眠、锻炼、营养和生活方式跟踪优化自然睾酮水平。
- [the-sports-db](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/the-sports-db/SKILL.md) - 通过 TheSportsDB 访问体育数据（球队、赛事、比分）。
- [weight-loss](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/weight-loss/SKILL.md) - 通过称重记录、趋势分析和目标里程碑，跟踪减重进程。
- [whoop](https://github.com/clawdbot/skills/tree/main/skills/borahm/whoop/SKILL.md) - WHOOP 早晨签到（恢复/睡眠/压力）及建议。
- [whoop-morning](https://github.com/clawdbot/skills/tree/main/skills/borahm/whoop-morning/SKILL.md) - 每天早晨检查 WHOOP 的恢复、睡眠和压力数据，并发送建议。
- [whoopskill](https://github.com/clawdbot/skills/tree/main/skills/koala73/whoopskill/SKILL.md) - WHOOP CLI 提供健康洞察、趋势分析及数据获取（睡眠、恢复、HRV、压力）。
- [workout](https://github.com/clawdbot/skills/tree/main/skills/gricha/workout/SKILL.md) - 使用 workout-cli 记录锻炼，记录组数，管理动作和模板。
- [workout-logger](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/workout-logger/SKILL.md) - 记录锻炼，跟踪进展，获取运动建议及个人最佳记录追踪。

## 通信

- [apple-mail-search](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/apple-mail-search-safe/SKILL.md) - 快速且安全的 Apple Mail 搜索，支持正文内容检索。
- [beeper](https://github.com/clawdbot/skills/tree/main/skills/krausefx/beeper/SKILL.md) - 搜索并浏览本地 Beeper 聊天记录（线程、消息、全文搜索）。
- [camelcamelcamel-alerts](https://github.com/clawdbot/skills/tree/main/skills/jgramajo4/camelcamelcamel-alerts/SKILL.md) - 通过RSS监控CamelCamelCamel价格下降提醒，并在商品降价时发送Telegram通知。
- [clawdtalk](https://github.com/team-telnyx/clawdtalk-client) - OpenClaw 的电话和短信功能。从任何电话拨打您的 AI 代理，支持日历、Jira、网络搜索等深度工具集成。由 Telnyx 提供支持。
- [discord-doctor](https://github.com/clawdbot/skills/tree/main/skills/jhillock/discord-doctor/SKILL.md) - 快速诊断和修复 Discord 机器人、Gateway、OAuth 令牌及旧版配置问题。
- [google-chat](https://github.com/clawdbot/skills/tree/main/skills/darconada/google-chat/SKILL.md) - 通过 webhook 或 OAuth 向 Google Chat 空间和用户发送消息。
- [himalaya](https://github.com/clawdbot/skills/tree/main/skills/lamelas/himalaya/SKILL.md) - 通过 IMAP/SMTP 管理邮件的 CLI 工具。使用 `himalaya` 可实现列出、阅读、撰写、回复、转发和搜索邮件。
- [imsg](https://github.com/clawdbot/skills/tree/main/skills/steipete/imsg/SKILL.md) - iMessage/SMS CLI，用于列出聊天记录、查看历史、监控和发送消息。
- [linkedin](https://github.com/clawdbot/skills/tree/main/skills/biostartechnology/linkedin/SKILL.md) - 通过浏览器中继或Cookies实现LinkedIn的自动化，用于发送消息和浏览个人资料。
- [linkedin-cli](https://github.com/clawdbot/skills/tree/main/skills/arun-8687/linkedin-cli/SKILL.md) - 一个类鸟形的 LinkedIn CLI，用于搜索个人资料和查看消息。
- [ms365](https://github.com/clawdbot/skills/tree/main/skills/cvsloane/ms365/SKILL.md) - 微软365 (Microsoft 365)
- [paid-ads](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/paid-ads/SKILL.md) - 当用户需要关于Google Ads、Meta（Facebook/Instagram）付费广告活动的帮助时
- [protonmail](https://github.com/clawdbot/skills/tree/main/skills/durchblick-nl/protonmail/SKILL.md) - 通过 IMAP 桥接（Proton Bridge 或 hydroxide）读取、搜索和扫描 ProtonMail。
- [social-content](https://github.com/clawdbot/skills/tree/main/skills/jchopard69/marketing-skills/references/social-content/SKILL.md) - 当用户需要帮助创建、安排或优化社交媒体内容时。
- [table-image](https://github.com/clawdbot/skills/tree/main/skills/joargp/table-image/SKILL.md) - 将表格生成图片，以提升在 Telegram 等消息应用中的可读性。
- [telegram-usage](https://github.com/clawdbot/skills/tree/main/skills/c-drew/telegram-usage/SKILL.md) - 显示会话使用统计信息（配额、会话时间、令牌数、上下文）。
- [wacli](https://github.com/clawdbot/skills/tree/main/skills/steipete/wacli/SKILL.md) - 发送 WhatsApp 消息给其他人或搜索/同步 WhatsApp 历史记录。
- [whatsapp-video-mockup](https://github.com/clawdbot/skills/tree/main/skills/danpeg/whatsapp-video-mockup/SKILL.md) - whatsapp视频模型

## 语音与转录

- [assemblyai-transcribe](https://github.com/clawdbot/skills/tree/main/skills/tristanmanchester/assemblyai-transcribe/SKILL.md) - 使用 AssemblyAI 转录音频/视频（本地上传）。
- [audio-gen](https://github.com/clawdbot/skills/tree/main/skills/udiedrichsen/audio-gen/SKILL.md) - 按需生成有声书、播客或教育音频内容。
- [audio-reply](https://github.com/clawdbot/skills/tree/main/skills/matrixy/audio-reply-skill/SKILL.md) - 使用TTS生成语音回复。通过“read it to me [URL]”触发并获取内容。
- [edge-tts](https://github.com/clawdbot/skills/tree/main/skills/i3130002/edge-tts/SKILL.md) - 抱歉，您提供的内容为空或不完整，请您提供需要翻译的英文描述。
- [gettr-transcribe-summarize](https://github.com/clawdbot/skills/tree/main/skills/kevin37li/gettr-transcribe-summarize/SKILL.md) - 从GETTR帖子下载音频（通过HTML中的og:video），并在本地进行转录。
- [llmwhisperer](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/llmwhisperer/SKILL.md) - 使用 LLMWhisperer API 从图像和 PDF 中提取文本及布局信息。
- [local-whisper](https://github.com/clawdbot/skills/tree/main/skills/araa47/local-whisper/SKILL.md) - 本地语音转文本，基于 OpenAI Whisper。模型下载完成后可完全离线运行。
- [mlx-whisper](https://github.com/clawdbot/skills/tree/main/skills/kevin37li/mlx-whisper/SKILL.md) - 本地语音转文本，使用 MLX Whisper（针对 Apple Silicon 优化，无需 API 密钥）。
- [openai-whisper](https://github.com/clawdbot/skills/tree/main/skills/steipete/openai-whisper/SKILL.md) - 使用 Whisper CLI 实现本地语音转文字（无需 API 密钥）。
- [openai-whisper-api](https://github.com/clawdbot/skills/tree/main/skills/steipete/openai-whisper-api/SKILL.md) - 通过 OpenAI Audio Transcriptions API（Whisper）进行音频转录。
- [parakeet-mlx](https://github.com/clawdbot/skills/tree/main/skills/kylehowells/parakeet-mlx/SKILL.md) - 基于 Apple Silicon 的 Parakeet MLX 本地语音转文本（ASR），无需 API 密钥。
- [parakeet-stt](https://github.com/clawdbot/skills/tree/main/skills/carlulsoe/parakeet-stt/SKILL.md) - 抱歉，您提供的内容不完整或无法识别，请提供完整的英文描述以便翻译。
- [pocket-transcripts](https://github.com/clawdbot/skills/tree/main/skills/tmustier/heypocket-reader/SKILL.md) - 读取来自 Pocket AI（heypocket.com）录音设备的转录文本和摘要。
- [pocket-tts](https://github.com/clawdbot/skills/tree/main/skills/sherajdev/pocket-tts/SKILL.md) - pocket-tts（便携式文本转语音）
- [tts-whatsapp](https://github.com/clawdbot/skills/tree/main/skills/hopyky/tts-whatsapp/SKILL.md) - 在WhatsApp上以40多种语言发送高质量的文本转语音语音消息，支持自动发送。
- [video-subtitles](https://github.com/clawdbot/skills/tree/main/skills/ngutman/video-subtitles/SKILL.md) - 从视频/音频生成带翻译支持的SRT字幕。
- [voice-transcribe](https://github.com/clawdbot/skills/tree/main/skills/darinkishore/voice-transcribe/SKILL.md) - 使用 OpenAI 的 gpt-4o-mini-transcribe 模型及词汇提示对音频文件进行转录。

## 智能家居与物联网

- [anova-oven](https://github.com/clawdbot/skills/tree/main/skills/dodeja/anova-skill/SKILL.md) - 通过WiFi WebSocket API控制Anova Precision Ovens和Precision Cookers（低温慢煮设备）。
- [bambu-cli](https://github.com/clawdbot/skills/tree/main/skills/tobiasbischoff/bambu-cli/SKILL.md) - 使用 bambu-cli（status/watch）操作和排查 BambuLab 打印机。
- [beestat](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/beestat/SKILL.md) - 通过 Beestat API 查询 ecobee 恒温器数据，包括温度、湿度和空气质量（CO2）。
- [dyson-cli](https://github.com/clawdbot/skills/tree/main/skills/tmustier/dyson-cli/SKILL.md) - 通过本地 MQTT 控制 Dyson 空气净化器、风扇和加热器。
- [eightctl](https://github.com/clawdbot/skills/tree/main/skills/steipete/eightctl/SKILL.md) - 控制八个 Eight Sleep 床垫（状态、温度、警报、日程）。
- [google-home](https://github.com/clawdbot/skills/tree/main/skills/mitchellbernstein/google-home/SKILL.md) - 控制 Google Nest 设备（恒温器、摄像头、门铃）
- [govee-lights](https://github.com/clawdbot/skills/tree/main/skills/joeynyc/govee-lights/SKILL.md) - 通过 Govee API 控制 Govee 智能灯。
- [homeassistant](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/homeassistant/SKILL.md) - 控制 Home Assistant —— 智能插座、灯光、场景、自动化。
- [homey](https://github.com/clawdbot/skills/tree/main/skills/maxsumrall/homey/SKILL.md) - 通过本地（LAN/VPN）或云端API控制Athom Homey智能家居设备。
- [homey-cli](https://github.com/clawdbot/skills/tree/main/skills/krausefx/homey-cli/SKILL.md) - 通过CLI控制Homey智能家居中枢。
- [nanoleaf](https://github.com/clawdbot/skills/tree/main/skills/rstierli/nanoleaf/SKILL.md) - 通过 Picoleaf CLI 控制 Nanoleaf 灯光面板。
- [nest-devices](https://github.com/clawdbot/skills/tree/main/skills/amogower/nest-devices/SKILL.md) - 通过 Device Access API 控制 Nest 智能家居设备（恒温器、摄像头、门铃）。
- [openhue](https://github.com/clawdbot/skills/tree/main/skills/steipete/openhue/SKILL.md) - 通过 OpenHue CLI 控制 Philips Hue 灯光/场景。
- [pihole](https://github.com/clawdbot/skills/tree/main/skills/baanish/pihole/SKILL.md) - pihole 是一种网络广告拦截工具，通常作为局域网内的DNS服务器使用，用于阻止广告、跟踪器和恶意网站的访问，从而提升网络安全和浏览体验。
- [printer](https://github.com/clawdbot/skills/tree/main/skills/dhvanilpatel/printer/SKILL.md) - 通过 macOS 上的 CUPS 管理打印机（发现、添加、打印、队列、状态、唤醒）。
- [voicemonkey](https://github.com/clawdbot/skills/tree/main/skills/jayakumark/voicemonkey/SKILL.md) - 通过 VoiceMonkey API v2 控制 Alexa 设备——进行公告、触发例程、启动流程。

## 购物与电子商务

- [anylist](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/anylist/SKILL.md) - 通过 AnyList 管理杂货和购物清单。
- [bring-shopping](https://github.com/clawdbot/skills/tree/main/skills/cutzenfriend/bring-shopping/SKILL.md) - 通过非官方的 bring-shopping Node.js 库管理 Bring! 购物清单。
- [checkers-sixty60](https://github.com/clawdbot/skills/tree/main/skills/snopoke/checkers-sixty60/SKILL.md) - 通过浏览器自动化在 Checkers.co.za 使用 Sixty60 送货服务购物。
- [event-planner](https://github.com/clawdbot/skills/tree/main/skills/udiedrichsen/event-planner/SKILL.md) - 通过搜索场地规划活动（夜晚外出、周末、约会之夜、团队出游、用餐、旅行）。
- [food-order](https://github.com/clawdbot/skills/tree/main/skills/steipete/food-order/SKILL.md) - 使用 ordercli 重新排序 Foodora 订单并跟踪预计到达时间及状态。
- [grocery-list](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/grocery-list/SKILL.md) - 独立的购物清单、食谱和餐食计划，支持本地存储。
- [gurkerlcli](https://github.com/clawdbot/skills/tree/main/skills/pasogott/gurkerlcli/SKILL.md) - 通过 gurkerl.at 进行奥地利在线杂货购物。
- [idealista](https://github.com/clawdbot/skills/tree/main/skills/quifago/idealista/SKILL.md) - 通过 idealista-cli 使用 OAuth2 客户端凭证方式查询 Idealista API。
- [irish-takeaway](https://github.com/clawdbot/skills/tree/main/skills/cotyledonlab/irish-takeaway/SKILL.md) - 在爱尔兰查找附近的外卖店并通过 Deliveroo/Just Eat 浏览菜单。
- [marktplaats](https://github.com/clawdbot/skills/tree/main/skills/pvoo/marktplaats/SKILL.md) - 支持跨所有类别搜索 Marktplaats.nl 分类信息并提供筛选功能。
- [ordercli](https://github.com/clawdbot/skills/tree/main/skills/steipete/ordercli/SKILL.md) - 仅支持Foodora的CLI，用于查询历史订单和当前订单状态（Deliveroo功能开发中）。
- [paprika](https://github.com/clawdbot/skills/tree/main/skills/mjrussell/paprika/SKILL.md) - 从 Paprika Recipe Manager 获取食谱、膳食计划和购物清单。
- [picnic](https://github.com/clawdbot/skills/tree/main/skills/mpociot/picnic/SKILL.md) - 从Picnic超市订购杂货 - 搜索商品，管理购物车，安排送货时间。
- [plan2meal](https://github.com/clawdbot/skills/tree/main/skills/okikesolutions/plan2meal/SKILL.md) - plan2meal
- [shopping-expert](https://github.com/clawdbot/skills/tree/main/skills/udiedrichsen/shopping-expert/SKILL.md) - 在线（Google Shopping）和本地（附近商店）查找并比较产品。
- [whcli](https://github.com/clawdbot/skills/tree/main/skills/pasogott/whcli/SKILL.md) - Willhaben CLI 用于搜索奥地利最大的分类信息市场。

## 日历与日程安排

- [accli](https://github.com/clawdbot/skills/tree/main/skills/joargp/accli/SKILL.md) - 该技能应在与 macOS 上的 Apple Calendar 交互时使用。
- [apple-calendar](https://github.com/clawdbot/skills/tree/main/skills/tyler6204/apple-calendar/SKILL.md) - 适用于 macOS 的 Apple Calendar.app 集成。
- [apple-reminders](https://github.com/clawdbot/skills/tree/main/skills/steipete/apple-reminders/SKILL.md) - 通过 macOS 上的 `remindctl` CLI 管理 Apple Reminders（列出、添加、编辑、完成、删除）。
- [calcurse](https://github.com/clawdbot/skills/tree/main/skills/gumadeiras/calcurse/SKILL.md) - 一个基于文本的日历和日程管理应用。专用于CLI环境下的日历管理。
- [caldav-calendar](https://github.com/clawdbot/skills/tree/main/skills/asleep123/caldav-calendar/SKILL.md) - 同步和查询 CalDAV 日历（iCloud、Google、Fastmail、Nextcloud 等）
- [clippy](https://github.com/clawdbot/skills/tree/main/skills/foeken/clippy/SKILL.md) - Microsoft 365 / Outlook 的日历和邮件 CLI 工具。
- [cpc-mpqc-competence-tracker-compliance-uk](https://github.com/clawdbot/skills/tree/main/skills/kowl64/cpc-mpqc-competence-tracker-compliance-uk/SKILL.md) - 规划CPC/MPQC能力跟踪，包含提醒、证据清单和合规报告。
- [gog](https://github.com/clawdbot/skills/tree/main/skills/steipete/gog/SKILL.md) - 适用于 Gmail、Calendar、Drive、Contacts、Sheets 和 Docs 的 Google Workspace CLI。
- [holocube](https://github.com/clawdbot/skills/tree/main/skills/andrewjiang/holocube/SKILL.md) - 使用 HoloClawd 固件控制 GeekMagic HelloCubic-Lite 全息立方显示器。
- [mcd-cn](https://github.com/clawdbot/skills/tree/main/skills/ryanchen01/mcd-cn/SKILL.md) - 通过 mcd-cn CLI 查询 McDonald's China MCP 服务器的活动日历和优惠券。
- [morning-email-rollup](https://github.com/clawdbot/skills/tree/main/skills/am-will/morning-email-rollup/SKILL.md) - 每天上午8点汇总重要邮件和日历事件，并生成AI摘要。
- [remind-me](https://github.com/clawdbot/skills/tree/main/skills/julianengel/remind-me/SKILL.md) - 使用自然语言设置提醒。自动创建一次性cron任务并记录到markdown。
- [roadrunner](https://github.com/clawdbot/skills/tree/main/skills/johntheyoung/roadrunner/SKILL.md) - Beeper Desktop CLI 用于聊天、消息、搜索和提醒。
- [timer](https://github.com/clawdbot/skills/tree/main/skills/hisxo/timer/SKILL.md) - 设置定时器和闹钟。当后台定时器完成时。

## PDF 与文档

- [confluence](https://github.com/clawdbot/skills/tree/main/skills/francisbrero/confluence/SKILL.md) - 使用 confluence-cli 搜索和管理 Confluence 页面及空间。
- [excel](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/excel/SKILL.md) - 读取、写入、编辑和格式化 Excel 文件（.xlsx）。
- [excel-weekly-dashboard](https://github.com/clawdbot/skills/tree/main/skills/kowl64/excel-weekly-dashboard/SKILL.md) - 设计可刷新Excel仪表板（Power Query + 结构化表格 + 数据验证 + 透视表）。
- [intomd](https://github.com/clawdbot/skills/tree/main/skills/rezhajulio/intomd/SKILL.md) - 使用 into.md 服务获取并将任意文档 URL 转换为 Markdown 格式。
- [invoice-generator](https://github.com/clawdbot/skills/tree/main/skills/tmigone/invoice-generator/SKILL.md) - 从JSON数据生成专业PDF发票。
- [markdown-converter](https://github.com/clawdbot/skills/tree/main/skills/steipete/markdown-converter/SKILL.md) - 使用 markitdown 将文档和文件转换为 Markdown 格式。
- [mineru-pdf](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/mineru-pdf-parser-clawdbot-skill/SKILL.md) - 使用 MinerU 在本地（CPU）将 PDF 解析为 Markdown/JSON。
- [nano-pdf](https://github.com/clawdbot/skills/tree/main/skills/steipete/nano-pdf/SKILL.md) - 使用 nano-pdf CLI，通过自然语言指令编辑 PDF。
- [nudocs](https://github.com/clawdbot/skills/tree/main/skills/jdrhyne/nudocs/SKILL.md) - 通过 Nudocs.ai 上传、编辑和导出文档。
- [pdf-form-filler](https://github.com/clawdbot/skills/tree/main/skills/raulsimpetru/pdf-form-filler/SKILL.md) - 通过编程方式填写PDF表单，包括文本值和复选框。
- [pptx-creator](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/pptx-creator/SKILL.md) - 根据大纲、数据源或AI生成内容制作专业的PowerPoint演示文稿。
- [pymupdf-pdf](https://github.com/clawdbot/skills/tree/main/skills/kesslerio/pymupdf-pdf-parser-clawdbot-skill/SKILL.md) - 使用 PyMuPDF（fitz）实现快速本地 PDF 解析，支持输出 Markdown/JSON 格式，并可选提取图片和表格。

## 自托管与自动化

- [bridle](https://github.com/clawdbot/skills/tree/main/skills/bjesuiter/bridle/SKILL.md) - AI 编码助手的统一配置管理器。
- [fathom](https://github.com/clawdbot/skills/tree/main/skills/stopmoclay/fathom/SKILL.md) - 连接到 Fathom AI 以获取通话录音、转录文本和摘要。
- [frappecli](https://github.com/clawdbot/skills/tree/main/skills/pasogott/frappecli/SKILL.md) - Frappe Framework / ERPNext 实例的命令行工具（CLI）。
- [gotify](https://github.com/clawdbot/skills/tree/main/skills/jmagar/gotify/SKILL.md) - 当长时间运行的任务完成或发生重要事件时，通过 Gotify 发送推送通知。
- [meetgeek](https://github.com/clawdbot/skills/tree/main/skills/nexty5870/meetgeek/SKILL.md) - 通过 CLI 查询 MeetGeek 会议智能—列出会议、获取 AI 摘要和转录内容。
- [n8n](https://github.com/clawdbot/skills/tree/main/skills/thomasansems/n8n/SKILL.md) - 通过API管理n8n工作流和自动化。
- [n8n-workflow-automation](https://github.com/clawdbot/skills/tree/main/skills/kowl64/n8n-workflow-automation/SKILL.md) - 设计并输出包含健壮触发器、幂等性、错误处理和日志记录的 n8n 工作流 JSON。
- [paperless](https://github.com/clawdbot/skills/tree/main/skills/nickchristensen/paperless/SKILL.md) - 通过 ppls CLI 与 Paperless-NGX 文档管理系统交互。
- [unifi](https://github.com/clawdbot/skills/tree/main/skills/jmagar/unifi/SKILL.md) - 通过本地网关API（Cloud Gateway Max / UniFi OS）查询和监控UniFi网络。

## 新闻与RSS

- [bbc-news](https://github.com/clawdbot/skills/tree/main/skills/ddrayne/bbc-news/SKILL.md) - 通过RSS订阅获取并显示BBC News各个版块和地区的新闻报道。
- [blogwatcher](https://github.com/clawdbot/skills/tree/main/skills/steipete/blogwatcher/SKILL.md) - 使用 blogwatcher CLI 监控博客和 RSS/Atom 订阅源的更新。
- [hn](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/hn/SKILL.md) - 浏览 Hacker News —— 顶级故事、新帖、最佳、问答、展示、招聘及带评论的故事详情。
- [hn-digest](https://github.com/clawdbot/skills/tree/main/skills/cpojer/hn-digest/SKILL.md) - 按需获取并发送 Hacker News 首页帖子。
- [miniflux](https://github.com/clawdbot/skills/tree/main/skills/shekohex/miniflux/SKILL.md) - 浏览、阅读和管理 Miniflux 订阅源文章。
- [news-summary](https://github.com/clawdbot/skills/tree/main/skills/joargp/news-summary/SKILL.md) - 当用户请求新闻更新或每日简报时，应使用此技能。
- [newsletter-digest](https://github.com/clawdbot/skills/tree/main/skills/jhillin8/newsletter-digest/SKILL.md) - 总结新闻通讯和文章，提取关键信息，创建阅读列表。
- [orf-digest](https://github.com/clawdbot/skills/tree/main/skills/cpojer/orf/SKILL.md) - 按需提供德语ORF新闻摘要。当用户说“orf”、“pull orf”或“orf 10”时使用。

## 书签与阅读

- [fabric-api](https://github.com/clawdbot/skills/tree/main/skills/tristanmanchester/fabric-api/SKILL.md) - 通过 HTTP API 创建/搜索 Fabric 资源（记事本、文件夹、书签、文件）。
- [instapaper](https://github.com/clawdbot/skills/tree/main/skills/vburojevic/instapaper/SKILL.md) - 在使用 instapaper-cli (ip) 工具或进行故障排除时使用：身份验证。
- [karakeep](https://github.com/clawdbot/skills/tree/main/skills/jayphen/karakeep/SKILL.md) - 管理 Karakeep 实例中的书签和链接。
- [linkding](https://github.com/clawdbot/skills/tree/main/skills/jmagar/linkding/SKILL.md) - 使用 Linkding 管理书签。适用于用户请求“保存书签”或“添加链接”时。
- [readeck](https://github.com/clawdbot/skills/tree/main/skills/jayphen/readeck/SKILL.md) - Readeck 集成，用于保存和管理文章。
- [readwise](https://github.com/clawdbot/skills/tree/main/skills/refrigerator/readwise/SKILL.md) - 访问 Readwise 高亮内容和 Reader 保存的文章。
- [twitter-bookmark-sync](https://github.com/clawdbot/skills/tree/main/skills/tunaissacoding/twitter-bookmark-sync/SKILL.md) - 每天自动对你的 Twitter 收藏进行排名，并提供精选阅读列表。

## 天气

- [daily-recap](https://github.com/clawdbot/skills/tree/main/skills/dbhurley/daily-recap/SKILL.md) - 生成一张日常总结图像，图中你的agent手持一块展示成就的海报板。
- [snow-report](https://github.com/clawdbot/skills/tree/main/skills/davemorin/snow-report/SKILL.md) - 获取全球任意滑雪度假村的雪况、天气预报和滑雪报告。
- [weather](https://github.com/clawdbot/skills/tree/main/skills/steipete/weather/SKILL.md) - 获取当前天气和预报（无需API密钥）。
- [weather-pollen](https://github.com/clawdbot/skills/tree/main/skills/thesethrose/weather-pollen/SKILL.md) - 使用免费API获取任意地点的天气和花粉报告。
- [weathercli](https://github.com/clawdbot/skills/tree/main/skills/pjtf93/weathercli/SKILL.md) - 获取全球任意地点的当前天气状况和预报。

## 安全与密码

- [1password](https://github.com/clawdbot/skills/tree/main/skills/steipete/1password/SKILL.md) - 设置并使用 1Password CLI（op）。在安装 CLI 时启用桌面应用集成。
- [bitwarden](https://github.com/clawdbot/skills/tree/main/skills/asleep123/bitwarden/SKILL.md) - 使用 rbw CLI 安全访问和管理 Bitwarden/Vaultwarden 密码。
- [dashlane](https://github.com/clawdbot/skills/tree/main/skills/gnarco/dashlane/SKILL.md) - 从 Dashlane 保管库访问密码、安全笔记、密钥和一次性密码（OTP）代码。

## 贡献指南

欢迎贡献！

- To add your skill, first publish it to [ClawdHub](https://clawdhub.com). After publishing, you'll get a GitHub repository link (e.g., `https://github.com/clawdbot/skills/tree/main/skills/username/skill-name`). Then submit a PR to this repo with your skill entry including that link
- Improve existing definitions

**注意：** 请勿提交您在3小时前创建的技能。我们目前重点关注社区采纳的技能，尤其是由开发团队发布并在实际应用中验证的技能。质量优先于数量。

*这是一个精选列表。我们不对所列项目的安全性或正确性进行审核、认可或保证。*
