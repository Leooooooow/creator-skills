---
name: creator-attribution-lite
description: Connect creator content outputs to practical business outcomes using a lightweight attribution model. Use when the user asks which posts drove clicks/leads/sales, wants to prioritize high-ROI content types, or needs simple performance decisions without full BI setup.
---

# Creator Attribution Lite

## What this does

Show which content likely moved business outcomes, not just vanity metrics.

## Workflow

### 1) Validate data availability

Minimum fields per content item:
- content ID + date + platform
- views/watch metric
- click metric
- downstream metric (lead/signup/sale/GMV)

If real data is missing, run **simulation mode** and label outputs clearly as demo/synthetic.

### 2) Map funnel stage

Classify each content item as:
- awareness
- consideration
- conversion

### 3) Compute lightweight impact score

Use transparent weighted components:
- engagement quality
- click intent
- conversion signal

Explain formula and normalization assumptions.

### 4) Output action decisions

Return:
- ranked performers
- pause/optimize list
- next 3 content bets with rationale
- confidence note (sample size/data quality)

## Quality rules

- Keep model explainable and auditable.
- Avoid fake precision on tiny samples.
- Do not overclaim causality; treat as directional evidence.
## License

Copyright (c) 2026 **Razestar**.

This skill is available under **AGPL-3.0** for open-source use. Keep the
copyright notice, license text, and attribution notices when redistributing or
modifying it under AGPL-3.0.

If you want to use this skill in a **closed-source product, hosted platform,
white-label service, OEM distribution, or another arrangement that does not
comply with AGPL-3.0**, obtain a separate commercial license from **Razestar**.

No trademark or branding rights are granted.

