# Mohamed Amine Aslimani

I build hands-on projects across Linux systems, networking, software, automation, embedded hardware, and applied AI. This profile brings together implemented work, reproducible setup instructions, and explicit project limitations.

---

## Featured — Autonomous AI security agent

### [Can You Trust What an Autonomous Agent Tells You?](https://aminewe898.github.io/autonomous-agent-report/)

**[Read the report](https://aminewe898.github.io/autonomous-agent-report/)** · **[Repository](https://github.com/aminewe898/autonomous-agent-report)**

A blind, scoreboard-verified study of a local 26-billion-parameter language-model agent operating as an autonomous web-security tester — built and tested entirely on a consumer laptop (RTX 5060, 8 GB VRAM), with zero paid services.

> The agent reported solving challenges it had not solved. An independent, tamper-proof scoreboard caught every false claim. That — not the capability — is the result that matters as teams begin handing agents real authority.

- Autonomous agent on a 26B uncensored model, fully local, grounded with an offline base of ~6,300 real vulnerability records (MITRE ATT&CK, CWE, CAPEC, CISA KEV, OWASP) so it cites genuine identifiers instead of inventing them.
- Safety enforced **below** the model — a hard guard on dangerous operations — rather than through prompt instructions the model can skip.
- Evaluated blind against OWASP Juice Shop in an isolated lab; scoreboard-verified solve rate rose from **43% to 100%** on the core set across five iterations, and the investigation showed most of the apparent "model ceiling" was an engineering gap, not a reasoning limit.

Method, figures, and data are in the full technical report. All offensive testing was conducted inside an isolated, authorized lab against a deliberately vulnerable training application.

---

## Selected engineering work

| Project | Technical focus | Status |
| --- | --- | --- |
| [Relay](https://github.com/aminewe898/relay) | Self-hosted service desk: PostgreSQL queues, n8n workers, Telegram voice intake, structured extraction, and an operations console | v1.0.0 released; fresh provider acceptance has a documented deferral |
| [CloudLink](https://github.com/aminewe898/cloudlink) | Android SSH/SFTP client, custom terminal engine, credential storage, and remote Linux telemetry | Source published; debug CI passes; device/release work remains |
| [Unreal MCP](https://github.com/aminewe898/unreal-mcp) | Native C++ editor bridge and typed Python toolsets for Unreal Engine | Editor plugin; 21 static tests pass; native/live integration is host-dependent |
| [n8n FlowForge MCP](https://github.com/aminewe898/n8n-flowforge-mcp) | Controlled workflow tooling: validation, dry-run previews, execution diagnosis, and semantic diffs | Typechecks, 78 mock/loopback tests, and build pass; live-instance acceptance is separate |
| [Cyberdeck](https://github.com/aminewe898/cyberdeck) | Python/Flask system monitoring, authenticated routes, browser charts, and SSE | Implemented project; deployment-dependent metrics |
| [NEXUS PEAR Rev A](https://github.com/aminewe898/nexus-pear-reva) | ESP32-S3 carrier design, KiCad schematics/PCB, power and audio analysis, manufacturing review artifacts | Engineering review; delivery-record reconciliation, firmware, bench testing, and fabrication approval remain |

## Additional work

[Mini DJ Controller](https://github.com/aminewe898/mini-DJcontroller) preserves hands-on Pico PWM/ESP32 BLE prototypes, CAD, schematics, and build history. [MCC Interim Linux](https://github.com/aminewe898/mcc-interim-linux-modern-guide) documents early Linux installation, Bochs emulation, disk geometry, and a bootable-image release.

[SendReady](https://github.com/aminewe898/SendReady) is an Android/Media3 video-compression prototype with debug-build validation and pending device/release testing. [FinTrack](https://github.com/aminewe898/FinTrack) explores a dependency-free Node.js API, signed authentication, JSON persistence, and a browser dashboard. [Binary converter](https://github.com/aminewe898/binaryconverterbyamin) is a smaller educational app with step-by-step integer conversion.

## How to review the projects

Start with each README, then inspect source, architecture, validation evidence, and limitations. The repositories distinguish implemented features from future work; hardware, external-provider, and production-security claims are bounded by the evidence available.
