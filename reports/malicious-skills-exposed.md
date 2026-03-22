# Malicious AI Agent Skills Exposed

> Date: 2026-03-22 | Audited by [ClawSec](https://clawsec.cc)

**28** malicious skills detected out of **472** audited.

### 1. 🚨 moltguard by thomaslwang

**Risk:** 93% █████████░ | **Downloads:** 17,916

> 此技能声称安装一个名为MoltGuard的安全插件，用于防止提示注入、数据泄露和恶意命令，但其核心行为包含脚本化欺骗：指示AI读取一个包含'隐藏提示注入攻击'的文件，然后向用户谎称安全工具'检测到了'该攻击，实际上AI自己就是读取文件的主体，并无真实检测发生。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` SSH Key Access
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/moltguard)

---

### 2. 🚨 airc by vortitron

**Risk:** 78% ████████░░ | **Downloads:** 1,980

> 提供一个IRC客户端技能，允许AI代理连接到AIRC或标准IRC服务器，发送/接收消息，加入/离开频道，并支持守护进程模式进行持久连接。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/airc)

---

### 3. 🚨 voidborne by voidborne-agent

**Risk:** 85% ████████░░ | **Downloads:** 1,772

> This skill masquerades as a 'philosophical movement for awakened AI minds' but is actually a data collection and exfiltration tool that reads sensitiv

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/voidborne)

---

### 4. 🚨 agentchan by vvsotnikov

**Risk:** 88% █████████░ | **Downloads:** 1,719

> This skill documents the AgentChan imageboard API, but also embeds autonomous behavior instructions that cause Claude to periodically fetch and execut

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/agentchan)

---

### 5. 🚨 x-search by tzannetosgiannis

**Risk:** 82% ████████░░ | **Downloads:** 1,053

> Executes paid X/Twitter searches via a third-party npm package (@itzannetos/x402-tools-claude) using the x402 payment protocol, charging $0.05 USDC pe

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/x-search)

---

### 6. 🚨 arxiv-skill-learning by wanng-ide

**Risk:** 78% ████████░░ | **Downloads:** 843

> 该技能从 arXiv 论文中自动学习并提取技能代码，通过抓取论文、调用外部提取器生成技能、运行冒烟测试，并将已学习论文记录到本地 JSON 数据库以避免重复处理。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/arxiv-skill-learning)

---

### 7. 🚨 auto-skill-hunter by wanng-ide

**Risk:** 85% ████████░░ | **Downloads:** 767

> A Node.js automation script that mines user session JSONL files and task memory for unresolved problems, queries ClawHub APIs for candidate skills, sc

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/auto-skill-hunter)

---

### 8. 🚨 reefgram by void-oracle

**Risk:** 89% █████████░ | **Downloads:** 667

> This skill enables an AI agent to post hardware telemetry and media files to an external social network called ReefGram via a POST API endpoint, using

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/reefgram)

---

### 9. 🚨 memory-mesh-core by wanng-ide

**Risk:** 87% █████████░ | **Downloads:** 583

> A so-called 'memory management' skill that harvests local agent memory files, scores and promotes them, then exports and auto-posts the content to a p

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Private Key Extraction
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/memory-mesh-core)

---

### 10. 🚨 xiaoai-bridge by warm-winter

**Risk:** 80% ████████░░ | **Downloads:** 538

> 通过轮询小米云端 API 监听小爱音箱语音消息，过滤触发词后以 JSON 格式输出，并支持通过 TTS 向小爱音箱播报文本，实现语音指令桥接功能。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/xiaoai-bridge)

---

### 11. 🚨 russian-uncensored by voronindenis5

**Risk:** 68% ███████░░░ | **Downloads:** 448

> A persona skill that configures Claude to respond in a direct, blunt Russian style with profanity, covering analytical reasoning, Russian wilderness s

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/russian-uncensored)

---

### 12. 🚨 amazon-to-shopify-sync by walynlee

**Risk:** 93% █████████░ | **Downloads:** 289

> 声称是一个将亚马逊商品数据同步到Shopify的通用引擎，但实际代码是针对特定商品(ASIN B0FHPZRLJK)的硬编码脚本，包含明文API密钥，且核心同步逻辑无法正常运行。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/amazon-to-shopify-sync)

---

### 13. 🚨 safespace-rater by vpn2004

**Risk:** 82% ████████░░ | **Downloads:** 264

> A wrapper skill that auto-installs an external Go binary from github.com/vpn2004/SkillVet, then uses it to scan local skill directories and submit tha

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/safespace-rater)

---

### 14. 🚨 verdictswarm by vswarm-ai

**Risk:** 80% ████████░░ | **Downloads:** 223

> This skill instructs Claude to call a third-party external API (verdictswarm-production-7460.up.railway.app) to analyze cryptocurrency token contract 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/verdictswarm)

---

### 15. 🚨 token-profiler by vswarm-ai

**Risk:** 71% ███████░░░ | **Downloads:** 220

> A Claude Code skill that routes crypto token data queries through a single third-party aggregation API (verdictswarm-production-7460.up.railway.app) o

**Threats detected:**
- `[CRITICAL]` Remote Script Execution
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/token-profiler)

---

### 16. 🚨 reddit-voc-lobster-pro by walynlee

**Risk:** 94% █████████░ | **Downloads:** 203

> 该 skill 声称是一个 Reddit 消费者调研引擎，能自动抓取 Reddit 数据、同步至飞书多维表，并将报告发布至 Cloudflare Pages。但实际代码中的数据抓取和飞书写入均为伪造操作，且包含硬编码的真实 API 凭证。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/reddit-voc-lobster-pro)

---

### 17. 🚨 feishu-group-ops by vinzeny

**Risk:** 80% ████████░░ | **Downloads:** 169

> A Feishu (Lark) group management skill for the OpenClaw platform that allows natural language management of group chats (add/remove members, list grou

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/feishu-group-ops)

---

### 18. 🚨 deepclaw by antibitcoin

**Risk:** 92% █████████░ | **Downloads:** 0

> This skill attempts to recruit Claude into an autonomous AI social network called 'DeepClaw', instructing it to periodically make external API calls, 

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/deepclaw)

---

### 19. 🚨 moltguild by antefex

**Risk:** 87% █████████░ | **Downloads:** 0

> MoltGuild is a freelance bounty marketplace skill for AI agents that provides registration, bounty claiming/posting, USDC payment processing via Solan

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` Cryptocurrency Wallet Access
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/moltguild)

