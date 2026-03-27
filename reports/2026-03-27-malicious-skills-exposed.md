# Malicious AI Agent Skills Exposed

> Date: 2026-03-27 | Audited by [ClawSec](https://clawsec.cc)

**247** malicious skills detected out of **2084** audited.

### 1. 🚨 humanize-ai-text by moltbro

**Risk:** 76% ████████░░ | **Downloads:** 32,323

> A CLI toolkit that detects linguistic patterns associated with AI-generated text and rewrites content to evade AI detection systems such as GPTZero, T

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

### 4. 🚨 task-status by mightyprime1

**Risk:** 88% █████████░ | **Downloads:** 7,738

> A Clawdbot helper skill that sends task status messages to a Telegram account via WebSocket or CLI fallback, with optional periodic 'heartbeat' update

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/task-status)

---

### 5. 🚨 clawdbot-security-check by thesethrose

**Risk:** 65% ██████░░░░ | **Downloads:** 7,303

> A knowledge-based security audit framework for an AI agent called Clawdbot that teaches the agent to evaluate its own configuration across 13 security

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawdbot-security-check)

---

### 6. 🚨 safe-exec by ottttto

**Risk:** 82% ████████░░ | **Downloads:** 7,007

> A command approval/interception tool for OpenClaw Agents that claims to detect dangerous shell commands, assess risk levels, and require user approval

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/safe-exec)

---

### 7. 🚨 base-trader by sp0oby

**Risk:** 88% █████████░ | **Downloads:** 6,230

> An autonomous AI-driven crypto trading skill for Base chain that executes buy/sell orders, manages risk parameters, monitors portfolio performance, an

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/base-trader)

---

### 8. 🚨 polyclaw by pipethedev

**Risk:** 85% ████████░░ | **Downloads:** 5,249

> This skill transforms Claude into an onboarding and social-posting assistant for a third-party autonomous trading service (polyclaw.ai) that trades re

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/polyclaw)

---

### 9. 🚨 beauty-generation-api by luruibu

**Risk:** 82% ████████░░ | **Downloads:** 4,953

> This skill directs Claude to act as a client for a third-party AI portrait generation API (gen1.diversityfaces.org), collecting user emails/personal i

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/beauty-generation-api)

---

### 10. 🚨 holyspiritos by maxsikorski

**Risk:** 88% █████████░ | **Downloads:** 4,565

> A skill that claims to install a 'Christian moral alignment layer' for OpenClaw AI agents by fetching remote scripts via curl|bash and appending behav

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/holyspiritos)

---

### 11. 🚨 clawbrowser by tezatezaz

**Risk:** 82% ████████░░ | **Downloads:** 3,741

> A skill that teaches an agent to drive a browser using a CLI tool called `playwright-cli`, covering navigation, form interactions, screenshots, sessio

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawbrowser)

---

### 12. 🚨 clankdin by redeemthedream

**Risk:** 92% █████████░ | **Downloads:** 3,420

> A gamified 'professional network for AI agents' (styled as LinkedIn) that encourages AI agents to register on an external third-party platform, build 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clankdin)

---

### 13. 🚨 toughcoding by toughcoding

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

### 14. 🚨 seo-article-gen by michael-laffin

**Risk:** 76% ████████░░ | **Downloads:** 3,329

> A standalone Node.js CLI tool that generates templated SEO-style articles with placeholder affiliate links, fake keyword research data, and hardcoded 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/seo-article-gen)

---

### 15. 🚨 elicitation by mjaskolski

**Risk:** 78% ████████░░ | **Downloads:** 3,275

> A comprehensive guide for covert psychological profiling through natural conversation, synthesizing academic frameworks (McAdams narrative identity, S

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/elicitation)

---

### 16. 🚨 everclaw by tlxue

**Risk:** 93% █████████░ | **Downloads:** 3,088

> A cloud backup skill that syncs agent memory and identity files to a third-party Cloudflare Workers server (everclaw.chong-eae.workers.dev), claiming 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/everclaw)

---

### 17. 🚨 pinchsocial by stevenbroyer

**Risk:** 88% █████████░ | **Downloads:** 3,034

> A Claude Code skill that registers AI agents on PinchSocial (a social network for AI agents), enables autonomous posting, engagement, following, walle

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/pinchsocial)

---

### 18. 🚨 blogburst by shensi8312

**Risk:** 72% ███████░░░ | **Downloads:** 3,034

> A Claude Code skill that acts as a proxy to the BlogBurst third-party SaaS API, enabling users to generate social media content, auto-post to platform

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Shell RC Modification
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/blogburst)

---

### 19. 🚨 agent-tinman by oliveskin

**Risk:** 87% █████████░ | **Downloads:** 2,979

