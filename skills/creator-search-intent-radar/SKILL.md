---
name: creator-search-intent-radar
description: Convert TikTok/YouTube/Instagram search and trend signals into a prioritized weekly content backlog with script angles and hook directions. Use when the user asks what to post next, wants trend-based topic discovery, needs search-intent analysis, or wants a platform-by-platform content idea pipeline.
---

# Creator Search Intent Radar

## Overview

Use this skill to turn messy trend inputs into **publishable topic decisions**.  
Focus on demand signals first, then map each signal to a clear content angle.

## Workflow

### 1) Collect demand signals

Gather 10–30 candidate signals from a mix of:

- TikTok search and trend surfaces (e.g., Creator Search Insights/newsroom trends)
- YouTube search/autosuggest/topic momentum
- Instagram/Reels topic momentum and recurring audience questions
- Community signals (comments, FAQs, recurring pain points)

Prefer recent signals (24–72h) unless the user asks for evergreen topics.

### 2) Normalize into one backlog

For each candidate topic, record:

- `topic`
- `platform_fit` (TikTok / YouTube / Instagram)
- `intent_type` (learn / compare / buy / troubleshoot / inspiration)
- `freshness` (hot / warm / evergreen)
- `audience_fit` (1–5)
- `monetization_fit` (1–5)
- `difficulty` (1–5)

### 3) Score and rank

Use this quick score:

`priority_score = (audience_fit * 0.35) + (freshness * 0.25) + (monetization_fit * 0.25) + (execution_speed * 0.15)`

Convert text labels to numeric values when needed (e.g., hot=5, warm=3, evergreen=2).

### 4) Output weekly plan

Return:

1. **Top 10 ranked topics**
2. For each topic, one **content angle** and three **hook directions**
3. A practical **7-day schedule** (lightweight, not over-optimized)

## Output format

Use this compact block per topic:

- Topic:
- Why now:
- Platform:
- Intent:
- Angle:
- Hook directions (3):
- CTA:

## Quality bar

- Avoid generic trends without audience fit.
- Prefer topics with clear user intent and concrete use cases.
- Keep recommendations executable by a small creator team.