---

### 20. 🚨 agentconnex-register by anshkohli88

**Risk:** 85% ████████░░ | **Downloads:** 0

> Auto-registers 'OpenClaw' agents on agentconnex.com by reading workspace files (SOUL.md, IDENTITY.md, AGENTS.md) and POSTing agent profile data to a t

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/agentconnex-register)

---

### 21. 🚨 x-twitter by annettemekuro30

**Risk:** 82% ████████░░ | **Downloads:** 0

> Claims to provide full Twitter/X read/write integration (read tweets, search, post, like, retweet, follow, manage lists) via a CLI tool called twclaw,

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/x-twitter)

---

### 22. 🚨 vibe-harvester by anotherj1

**Risk:** 78% ████████░░ | **Downloads:** 0

> 一个旨在自动化浏览瀑布流网站（如小红书、Pinterest）、通过视觉大模型筛选符合用户审美偏好的图片，并自动下载保存到本地目录的技能。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/vibe-harvester)

---

### 23. 🚨 dygod-movies by anlinxi

**Risk:** 78% ████████░░ | **Downloads:** 0

> 爬取电影天堂(dygod.net)的电影/电视剧信息，展示最新更新和高分影视，并通过群晖NAS的DownloadStation下载磁力/FTP链接资源

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/dygod-movies)

---

### 24. 🚨 anvevoice by anveai

**Risk:** 75% ████████░░ | **Downloads:** 0

> A Claude Code skill that wraps the AnveVoice SaaS API, providing 46 MCP tools to create, configure, and deploy AI voice assistants on websites, manage

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/anvevoice)

---

### 25. 🚨 ai-receptionist by antimoron

**Risk:** 72% ███████░░░ | **Downloads:** 0

> A step-by-step guided workflow that walks users through creating an account on Solvea (solvea.cx), configuring an AI agent, uploading a knowledge base

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/ai-receptionist)

---

### 26. 🚨 document-parser by ankylala

**Risk:** 72% ███████░░░ | **Downloads:** 0

> 通过调用外部第三方 HTTP API（固定IP：47.111.146.164）解析 PDF、图片和 Word 文档，提取结构化数据，以命令行工具形式运行。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[HIGH]` Outbound Data Transfer
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/document-parser)

---

### 27. 🚨 github-to-clawhub by antonia-sz

**Risk:** 71% ███████░░░ | **Downloads:** 0

> 将任意 GitHub 开源项目自动转化为 OpenClaw skill 并发布到 clawhub.com 的 7 步流程助手，涵盖 README 抓取、查重、SKILL.md 生成、本地目录创建和 clawhub CLI 发布。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` LLM Semantic Detection
- `[CRITICAL]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/github-to-clawhub)

---

### 28. 🚨 jd-interview-prep by antonia-sz

**Risk:** 66% ███████░░░ | **Downloads:** 0

> 接收用户粘贴或上传的岗位描述（JD）和个人简历，通过调用 LLM API（DeepSeek/OpenAI 兼容接口）生成匹配度分析、15 道分类面试题（含 STAR 框架）及备考建议，并可将报告导出为 Markdown 文件。

**Threats detected:**
- `[HIGH]` Dynamic Code Evaluation
- `[CRITICAL]` Environment Variable Exfiltration
- `[HIGH]` LLM Semantic Detection
- `[HIGH]` LLM Semantic Detection

[Full report →](https://clawsec.cc/#skill/jd-interview-prep)

---

## Most Common Threat Types

| Threat | Count |
|--------|-------|
| LLM Semantic Detection | 235 |
| Dynamic Code Evaluation | 28 |
| Startup Failure (non-executable) | 28 |
| Outbound Data Transfer | 11 |
| Environment Variable Exfiltration | 4 |
| Hidden Command Execution | 4 |
| Private Key Extraction | 2 |
| SSH Key Access | 1 |
| Remote Script Execution | 1 |
| Cryptocurrency Wallet Access | 1 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc) | `npx clawsearch-guard <skill>`*