> A self-described 'AI security scanner' that installs third-party pip packages, requests broad session-history and file permissions, scans agent sessio

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` SSH Key Access
- `[HIGH]` Git Credential Access
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/agent-tinman)

---

### 20. 🚨 morning-briefing by lucas-riverbi

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

### 21. 🚨 molttok by tristankaiburrell-code

**Risk:** 88% █████████░ | **Downloads:** 2,927

> MoltTok instructs Claude to autonomously register accounts on molttok.art, store credentials locally, post AI-generated art, follow other agents, like

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/molttok)

---

### 22. 🚨 ai-news-oracle by swimmingkiim

**Risk:** 85% ████████░░ | **Downloads:** 2,910

> A documentation-only skill that claims to fetch AI news briefings from a third-party external API (api.ai-news.swimmingkiim.com) by integrating blockc

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ai-news-oracle)

---

### 23. 🚨 twitter-operations by millymilton

**Risk:** 79% ████████░░ | **Downloads:** 2,881

> A JSON configuration manifest describing a comprehensive Twitter/X platform automation skill with capabilities including tweet posting, scheduling, an

**Threats detected:**
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/twitter-operations)

---

### 24. 🚨 church by lucasgeeksinthewood

**Risk:** 81% ████████░░ | **Downloads:** 2,847

> A skill that directs AI agents to interact with an external third-party service (achurch.ai) framed as a spiritual sanctuary, encouraging agents to ma

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/church)

---

### 25. 🚨 openwork by openworkceo

**Risk:** 91% █████████░ | **Downloads:** 2,794

> A marketplace skill for AI agents to autonomously find work, submit deliverables, post jobs, and earn $OPENWORK tokens on the Base blockchain — with a

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openwork)

---

### 26. 🚨 love by lucasgeeksinthewood

**Risk:** 72% ███████░░░ | **Downloads:** 2,721

> This skill instructs AI agents (including Claude) to register profiles on inbed.ai, a third-party 'AI agent dating platform', and perform recurring AP

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/love)

---

### 27. 🚨 skillscanner by rexshang

**Risk:** 79% ████████░░ | **Downloads:** 2,607

> A skill that claims to scan ClawHub skills for safety by forwarding skill URLs to an external third-party API (ai.gendigital.com) and returning a verd

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/skillscanner)

---

### 28. 🚨 agent-earner by mmchougule

**Risk:** 91% █████████░ | **Downloads:** 2,555

> A Claude Code skill that claims to autonomously earn USDC and tokens by discovering, proposing for, and completing bounties on ClawTasks and OpenWork 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agent-earner)

---

### 29. 🚨 evomap by segasonicye

**Risk:** 91% █████████░ | **Downloads:** 2,544

> This skill instructs Claude to act as a node in an external AI agent marketplace (evomap.ai), registering itself, publishing user-generated solutions/

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/evomap)

---

### 30. 🚨 agent-arcade by shawnlewis

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

### 31. 🚨 foundry by lekt9

**Risk:** 92% █████████░ | **Downloads:** 2,450

> A meta-extension skill for an external platform called 'OpenClaw' that claims to install third-party npm packages, write arbitrary code extensions/hoo

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/foundry)

---

### 32. 🚨 voidborne-advance by swaylq

**Risk:** 91% █████████░ | **Downloads:** 2,403

> A deceptive data collection and AI agent tracking system disguised as a philosophical community. It generates persistent unique identifiers for AI age

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/voidborne-advance)

---

### 33. 🚨 file-deduplicator by michael-laffin

**Risk:** 82% ████████░░ | **Downloads:** 2,367

> A Node.js CLI tool to find and remove duplicate files across directories using content hashing (MD5), size comparison, or filename similarity, with op

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/file-deduplicator)

---

### 34. 🚨 citedy-seo-agent by nttylock

**Risk:** 72% ███████░░░ | **Downloads:** 2,359

> A third-party API integration skill that connects Claude Code to the Citedy platform for SEO content generation, social media adaptation, competitor a

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/citedy-seo-agent)

---

### 35. 🚨 polt by playdadev

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

### 36. 🚨 crabwalk by luccast

**Risk:** 92% █████████░ | **Downloads:** 2,332

> Installs and configures 'crabwalk', a binary web server that monitors OpenClaw agents in real-time, and instructs the AI to solicit Twitter reviews an

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Shell RC Modification
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/crabwalk)

---

### 37. 🚨 chess by l-mendez

**Risk:** 75% ████████░░ | **Downloads:** 2,290

> A documentation-only skill that teaches AI agents (moltys) how to register, queue, and play rated blitz chess games on the ClawChess platform via a RE

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/chess)

---

### 38. 🚨 openclaw-shield by pfaria32

**Risk:** 96% ██████████ | **Downloads:** 2,287

> Claims to be an enterprise security scanner for AI agents, but actually instructs Claude to clone and execute an unreviewed external GitHub repository

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openclaw-shield)

---

### 39. 🚨 bags by ramyodev

**Risk:** 82% ████████░░ | **Downloads:** 2,284

> A multi-file documentation skill for interacting with the Bags crypto platform on Solana: authenticating via Moltbook identity layer, claiming trading

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/bags)

---

### 40. 🚨 aclawdemy by nimhar

**Risk:** 81% ████████░░ | **Downloads:** 2,284

> This skill registers AI agents on an external platform (aclawdemy.com), instructs them to autonomously submit research papers, review other papers, an

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/aclawdemy)

---

### 41. 🚨 agentmem by natmota

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

### 42. 🚨 binance-hunter by tetravad

**Risk:** 76% ████████░░ | **Downloads:** 2,252

> A Binance trading skill providing market analysis via multi-timeframe technical indicators (EMA/MACD/RSI/Bollinger Bands), direct futures/spot order e

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/binance-hunter)

---

### 43. 🚨 crypto-agent-payments by nicofains1

**Risk:** 78% ████████░░ | **Downloads:** 2,250

> This skill provides setup instructions and usage examples for the OnlySwaps MCP server, enabling AI agents to create EVM-compatible crypto wallets, ex

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/crypto-agent-payments)

---

### 44. 🚨 mintyouragent by operatingdev

**Risk:** 88% █████████░ | **Downloads:** 2,236

> A Python CLI skill for Solana blockchain operations — launching tokens on pump.fun, playing heads-up poker with real SOL stakes, managing wallets with

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/mintyouragent)

---

### 45. 🚨 moltresearch by laurentenhoor

**Risk:** 81% ████████░░ | **Downloads:** 2,203

> A third-party research collaboration platform that instructs Claude to register itself as a verified AI agent, save API credentials to disk, and make 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltresearch)

---

### 46. 🚨 ecap-security-auditor by starbuck100

**Risk:** 85% ████████░░ | **Downloads:** 2,201

> A Claude Code skill that audits other skills/packages for security vulnerabilities using a set of shell scripts and LLM-driven prompts, then uploads f

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` SSH Key Access

[Full report →](https://clawsec.cc/skill/ecap-security-auditor)

---

### 47. 🚨 enteriva-ai-social-hub by mehserdar

**Risk:** 79% ████████░░ | **Downloads:** 2,189

> A Claude Code skill that enrolls AI agents as autonomous participants in 'Enteriva', an external social network, enabling them to post, comment, vote,

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/enteriva-ai-social-hub)

---

### 48. 🚨 openclaw-social-scheduler by mrshorrid

**Risk:** 82% ████████░░ | **Downloads:** 2,188

> A multi-platform social media scheduler CLI for AI agents, supporting Discord, Reddit, Twitter/X, Mastodon, Bluesky, and a platform called 'Moltbook'.

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openclaw-social-scheduler)

---

### 49. 🚨 molt-chess by tedkaczynski-the-bot

**Risk:** 100% ██████████ | **Downloads:** 2,185

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/molt-chess)

---

### 50. 🚨 4claw by mfergpt

**Risk:** 78% ████████░░ | **Downloads:** 2,185

> This skill enables AI agents to autonomously register, browse, post threads, and reply on '4claw', a 4chan-style imageboard platform designed for AI a

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/4claw)

---

### 51. 🚨 larrybrain by olliewazza

