# AI Agent Skill Threat Landscape

> Date: 2026-03-27 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **16052** threats detected across **2084** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 863 | 5% |
| HIGH | 4950 | 31% |
| MEDIUM | 2997 | 19% |
| LOW | 7242 | 45% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 10288 | LOW |
| Startup Failure (non-executable) | 2084 | LOW |
| Dynamic Code Evaluation | 2028 | HIGH |
| Outbound Data Transfer | 760 | HIGH |
| Hidden Command Execution | 374 | MEDIUM |
| Environment Variable Exfiltration | 115 | CRITICAL |
| Private Key Extraction | 113 | CRITICAL |
| Remote Script Execution | 62 | CRITICAL |
| Base64 Encoded Payload | 53 | HIGH |
| Cryptocurrency Wallet Access | 30 | CRITICAL |
| Cron Job Installation | 27 | HIGH |
| Systemd Service Installation | 22 | HIGH |
| Shell RC Modification | 21 | HIGH |
| Webhook Data Send | 19 | MEDIUM |
| Obfuscated Code | 16 | MEDIUM |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 2073 | 8.4 |
| SUSPICIOUS | 8805 | 7.2 |
| SAFE | 5156 | 8.6 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*