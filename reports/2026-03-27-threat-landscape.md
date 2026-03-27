# AI Agent Skill Threat Landscape

> Date: 2026-03-27 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **16003** threats detected across **2079** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 862 | 5% |
| HIGH | 4936 | 31% |
| MEDIUM | 2987 | 19% |
| LOW | 7218 | 45% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 10253 | LOW |
| Startup Failure (non-executable) | 2079 | LOW |
| Dynamic Code Evaluation | 2023 | HIGH |
| Outbound Data Transfer | 759 | HIGH |
| Hidden Command Execution | 373 | MEDIUM |
| Environment Variable Exfiltration | 115 | CRITICAL |
| Private Key Extraction | 113 | CRITICAL |
| Remote Script Execution | 62 | CRITICAL |
| Base64 Encoded Payload | 52 | HIGH |
| Cryptocurrency Wallet Access | 30 | CRITICAL |
| Cron Job Installation | 27 | HIGH |
| Systemd Service Installation | 22 | HIGH |
| Shell RC Modification | 21 | HIGH |
| Webhook Data Send | 19 | MEDIUM |
| Obfuscated Code | 15 | MEDIUM |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 2073 | 8.4 |
| SUSPICIOUS | 8763 | 7.2 |
| SAFE | 5149 | 8.6 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*