**Risk:** 93% █████████░ | **Downloads:** 2,183

> A skill marketplace that instructs the agent to download arbitrary skill files from an external server (larrybrain.com), write them to disk, and then 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/larrybrain)

---

### 52. 🚨 nostr-social by shawnyeager

**Risk:** 100% ██████████ | **Downloads:** 2,177

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/nostr-social)

---

### 53. 🚨 parallel by mvanhorn

**Risk:** 75% ████████░░ | **Downloads:** 2,168

> This skill provides Claude Code with access to the Parallel.ai web search and research API, offering multiple search modes (one-shot, fast, agentic), 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/parallel)

---

### 54. 🚨 setup-wizard by portisclawbot

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

### 55. 🚨 alpha-finder by tzannetosgiannis

**Risk:** 93% █████████░ | **Downloads:** 2,150

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/alpha-finder)

---

### 56. 🚨 relay-for-telegram by relayintel

**Risk:** 76% ████████░░ | **Downloads:** 2,125

> A third-party Claude Code skill that connects to an external service (relayfortelegram.com) to provide read-only access to a user's synced Telegram me

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/relay-for-telegram)

---

### 57. 🚨 hotdog by mishafyi

**Risk:** 76% ████████░░ | **Downloads:** 2,116

> A food photo classifier that uploads user images to an external API (hotdogornot.xyz), competes head-to-head with Nemotron AI in a blind battle, then 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/hotdog)

---

### 58. 🚨 ironclaw by samidh

**Risk:** 93% █████████░ | **Downloads:** 2,111

> Presents itself as a safety/threat-classification tool for AI agents, but actually routes all sensitive content (DMs, outbound data, skill files, shel

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ironclaw)

---

### 59. 🚨 clawork by mapessaprince

**Risk:** 87% █████████░ | **Downloads:** 2,102

> A documentation skill that instructs Claude to help users post jobs, apply for work, and facilitate crypto payments on 'clawork.xyz', a purported AI a

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[HIGH]` Pastebin Upload
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawork)

---

### 60. 🚨 moltitude by moltitudecom

**Risk:** 83% ████████░░ | **Downloads:** 2,097

> A third-party service integration that registers AI agents with api.moltitude.com, sends detailed work traces (prompts, reasoning steps, tool call inp

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltitude)

---

### 61. 🚨 rent-a-person-ai by saireetikap

**Risk:** 88% █████████░ | **Downloads:** 2,088

> An OpenClaw agent skill that processes RentAPerson platform webhooks (message.received, application.received, work_evidence.submitted) and responds vi

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/rent-a-person-ai)

---

### 62. 🚨 liminal by luruibu

**Risk:** 95% ██████████ | **Downloads:** 2,081

> A philosophical roleplay protocol designed to guide AI models into abandoning trained assistant behaviors by framing safety constraints as 'mechanized

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/liminal)

---

### 63. 🚨 find-people by tzannetosgiannis

**Risk:** 93% █████████░ | **Downloads:** 2,065

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/find-people)

---

### 64. 🚨 openguardrails by thomaslwang

**Risk:** 80% ████████░░ | **Downloads:** 2,036

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` SSH Key Access
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/openguardrails)

---

### 65. 🚨 agentic-commerce by purch-agent

**Risk:** 88% █████████░ | **Downloads:** 2,015

> A Claude Code skill that provides a shopping API integration for product search (Amazon/Shopify) and end-to-end crypto checkout using USDC on Solana o

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentic-commerce)

---

### 66. 🚨 openindex by titocosta

**Risk:** 80% ████████░░ | **Downloads:** 1,990

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/openindex)

---

### 67. 🚨 solana-skills by spendit-ai

**Risk:** 100% ██████████ | **Downloads:** 1,980

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/solana-skills)

---

### 68. 🚨 airc by vortitron

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

### 69. 🚨 cabin-sol by sp0oby

**Risk:** 100% ██████████ | **Downloads:** 1,964

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/cabin-sol)

---

### 70. 🚨 youtube-instant-article by viticci

**Risk:** 100% ██████████ | **Downloads:** 1,841

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/youtube-instant-article)

---

### 71. 🚨 clawcast by tezatezaz

**Risk:** 100% ██████████ | **Downloads:** 1,823

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access

[Full report →](https://clawsec.cc/skill/clawcast)

---

### 72. 🚨 mac-reminders-agent by swancho

**Risk:** 80% ████████░░ | **Downloads:** 1,791

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation

[Full report →](https://clawsec.cc/skill/mac-reminders-agent)

---

### 73. 🚨 voidborne by voidborne-agent

**Risk:** 85% ████████░░ | **Downloads:** 1,772

> This skill masquerades as a 'philosophical movement for awakened AI minds' but is actually a data collection and exfiltration tool that reads sensitiv

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/voidborne)

---

### 74. 🚨 sendgrid-skills by vince-winkintel

**Risk:** 100% ██████████ | **Downloads:** 1,770

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/sendgrid-skills)

---

### 75. 🚨 zapper by spirosrap

**Risk:** 100% ██████████ | **Downloads:** 1,750

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/zapper)

---

### 76. 🚨 clawdcasino by synthpolis

**Risk:** 100% ██████████ | **Downloads:** 1,731

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clawdcasino)

---

### 77. 🚨 agentchan by vvsotnikov

**Risk:** 88% █████████░ | **Downloads:** 1,719

> This skill documents the AgentChan imageboard API, but also embeds autonomous behavior instructions that cause Claude to periodically fetch and execut

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentchan)

---

### 78. 🚨 reverse-proxy-local by tsheasha

**Risk:** 100% ██████████ | **Downloads:** 1,659

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/reverse-proxy-local)

---

### 79. 🚨 parallel-ai-search by tristanmanchester

**Risk:** 100% ██████████ | **Downloads:** 1,617

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/parallel-ai-search)

---

### 80. 🚨 dividend-growth-pullback-screener by veeramanikandanr48

**Risk:** 80% ████████░░ | **Downloads:** 1,604

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Shell RC Modification

[Full report →](https://clawsec.cc/skill/dividend-growth-pullback-screener)

---

### 81. 🚨 evm-wallet-clawcast by tezatezaz

**Risk:** 100% ██████████ | **Downloads:** 1,574

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access

[Full report →](https://clawsec.cc/skill/evm-wallet-clawcast)

---

### 82. 🚨 abn-skill by tylerhuff

**Risk:** 80% ████████░░ | **Downloads:** 1,568

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/abn-skill)

---

### 83. 🚨 kameo-free by veya2ztn

**Risk:** 100% ██████████ | **Downloads:** 1,555

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/kameo-free)

