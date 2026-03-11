# Smoke Test: creator-attribution-lite

## 1) Minimal dataset (6 short videos)

| Content ID | Platform | Publish Date | Funnel Stage | Views | Watch % | Saves | Clicks | Signups | Sales |
|---|---|---|---|---:|---:|---:|---:|---:|---:|
| TT-101 | TikTok | 2026-03-01 | Awareness | 82,000 | 34% | 1,180 | 640 | 52 | 9 |
| TT-102 | TikTok | 2026-03-03 | Conversion | 46,000 | 29% | 420 | 910 | 88 | 21 |
| IG-201 | Reels | 2026-03-04 | Consideration | 39,000 | 31% | 960 | 350 | 37 | 7 |
| IG-202 | Reels | 2026-03-06 | Awareness | 71,000 | 19% | 210 | 120 | 9 | 1 |
| YT-301 | Shorts | 2026-03-07 | Consideration | 55,000 | 42% | 1,430 | 520 | 61 | 12 |
| YT-302 | Shorts | 2026-03-09 | Conversion | 28,000 | 24% | 180 | 610 | 70 | 18 |

## 2) Lightweight impact scoring model (transparent)

- **Engagement Quality (EQ)** = 60% watch-rate index + 40% save-rate index
- **Click Intent (CI)** = CTR index
- **Conversion Signal (CS)** = 40% signup-rate-from-click index + 60% sales-rate-from-click index
- **Impact Score (0–100)** = 35% EQ + 25% CI + 40% CS
- Indexes are normalized to the best item in this 6-video sample.

> Small sample (n=6): treat scores as directional for decisions, not absolute truth.

| Content ID | EQ | CI | CS | Impact Score |
|---|---:|---:|---:|---:|
| YT-301 | 1.000 | 0.434 | 0.869 | **80.6** |
| YT-302 | 0.442 | 1.000 | 0.992 | **80.1** |
| TT-102 | 0.555 | 0.908 | 0.799 | **74.1** |
| IG-201 | 0.822 | 0.412 | 0.767 | **69.7** |
| TT-101 | 0.707 | 0.358 | 0.563 | **56.2** |
| IG-202 | 0.317 | 0.078 | 0.425 | **30.0** |

## 3) Action list

### Top performers by business impact
1. **YT-301 (80.6)** — strongest retention + saves, with solid downstream conversion.
2. **YT-302 (80.1)** — best click intent and best sales efficiency from click.
3. **TT-102 (74.1)** — conversion-led format works despite lower watch depth.

### Pause list (underperformers)
- **IG-202 (30.0)** — high reach, but weak watch depth, CTR, and conversion; pause this creative style.
- **TT-101 (56.2)** — awareness is okay, but weak click/conversion efficiency vs peers; pause until CTA/offer packaging is rebuilt.

### Next 3 content bets
1. **Shorts 2-step funnel bet:** publish tutorial-first (YT-301 style) followed by offer-led follow-up (YT-302 style) within 24–48h.
2. **Reels conversion recovery bet:** adapt TT-102 structure to Reels (proof-first opener + explicit CTA + pinned link).
3. **TikTok CTR lift bet:** recut high-retention educational content with a tighter first-2s hook and stronger end-card CTA.

SMOKE_TEST_DONE
