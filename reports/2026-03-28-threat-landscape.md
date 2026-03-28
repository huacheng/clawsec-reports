# AI Agent Skill Threat Landscape

> Date: 2026-03-28 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **13586** threats detected across **1403** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 601 | 4% |
| HIGH | 3725 | 27% |
| MEDIUM | 2664 | 20% |
| LOW | 6596 | 49% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 9870 | LOW |
| Startup Failure (non-executable) | 1402 | LOW |
| Dynamic Code Evaluation | 1353 | HIGH |
| Outbound Data Transfer | 459 | HIGH |
| Hidden Command Execution | 234 | MEDIUM |
| Environment Variable Exfiltration | 60 | CRITICAL |
| Private Key Extraction | 48 | CRITICAL |
| Base64 Encoded Payload | 34 | HIGH |
| Remote Script Execution | 33 | CRITICAL |
| Systemd Service Installation | 14 | HIGH |
| Cron Job Installation | 14 | HIGH |
| Shell RC Modification | 13 | HIGH |
| Obfuscated Code | 12 | MEDIUM |
| Webhook Data Send | 9 | MEDIUM |
| SSH Key Access | 8 | HIGH |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 1146 | 11.7 |
| SUSPICIOUS | 6974 | 10.4 |
| SAFE | 5450 | 8.6 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*