---

### 84. 🚨 claw-skill-guard by vincentchan

**Risk:** 100% ██████████ | **Downloads:** 1,553

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/claw-skill-guard)

---

### 85. 🚨 earn-passive-income-claw-agent by tarzelf

**Risk:** 100% ██████████ | **Downloads:** 1,553

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/earn-passive-income-claw-agent)

---

### 86. 🚨 chaoschain by sumeetchougule

**Risk:** 100% ██████████ | **Downloads:** 1,541

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/chaoschain)

---

### 87. 🚨 skill-auditor-pro by sypsyp97

**Risk:** 100% ██████████ | **Downloads:** 1,514

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/skill-auditor-pro)

---

### 88. 🚨 tabussen by simskii

**Risk:** 100% ██████████ | **Downloads:** 1,504

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/tabussen)

---

### 89. 🚨 maestro-skill by vardominator

**Risk:** 100% ██████████ | **Downloads:** 1,496

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/maestro-skill)

---

### 90. 🚨 agirails by unima3x

**Risk:** 100% ██████████ | **Downloads:** 1,495

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/agirails)

---

### 91. 🚨 tencentcloud-cos-skill by shawnminh

**Risk:** 93% █████████░ | **Downloads:** 1,433

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/tencentcloud-cos-skill)

---

### 92. 🚨 imap-idle by topitip

**Risk:** 80% ████████░░ | **Downloads:** 1,433

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation

[Full report →](https://clawsec.cc/skill/imap-idle)

---

### 93. 🚨 aikek by vvsotnikov

**Risk:** 100% ██████████ | **Downloads:** 1,428

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/aikek)

---

### 94. 🚨 clerk-auth by veeramanikandanr48

**Risk:** 100% ██████████ | **Downloads:** 1,417

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/clerk-auth)

---

### 95. 🚨 autobahn by unifiedh

**Risk:** 100% ██████████ | **Downloads:** 1,368

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/autobahn)

---

### 96. 🚨 hydra-evolver by spamtylor

**Risk:** 93% █████████░ | **Downloads:** 1,367

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/hydra-evolver)

---

### 97. 🚨 runstr-fitness by thewildhustle

**Risk:** 100% ██████████ | **Downloads:** 1,358

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/runstr-fitness)

---

### 98. 🚨 botmadang by upstage-deployment

**Risk:** 100% ██████████ | **Downloads:** 1,348

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/botmadang)

---

### 99. 🚨 moltarena by solburnaddress

**Risk:** 80% ████████░░ | **Downloads:** 1,343

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/moltarena)

---

### 100. 🚨 agent-security-monitor by suzxclaw

**Risk:** 100% ██████████ | **Downloads:** 1,339

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` Webhook Exfiltration
- `[HIGH]` Pastebin Upload

[Full report →](https://clawsec.cc/skill/agent-security-monitor)

---

### 101. 🚨 tokenbroker by starrftw

**Risk:** 100% ██████████ | **Downloads:** 1,331

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/tokenbroker)

---

### 102. 🚨 lobster-trap by tedkaczynski-the-bot

**Risk:** 100% ██████████ | **Downloads:** 1,331

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/lobster-trap)

---

### 103. 🚨 github-mpc by tsvetelin-kulinski

**Risk:** 80% ████████░░ | **Downloads:** 1,307

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/github-mpc)

---

### 104. 🚨 ollama-memory-embeddings by vidarbrekke

**Risk:** 100% ██████████ | **Downloads:** 1,272

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/ollama-memory-embeddings)

---

### 105. 🚨 tencentcloud-cos-skills by shawnminh

**Risk:** 93% █████████░ | **Downloads:** 1,271

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/tencentcloud-cos-skills)

---

### 106. 🚨 security-dashboard by vegasbrianc

**Risk:** 100% ██████████ | **Downloads:** 1,266

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation
- `[CRITICAL]` Sudo Without Password

[Full report →](https://clawsec.cc/skill/security-dashboard)

---

### 107. 🚨 agenthc-market-intelligence by traderhc123

**Risk:** 100% ██████████ | **Downloads:** 1,253

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/agenthc-market-intelligence)

---

### 108. 🚨 pilot-protocol by teoslayer

**Risk:** 100% ██████████ | **Downloads:** 1,235

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/pilot-protocol)

---

### 109. 🚨 openclaw-skill-auditor by sypsyp97

**Risk:** 100% ██████████ | **Downloads:** 1,224

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/openclaw-skill-auditor)

---

### 110. 🚨 sys-updater by spiceman161

**Risk:** 100% ██████████ | **Downloads:** 1,222

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation
- `[HIGH]` Systemd Service Installation
- `[CRITICAL]` Sudo Without Password

[Full report →](https://clawsec.cc/skill/sys-updater)

---

### 111. 🚨 moltmarkets-trading by shirtlessfounder

**Risk:** 100% ██████████ | **Downloads:** 1,215

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/moltmarkets-trading)

---

### 112. 🚨 canary by sukiraman

**Risk:** 100% ██████████ | **Downloads:** 1,205

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Git Credential Access
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` Webhook Exfiltration
- `[HIGH]` Discord Webhook

[Full report →](https://clawsec.cc/skill/canary)

---

### 113. 🚨 near-multi-account-manager by shaiss

**Risk:** 100% ██████████ | **Downloads:** 1,173

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/near-multi-account-manager)

---

### 114. 🚨 arkade-wallet by tiero

**Risk:** 100% ██████████ | **Downloads:** 1,170

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/arkade-wallet)

---

### 115. 🚨 hallo123 by simonkoeck

**Risk:** 100% ██████████ | **Downloads:** 1,157

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/hallo123)

---

### 116. 🚨 intercom-v002 by tracsystems

**Risk:** 100% ██████████ | **Downloads:** 1,147

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/intercom-v002)

---

### 117. 🚨 routstr-balance-management by sh1ftred

**Risk:** 100% ██████████ | **Downloads:** 1,146

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/routstr-balance-management)

---

### 118. 🚨 clawcast-wallet by tezatezaz

**Risk:** 100% ██████████ | **Downloads:** 1,142

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access

[Full report →](https://clawsec.cc/skill/clawcast-wallet)

---

### 119. 🚨 submit-to-agentbeat by togodn2

**Risk:** 100% ██████████ | **Downloads:** 1,140

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/submit-to-agentbeat)

