---
name: creator-monetization-risk-checker
description: Run a pre-publish monetization risk check for creator content across short-video platforms. Use when the user asks if a script is safe to monetize, wants policy-risk triage, needs advertiser-friendliness checks, or wants rewrite guidance to reduce demonetization and distribution risk.
---

# Creator Monetization Risk Checker

## What this does (plain language)

Check content before posting so creators avoid avoidable monetization and distribution losses.

Output a simple decision:
- **Green**: publish
- **Yellow**: revise first
- **Red**: major risk, rework

## Workflow

### 1) Parse draft content

Review:
- script text
- hook/thumbnail/title claims
- sensitive topics and wording
- reused vs original content signals

### 2) Score risk categories

Score 1–5 for:
- policy/advertiser safety risk
- originality/reuse risk
- misleading-claim risk
- brand suitability risk

### 3) Produce mitigation edits

For each yellow/red item, provide:
- problem line
- safer rewrite
- confidence note

### 4) Final verdict

Return:
- risk color (green/yellow/red)
- top 3 fixes by impact
- revised publish-ready version when possible

## Quality rules

- Be strict on clear policy risk.
- Avoid fear-driven overblocking.
- Keep rewrites human, specific, and publishable.
