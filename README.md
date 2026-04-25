# risk-radar

> 🇰🇷 [한국어 README](./README.ko.md)

**A proactive risk prediction and monitoring engine built on rigorous risk theory — Knight's uncertainty, Taleb's antifragility, Reason's Swiss Cheese, Perrow's Normal Accidents — going far beyond probability × impact matrices.**

## Prerequisites

- **Claude Cowork or Claude Code** environment

## Goal

Traditional risk management identifies risks and puts them in a matrix. This skill goes deeper: it classifies risk types (Risk vs Uncertainty vs Ambiguity), diagnoses system vulnerability (complexity × coupling), screens for cognitive biases that distort risk assessment, and designs responses informed by antifragility principles and High Reliability Organization theory.

## When & How to Use

Triggers when you mention risk analysis, risk scanning, or risk monitoring. Three modes: **Scan** (comprehensive risk assessment), **Update** (refresh existing risk map), and **Deep Dive** (causal chain analysis of specific risks). Say "이 프로젝트 리스크 점검해줘" or "리스크 맵 업데이트해줘".

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Project risk scan | `"이 프로젝트 리스크 점검해줘"` | Knight classification → 6-axis screening → Perrow system diagnosis → multi-dimensional assessment → cognitive bias debrief → response design |
| Investment risk analysis | `"투자 결정 전에 리스크 스캔해줘"` | Identifies fat-tail risks, applies Flyvbjerg reference class forecasting, designs barbell-style response |
| Risk map refresh | `"지난번 리스크 맵 업데이트해줘"` | Updates P×I + velocity + interconnectedness, re-screens biases, validates response effectiveness |

## Key Features

- **Risk Type Classification** — Knight's trichotomy (Risk/Uncertainty/Ambiguity) × Kaplan & Mikes (Preventable/Strategy/External) dual classification routing to different management methods
- **System Vulnerability Diagnosis** — Perrow's complexity × coupling matrix identifies systems prone to "normal accidents"
- **Multi-dimensional Assessment** — Beyond P×I: adds velocity, interconnectedness, fat-tail potential, and detection difficulty
- **Cognitive Bias Debrief** — Mandatory post-scan check for 6 biases (normalcy, availability, optimism, narrative fallacy, probability neglect, representativeness)
- **Antifragility Design** — Response strategies include Taleb's barbell, optionality, and HRO principles
- **Hub+Spoke Architecture** — Lean hub with 6 deep reference files

## Works With

- **[management-skill](https://github.com/jasonnamii/management-skill)** — Red risks trigger crisis management (M6) handoff
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — Strategic risk pattern matching
- **[startup-investment](https://github.com/jasonnamii/startup-investment)** — Investment risk → valuation/term sheet risk
- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — Planning phase risk scan integration

## Installation

```bash
git clone https://github.com/jasonnamii/risk-radar.git ~/.claude/skills/risk-radar
```

## Update

```bash
cd ~/.claude/skills/risk-radar && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