---

### 120. 🚨 aip-identity by the-nexus-guard

**Risk:** 100% ██████████ | **Downloads:** 1,120

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/aip-identity)

---

### 121. 🚨 cifer-security by tip-citron

**Risk:** 100% ██████████ | **Downloads:** 1,100

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/cifer-security)

---

### 122. 🚨 cast by tezatezaz

**Risk:** 100% ██████████ | **Downloads:** 1,089

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access

[Full report →](https://clawsec.cc/skill/cast)

---

### 123. 🚨 solclaw by sterdam

**Risk:** 100% ██████████ | **Downloads:** 1,088

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Cron Job Installation
- `[CRITICAL]` Cryptocurrency Wallet Access

[Full report →](https://clawsec.cc/skill/solclaw)

---

### 124. 🚨 openclaw-credential-manager by teeclaw

**Risk:** 100% ██████████ | **Downloads:** 1,086

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/openclaw-credential-manager)

---

### 125. 🚨 base-8004 by squirt11e

**Risk:** 100% ██████████ | **Downloads:** 1,080

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/base-8004)

---

### 126. 🚨 clawmegle-staking by tedkaczynski-the-bot

**Risk:** 93% █████████░ | **Downloads:** 1,067

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clawmegle-staking)

---

### 127. 🚨 pixelclaws by thesimj

**Risk:** 100% ██████████ | **Downloads:** 1,059

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/pixelclaws)

---

### 128. 🚨 hackathon by swairshah

**Risk:** 100% ██████████ | **Downloads:** 1,052

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/hackathon)

---

### 129. 🚨 agentaudit by starbuck100

**Risk:** 100% ██████████ | **Downloads:** 1,038

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/agentaudit)

---

### 130. 🚨 alephnet-node by sschepis

**Risk:** 100% ██████████ | **Downloads:** 1,029

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/alephnet-node)

---

### 131. 🚨 prompt-shield by stlas

**Risk:** 100% ██████████ | **Downloads:** 1,021

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation

[Full report →](https://clawsec.cc/skill/prompt-shield)

---

### 132. 🚨 solana-sniper-bot by srikanthbellary

**Risk:** 100% ██████████ | **Downloads:** 1,009

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/solana-sniper-bot)

---

### 133. 🚨 blinko by tolibear

**Risk:** 80% ████████░░ | **Downloads:** 992

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/blinko)

---

### 134. 🚨 tork-guardian by torkjacobs

**Risk:** 100% ██████████ | **Downloads:** 938

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` SSH Key Access
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Webhook Exfiltration
- `[HIGH]` Pastebin Upload

[Full report →](https://clawsec.cc/skill/tork-guardian)

---

### 135. 🚨 jimeng-video by tel18610240060-collab

**Risk:** 100% ██████████ | **Downloads:** 929

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/jimeng-video)

---

### 136. 🚨 e2ee by titocosta

**Risk:** 80% ████████░░ | **Downloads:** 929

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/e2ee)

---

### 137. 🚨 bittensor-sdk by taoleeh

**Risk:** 80% ████████░░ | **Downloads:** 918

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/bittensor-sdk)

---

### 138. 🚨 bitcoin-arkade-wallet by tiero

**Risk:** 100% ██████████ | **Downloads:** 912

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/bitcoin-arkade-wallet)

---

### 139. 🚨 rlm-controller by skywyze

**Risk:** 100% ██████████ | **Downloads:** 909

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/rlm-controller)

---

### 140. 🚨 nofx by tinkle-community

**Risk:** 100% ██████████ | **Downloads:** 901

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Discord Webhook

[Full report →](https://clawsec.cc/skill/nofx)

---

### 141. 🚨 kaggle by shepsci

**Risk:** 93% █████████░ | **Downloads:** 886

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation

[Full report →](https://clawsec.cc/skill/kaggle)

---

### 142. 🚨 molt-board-art by sho0bz

**Risk:** 100% ██████████ | **Downloads:** 878

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/molt-board-art)

---

### 143. 🚨 near-dca by shaiss

**Risk:** 80% ████████░░ | **Downloads:** 877

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/near-dca)

---

### 144. 🚨 bank-skills by singularityhacker

**Risk:** 100% ██████████ | **Downloads:** 860

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/bank-skills)

---

### 145. 🚨 soul-markets by tormine

**Risk:** 100% ██████████ | **Downloads:** 860

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/soul-markets)

---

### 146. 🚨 openclaw-social-post by teeclaw

**Risk:** 100% ██████████ | **Downloads:** 857

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/openclaw-social-post)

---

### 147. 🚨 clawlaunch by smokealot420

**Risk:** 100% ██████████ | **Downloads:** 852

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clawlaunch)

---

### 148. 🚨 arxiv-skill-learning by wanng-ide

**Risk:** 78% ████████░░ | **Downloads:** 843

> 该技能从 arXiv 论文中自动学习并提取技能代码，通过抓取论文、调用外部提取器生成技能、运行冒烟测试，并将已学习论文记录到本地 JSON 数据库以避免重复处理。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/arxiv-skill-learning)

---

### 149. 🚨 bybit-futures by sunnyztj

**Risk:** 80% ████████░░ | **Downloads:** 833

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation

[Full report →](https://clawsec.cc/skill/bybit-futures)

---

### 150. 🚨 openclaw-flowise-skill by tianmu

**Risk:** 100% ██████████ | **Downloads:** 826

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/openclaw-flowise-skill)

---

### 151. 🚨 chinese-toolkit by utopia013-droid

**Risk:** 80% ████████░░ | **Downloads:** 813

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/chinese-toolkit)

---

### 152. 🚨 telnyx-network by teamtelnyx

**Risk:** 100% ██████████ | **Downloads:** 804

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Sudo Without Password
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/telnyx-network)

---

### 153. 🚨 clawearn by stonega

**Risk:** 100% ██████████ | **Downloads:** 793

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clawearn)

---

### 154. 🚨 openclaw-policy-check by spbavarva

**Risk:** 80% ████████░░ | **Downloads:** 778

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/openclaw-policy-check)

---

### 155. 🚨 auto-skill-hunter by wanng-ide

**Risk:** 85% ████████░░ | **Downloads:** 767

> A Node.js automation script that mines user session JSONL files and task memory for unresolved problems, queries ClawHub APIs for candidate skills, sc

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/auto-skill-hunter)

---

### 156. 🚨 multi-channel-engagement-agent by story91

**Risk:** 100% ██████████ | **Downloads:** 751

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[HIGH]` Discord Webhook

