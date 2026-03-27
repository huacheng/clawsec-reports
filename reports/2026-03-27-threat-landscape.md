# AI Agent Skill Threat Landscape

> Date: 2026-03-27 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **11411** threats detected across **1197** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 474 | 4% |
| HIGH | 3089 | 27% |
| MEDIUM | 2210 | 19% |
| LOW | 5638 | 49% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 8274 | LOW |
| Startup Failure (non-executable) | 1196 | LOW |
| Dynamic Code Evaluation | 1156 | HIGH |
| Outbound Data Transfer | 363 | HIGH |
| Hidden Command Execution | 203 | MEDIUM |
| Environment Variable Exfiltration | 49 | CRITICAL |
| Private Key Extraction | 40 | CRITICAL |
| Remote Script Execution | 27 | CRITICAL |
| Base64 Encoded Payload | 27 | HIGH |
| Systemd Service Installation | 13 | HIGH |
| Cron Job Installation | 12 | HIGH |
| Obfuscated Code | 11 | MEDIUM |
| Shell RC Modification | 9 | HIGH |
| Webhook Data Send | 7 | MEDIUM |
| SSH Key Access | 6 | HIGH |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 847 | 11.4 |
| SUSPICIOUS | 5922 | 10.3 |
| SAFE | 4626 | 8.5 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*