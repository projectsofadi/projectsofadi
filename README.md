# Adrian Cristache

Founding Partner & CTO at Equinox AI · 15 years in software · Bucharest, Romania (remote, EU/US overlap).
I build LLM/agent systems in production. At Equinox AI that means multi-agent review with verification gates on every money-path change to a crypto market-making platform that's been live 24/7 for 7+ years. The repositories here are independent, from-scratch builds of the same patterns — deliberately small, self-contained, and written to be reused.

**Focus:** multi-agent orchestration · Model Context Protocol (MCP) · agent evaluation & reliability · production hardening
**Contact:** adi@adriancristache.com · [LinkedIn](https://www.linkedin.com/in/adrian-cristache)

## What each repository demonstrates

| Repository | What it shows |
|---|---|
| [mcp-ci-triage](https://github.com/projectsofadi/mcp-ci-triage) | A working MCP server — GitHub Actions triage for coding agents: four read-only tools, one hardened network seam (deadlines, byte caps, redirect policy), 42 offline tests |
| [mcp-server-template](https://github.com/projectsofadi/mcp-server-template) | The build method behind it — I/O seams, offline test harness, least-privilege docs, and an 8-step half-day workflow ([BUILDING.md](https://github.com/projectsofadi/mcp-server-template/blob/HEAD/BUILDING.md)) |
| [ai_dev_team](https://github.com/projectsofadi/ai_dev_team) | An experimental multi-agent dev-team prototype — one shared ReAct loop, delegation as tool calls, fail-closed approval gates, a TS↔Python task bridge; 139 tests across both languages |
| [StrategyLab](https://github.com/projectsofadi/StrategyLab) | A deterministic strategy backtesting lab — strategies as validated JSON configs, adversarial weakness analysis in plain language, 141 offline tests |

All four are MIT-licensed with CI on Python 3.11–3.14 (SHA-pinned actions, ruff, offline test suites).