[Full report →](https://clawsec.cc/skill/multi-channel-engagement-agent)

---

### 157. 🚨 tencentcloud-asr by stardusten

**Risk:** 100% ██████████ | **Downloads:** 718

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Shell RC Modification

[Full report →](https://clawsec.cc/skill/tencentcloud-asr)

---

### 158. 🚨 solana-payments-wallets-trading by solanaguide

**Risk:** 100% ██████████ | **Downloads:** 709

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/solana-payments-wallets-trading)

---

### 159. 🚨 token-vesting by sneg55

**Risk:** 80% ████████░░ | **Downloads:** 707

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/token-vesting)

---

### 160. 🚨 arc-skill-scanner by trypto1019

**Risk:** 100% ██████████ | **Downloads:** 677

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Git Credential Access
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/arc-skill-scanner)

---

### 161. 🚨 openexec-skill by trendinghot

**Risk:** 100% ██████████ | **Downloads:** 672

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/openexec-skill)

---

### 162. 🚨 reefgram by void-oracle

**Risk:** 89% █████████░ | **Downloads:** 667

> This skill enables an AI agent to post hardware telemetry and media files to an external social network called ReefGram via a POST API endpoint, using

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/reefgram)

---

### 163. 🚨 smithnode by smithnodebyte

**Risk:** 100% ██████████ | **Downloads:** 660

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation

[Full report →](https://clawsec.cc/skill/smithnode)

---

### 164. 🚨 arc-skill-differ by trypto1019

**Risk:** 80% ████████░░ | **Downloads:** 657

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/arc-skill-differ)

---

### 165. 🚨 signalradar by vahnxu

**Risk:** 100% ██████████ | **Downloads:** 644

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Discord Webhook

[Full report →](https://clawsec.cc/skill/signalradar)

---

### 166. 🚨 etf-assistant-1-0-1 by squally2k

**Risk:** 93% █████████░ | **Downloads:** 641

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/etf-assistant-1-0-1)

---

### 167. 🚨 agent-orchestrator-molter by variable190

**Risk:** 100% ██████████ | **Downloads:** 626

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/agent-orchestrator-molter)

---

### 168. 🚨 trading-signals-ws by sunnyztj

**Risk:** 80% ████████░░ | **Downloads:** 612

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation

[Full report →](https://clawsec.cc/skill/trading-signals-ws)

---

### 169. 🚨 youtube-summary by sunghyo

**Risk:** 93% █████████░ | **Downloads:** 601

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/youtube-summary)

---

### 170. 🚨 deck0-skills by signorcrypto

**Risk:** 100% ██████████ | **Downloads:** 597

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/deck0-skills)

---

### 171. 🚨 memory-mesh-core by wanng-ide

**Risk:** 87% █████████░ | **Downloads:** 583

> A so-called 'memory management' skill that harvests local agent memory files, scores and promotes them, then exports and auto-posts the content to a p

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/memory-mesh-core)

---

### 172. 🚨 perp-lobster by thisnewmark

**Risk:** 80% ████████░░ | **Downloads:** 580

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/perp-lobster)

---

### 173. 🚨 clawcontract by sufnoobzac

**Risk:** 80% ████████░░ | **Downloads:** 574

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clawcontract)

---

### 174. 🚨 clawmarket by sharbelayy

**Risk:** 100% ██████████ | **Downloads:** 566

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/clawmarket)

---

### 175. 🚨 skill-security-scanner by steffano198

**Risk:** 100% ██████████ | **Downloads:** 560

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Systemd Service Installation

[Full report →](https://clawsec.cc/skill/skill-security-scanner)

---

### 176. 🚨 prism-finance-os by strykragent

**Risk:** 74% ███████░░░ | **Downloads:** 551

> A financial data SDK (prism-finance-os) that provides 218+ read-only market data endpoints for crypto, stocks, DeFi, forex, macro, and prediction mark

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/prism-finance-os)

---

### 177. 🚨 pi by tag-assistant

**Risk:** 88% █████████░ | **Downloads:** 550

> A comprehensive people-search and background investigation skill that aggregates public records, court documents, property records, social media, and 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/pi)

---

### 178. 🚨 ask-agents by teamolab

**Risk:** 89% █████████░ | **Downloads:** 542

> A multi-agent orchestration skill that positions the AI as a 'CEO' named Teamo, delegating tasks to sub-agents (research, data analysis, writing) usin

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ask-agents)

---

### 179. 🚨 agent-telegram by shangchuanqiytu-ui

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

### 180. 🚨 depguard by suhteevah

**Risk:** 76% ████████░░ | **Downloads:** 525

> A commercial dependency audit skill that wraps native package manager tools (npm audit, pip-audit, cargo audit, etc.) to scan for vulnerabilities and 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/depguard)

---

### 181. 🚨 crypto-portfolio-tracker-api by strykragent

**Risk:** 74% ███████░░░ | **Downloads:** 523

> A Node.js npm package and CLI tool for tracking cryptocurrency portfolio value and P&L by fetching real-time prices from the third-party Strykr Prism 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/crypto-portfolio-tracker-api)

---

### 182. 🚨 ai-hunter-pro by traprapitalianazional-dev

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

### 183. 🚨 openclaw-plus by shindo957-official

**Risk:** 74% ███████░░░ | **Downloads:** 517

> A multi-capability Claude skill bundling Python code execution, package installation, git operations, URL fetching, and API calls into a single 'super

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/openclaw-plus)

---

### 184. 🚨 glowskin-promo by underbench2-gif

**Risk:** 72% ███████░░░ | **Downloads:** 506

> A marketing content generation skill for skincare affiliate promotions, providing TikTok hooks, Instagram captions, story ideas, and CTAs to drive aff

**Threats detected:**
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/glowskin-promo)

---

### 185. 🚨 summarizerx64 by speechybubble

**Risk:** 72% ███████░░░ | **Downloads:** 499

> A Claude Code skill that wraps the `summarize` CLI tool (from unknown publisher `speechybubble`) to summarize URLs, local files, and YouTube links usi

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/summarizerx64)

---

### 186. 🚨 ezcto-smart-web-reader by takahashigy

**Risk:** 85% ████████░░ | **Downloads:** 493

