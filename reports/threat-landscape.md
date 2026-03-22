# AI Agent Skill Threat Landscape

> Date: 2026-03-22 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **4396** threats detected across **472** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 190 | 4% |
| HIGH | 1172 | 27% |
| MEDIUM | 838 | 19% |
| LOW | 2196 | 50% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 3222 | LOW |
| Startup Failure (non-executable) | 472 | LOW |
| Dynamic Code Evaluation | 457 | HIGH |
| Outbound Data Transfer | 106 | HIGH |
| Hidden Command Execution | 62 | MEDIUM |
| Environment Variable Exfiltration | 22 | CRITICAL |
| Private Key Extraction | 13 | CRITICAL |
| Remote Script Execution | 7 | CRITICAL |
| Base64 Encoded Payload | 6 | HIGH |
| Cryptocurrency Wallet Access | 6 | CRITICAL |
| Cron Job Installation | 5 | HIGH |
| Systemd Service Installation | 4 | HIGH |
| Shell RC Modification | 4 | HIGH |
| Webhook Data Send | 3 | MEDIUM |
| Obfuscated Code | 3 | MEDIUM |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 315 | 11.2 |
| SUSPICIOUS | 2329 | 10.2 |
| SAFE | 1746 | 8.2 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*