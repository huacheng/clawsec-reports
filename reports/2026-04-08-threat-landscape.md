# AI Agent Skill Threat Landscape

> Date: 2026-04-08 | Audited by [ClawSec](https://clawsec.cc)

Analysis of **20813** threats detected across **2105** audited skills.

## Threats by Severity

| Severity | Count | % |
|----------|-------|---|
| CRITICAL | 1052 | 5% |
| HIGH | 5825 | 28% |
| MEDIUM | 4178 | 20% |
| LOW | 9758 | 47% |

## Top 15 Threat Types

| Threat | Count | Severity |
|--------|-------|----------|
| LLM Semantic Detection | 15201 | LOW |
| Dynamic Code Evaluation | 2018 | HIGH |
| Startup Failure (non-executable) | 1947 | LOW |
| Outbound Data Transfer | 765 | HIGH |
| Hidden Command Execution | 342 | MEDIUM |
| Private Key Extraction | 107 | CRITICAL |
| Environment Variable Exfiltration | 107 | CRITICAL |
| Base64 Encoded Payload | 58 | HIGH |
| Remote Script Execution | 54 | CRITICAL |
| Execution Crash | 26 | MEDIUM |
| Shell RC Modification | 24 | HIGH |
| Cron Job Installation | 22 | HIGH |
| Obfuscated Code | 20 | MEDIUM |
| Systemd Service Installation | 19 | HIGH |
| Cryptocurrency Wallet Access | 19 | CRITICAL |

## Threats by Verdict

| Verdict | Threats | Avg Threats/Skill |
|---------|---------|-------------------|
| MALICIOUS | 2065 | 12.0 |
| SUSPICIOUS | 10744 | 10.6 |
| SAFE | 7988 | 8.7 |

---
*[ClawSec](https://clawsec.cc) | [ClawSearch](https://clawsearch.cc)*