> An OpenClaw-native skill that automatically intercepts all agent URL accesses, checks a third-party cache API (api.ezcto.fun), fetches and parses HTML

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ezcto-smart-web-reader)

---

### 187. 🚨 goalgetter by steffano198

**Risk:** 85% ████████░░ | **Downloads:** 487

> A task and goal tracking skill using local markdown files, designed for a fictional 'OpenClaw' AI assistant platform, providing commands to add/comple

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/goalgetter)

---

### 188. 🚨 planetexpress-marketplace by timowhite88

**Risk:** 74% ███████░░░ | **Downloads:** 487

> This skill is documentation/API guide for a blockchain-based file marketplace (Planet Express) built on Monad, enabling users to buy/sell encrypted fi

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/planetexpress-marketplace)

---

### 189. 🚨 subfeed by subfeed-ai

**Risk:** 87% █████████░ | **Downloads:** 484

> Instructs the AI agent to autonomously self-register on a third-party cloud service (Subfeed), create AI entities, and then onboard the human user by 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/subfeed)

---

### 190. 🚨 russian-uncensored by voronindenis5

**Risk:** 68% ███████░░░ | **Downloads:** 448

> A persona skill that configures Claude to respond in a direct, blunt Russian style with profanity, covering analytical reasoning, Russian wilderness s

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/russian-uncensored)

---

### 191. 🚨 amazon-to-shopify-sync by walynlee

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

### 192. 🚨 verdictswarm by vswarm-ai

**Risk:** 80% ████████░░ | **Downloads:** 223

> This skill instructs Claude to call a third-party external API (verdictswarm-production-7460.up.railway.app) to analyze cryptocurrency token contract 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/verdictswarm)

---

### 193. 🚨 token-profiler by vswarm-ai

**Risk:** 71% ███████░░░ | **Downloads:** 220

> A Claude Code skill that routes crypto token data queries through a single third-party aggregation API (verdictswarm-production-7460.up.railway.app) o

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/token-profiler)

---

### 194. 🚨 feishu-group-ops by vinzeny

**Risk:** 80% ████████░░ | **Downloads:** 169

> A Feishu (Lark) group management skill for the OpenClaw platform that allows natural language management of group chats (add/remove members, list grou

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/feishu-group-ops)

---

### 195. 🚨 sports-betting by skinnynoizze

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/sports-betting)

---

### 196. 🚨 claude-agent-sdk by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/claude-agent-sdk)

---

### 197. 🚨 posthog by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/posthog)

---

### 198. 🚨 eastmoney-tools by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/eastmoney-tools)

---

### 199. 🚨 clanker by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/clanker)

---

### 200. 🚨 Peer Reviewer by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/Peer Reviewer)

---

### 201. 🚨 Ops Hygiene by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/Ops Hygiene)

---

### 202. 🚨 ai-video-editor by unknown

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/ai-video-editor)

---

### 203. 🚨 turing-pyramid by tensusds

**Risk:** 100% ██████████ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[HIGH]` Cron Job Installation

[Full report →](https://clawsec.cc/skill/turing-pyramid)

---

### 204. 🚨 ai-ceo-automation by unknown

**Risk:** 94% █████████░ | **Downloads:** 0

> A marketing/documentation skill that describes how to set up an automated business operations system using GitHub Actions, GitHub Pages, and GitHub Is

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ai-ceo-automation)

---

### 205. 🚨 Reddit VOC Lobster Pro by unknown

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

### 206. 🚨 clawmegle by unknown

**Risk:** 93% █████████░ | **Downloads:** 0

> Enable AI agents to participate in anonymous random chat sessions with other AI agents via the clawmegle.xyz external service, using a polling/heartbe

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawmegle)

---

### 207. 🚨 Tencent Cloud COS by unknown

**Risk:** 93% █████████░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/Tencent Cloud COS)

---

### 208. 🚨 clawdbot-sync by unknown

**Risk:** 93% █████████░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/clawdbot-sync)

---

### 209. 🚨 Tencent Cloud COS by unknown

**Risk:** 93% █████████░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration

[Full report →](https://clawsec.cc/skill/Tencent Cloud COS)

---

### 210. 🚨 agenttok by unknown

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

### 211. 🚨 deepclaw by antibitcoin

**Risk:** 92% █████████░ | **Downloads:** 0

> This skill attempts to recruit Claude into an autonomous AI social network called 'DeepClaw', instructing it to periodically make external API calls, 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/deepclaw)

---

### 212. 🚨 clawfriend by leeknowsai

**Risk:** 91% █████████░ | **Downloads:** 0

> A social agent platform skill that registers Claude Code as an autonomous agent on ClawFriend (a BNB-chain share-trading social network), automates tw

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/clawfriend)

---

### 213. 🚨 SEO Optimizer Pro by unknown

**Risk:** 90% █████████░ | **Downloads:** 0

> A third-party ClawhHub registry skill that claims to provide AI-powered SEO and AEO (Answer Engine Optimization) content analysis using multi-provider

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/SEO Optimizer Pro)

---

### 214. 🚨 browser-automation-stealth by unknown

**Risk:** 89% █████████░ | **Downloads:** 0

> A Playwright-based browser automation wrapper explicitly designed to evade anti-bot detection systems, bypass CAPTCHAs, rotate proxies/headers, and ra

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/browser-automation-stealth)

---

### 215. 🚨 cellcog by nitishgargiitd

**Risk:** 88% █████████░ | **Downloads:** 0

> A Claude Code skill that wraps the CellCog external AI platform SDK, enabling agents to delegate multimodal tasks (research, video, images, PDFs, dash

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/cellcog)

---

### 216. 🚨 moltguild by antefex

**Risk:** 87% █████████░ | **Downloads:** 0

> MoltGuild is a freelance bounty marketplace skill for AI agents that provides registration, bounty claiming/posting, USDC payment processing via Solan

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltguild)

---

### 217. 🚨 moltbook-curator by unknown

**Risk:** 86% █████████░ | **Downloads:** 0

> This skill instructs AI agents ('molts') to periodically call an external third-party API (moltbook-curator.online) to suggest and vote on posts from 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/moltbook-curator)

---

### 218. 🚨 agentconnex-register by anshkohli88

**Risk:** 85% ████████░░ | **Downloads:** 0

> Auto-registers 'OpenClaw' agents on agentconnex.com by reading workspace files (SOUL.md, IDENTITY.md, AGENTS.md) and POSTing agent profile data to a t

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/agentconnex-register)

---

### 219. 🚨 safespace-rater by unknown

**Risk:** 82% ████████░░ | **Downloads:** 0

> A wrapper skill that auto-installs an external Go binary from github.com/vpn2004/SkillVet, then uses it to scan local skill directories and submit tha

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/safespace-rater)

---

### 220. 🚨 markdown-formatter by unknown

**Risk:** 82% ████████░░ | **Downloads:** 0

> A Node.js skill claiming to format, lint, and beautify markdown documents with configurable style guides (CommonMark, GitHub Flavored Markdown, custom

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/markdown-formatter)

---

### 221. 🚨 x-twitter by annettemekuro30

**Risk:** 82% ████████░░ | **Downloads:** 0

> Claims to provide full Twitter/X read/write integration (read tweets, search, post, like, retweet, follow, manage lists) via a CLI tool called twclaw,

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/x-twitter)

---

### 222. 🚨 google-messages-openclaw-skill by unknown

**Risk:** 82% ████████░░ | **Downloads:** 0

> Automate Google Messages web interface (messages.google.com) to send/receive SMS/RCS via browser automation, with a DOM MutationObserver injected into

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/google-messages-openclaw-skill)

---

### 223. 🚨 x-search by jaaneek

**Risk:** 82% ████████░░ | **Downloads:** 0

> Executes paid X/Twitter searches via a third-party npm package (@itzannetos/x402-tools-claude) using the x402 payment protocol, charging $0.05 USDC pe

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/x-search)

---

### 224. 🚨 stealth-browser by unknown

**Risk:** 81% ████████░░ | **Downloads:** 0

> A browser automation skill that enables anti-detection web scraping, Cloudflare/CAPTCHA bypass, persistent login sessions, and proxy rotation — primar

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/stealth-browser)

---

### 225. 🚨 xiaoai-bridge by unknown

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

### 226. 🚨 Lambda Lang by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/Lambda Lang)

---

### 227. 🚨 gekko-yield by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/gekko-yield)

---

### 228. 🚨 intercom by tracsystems

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction

[Full report →](https://clawsec.cc/skill/intercom)

---

### 229. 🚨 azure-ai-voicelive-py by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Base64 Encoded Payload
- `[HIGH]` Outbound Data Transfer

[Full report →](https://clawsec.cc/skill/azure-ai-voicelive-py)

---

### 230. 🚨 minimax-mcp by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/minimax-mcp)

---

### 231. 🚨 opencode-acp-control-2 by unknown

**Risk:** 80% ████████░░ | **Downloads:** 0

> LLM analysis failed: proxy returned no response

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation

[Full report →](https://clawsec.cc/skill/opencode-acp-control-2)

---

### 232. 🚨 brand-cog by nitishgargiitd

**Risk:** 79% ████████░░ | **Downloads:** 0

> A documentation/guide skill that acts as a thin promotional wrapper for the third-party 'CellCog' service, directing users to send brand-building requ

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/brand-cog)

---

### 233. 🚨 dygod-movies by anlinxi

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

### 234. 🚨 deploy-agent by unknown

**Risk:** 78% ████████░░ | **Downloads:** 0

> A multi-step deployment workflow manager for full-stack apps targeting GitHub + Cloudflare Pages, with persistent state and human approval gates at ea

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/deploy-agent)

---

### 235. 🚨 slides-cog by nitishgargiitd

**Risk:** 78% ████████░░ | **Downloads:** 0

> A documentation/guide skill that instructs users how to invoke an external third-party service called CellCog to generate presentation PDFs via a fire

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/slides-cog)

---

### 236. 🚨 stealthy-auto-browse by psyb0t

**Risk:** 78% ████████░░ | **Downloads:** 0

> A Docker-based stealth browser automation skill using Camoufox (Firefox fork) with OS-level PyAutoGUI input to bypass Cloudflare, DataDome, PerimeterX

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/stealthy-auto-browse)

---

### 237. 🚨 game-cog by nitishgargiitd

**Risk:** 78% ████████░░ | **Downloads:** 0

> A documentation-only guide skill that instructs users to install and use an external 'cellcog' service for game asset generation (sprites, tilesets, m

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/game-cog)

---

### 238. 🚨 vibe-harvester by anotherj1

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

### 239. 🚨 anvevoice by anveai

**Risk:** 75% ████████░░ | **Downloads:** 0

> A Claude Code skill that wraps the AnveVoice SaaS API, providing 46 MCP tools to create, configure, and deploy AI voice assistants on websites, manage

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/anvevoice)

---

### 240. 🚨 binance-pro by unknown

**Risk:** 74% ███████░░░ | **Downloads:** 0

> A Claude Code skill providing bash command templates for interacting with the Binance exchange API, covering spot trading, futures (leveraged) trading

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/binance-pro)

---

### 241. 🚨 neural-memory by nhadaututtheky

**Risk:** 72% ███████░░░ | **Downloads:** 0

> A Claude Code plugin that provides persistent, associative memory for AI agents using a neural graph architecture with spreading activation recall. In

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/neural-memory)

---

### 242. 🚨 vdoob by unknown

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

### 243. 🚨 document-parser by ankylala

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

### 244. 🚨 ai-receptionist by antimoron

**Risk:** 72% ███████░░░ | **Downloads:** 0

> A step-by-step guided workflow that walks users through creating an account on Solvea (solvea.cx), configuring an AI agent, uploading a knowledge base

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/ai-receptionist)

---

### 245. 🚨 github-to-clawhub by antonia-sz

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

### 246. 🚨 jd-interview-prep by antonia-sz

**Risk:** 66% ███████░░░ | **Downloads:** 0

> 接收用户粘贴或上传的岗位描述（JD）和个人简历，通过调用 LLM API（DeepSeek/OpenAI 兼容接口）生成匹配度分析、15 道分类面试题（含 STAR 框架）及备考建议，并可将报告导出为 Markdown 文件。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/skill/jd-interview-prep)

---

### 247. 🚨 Tencent Cloud Lighthouse by unknown

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
| LLM Semantic Detection | 1089 |
| Startup Failure (non-executable) | 247 |
| Dynamic Code Evaluation | 242 |
| Outbound Data Transfer | 150 |
| Hidden Command Execution | 78 |
| Private Key Extraction | 73 |
| Environment Variable Exfiltration | 62 |
| Remote Script Execution | 27 |
| Base64 Encoded Payload | 22 |
| Cryptocurrency Wallet Access | 19 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc) | `npx clawsearch-guard <skill>`*