# Weekly Product Metrics — 2026-06-22

> **Period:** this_week = Jun 15–22 2026 | last_week = Jun 8–15 2026
>
> **Hostname note:** `code.llmgateway.io` returned no PostHog data. All "code" rows use `devpass.llmgateway.io`, the actual hostname for the dev-plans dashboard.

---

## Overall Traffic (this week vs last week)

| Product | PV (TW) | Uniques (TW) | Sessions (TW) | WoW PV | WoW Uniques |
|---|---|---|---|---|---|
| llmgateway.io | 16,490 | 4,337 | 5,416 | +26.1% | +44.2% |
| devpass.llmgateway.io | 5,159 | 404 | 1,070 | +21.8% | +7.4% |
| docs.llmgateway.io | 1,705 | 543 | 690 | **−18.8% ⚠️** | **−47.8% ⚠️** |
| chat.llmgateway.io | 1,161 | 383 | 514 | +38.9% | +59.6% |

---

## llmgateway.io

**Headline:** PV 16,490 (+26.1%) | Uniques 4,337 (+44.2%) | Sessions 5,416 (+32.5%)

### Top 10 pages (this week)
| Page | PV | Uniques |
|---|---|---|
| / | 3,146 | 1,978 |
| /models | 1,249 | 549 |
| /pricing | 725 | 562 |
| /signup | 695 | 534 |
| /dashboard | 460 | 212 |
| /login | 290 | 201 |
| /models/glm-4.7-flash-free | 219 | 122 |
| /features/unified-api-interface | 212 | 166 |
| /timeline | 201 | 151 |
| /providers | 147 | 90 |

### Top 10 referrers (this week)
| Referrer | Visits | Uniques |
|---|---|---|
| (direct) | 7,273 | 2,435 |
| www.google.com | 6,045 | 1,504 |
| llmgateway.io (self) | 851 | 126 |
| devpass.llmgateway.io | 450 | 54 |
| www.bing.com | 243 | 64 |
| t.co | 174 | 80 |
| accounts.google.com | 152 | 39 |
| www.reddit.com | 124 | 47 |
| github.com | 115 | 38 |
| duckduckgo.com | 101 | 27 |

Notable: `opencode.ai` (98 visits / 33 uniques) is a new notable referrer — developer-tool audience finding the gateway via the opencode ecosystem.

### Bounce rate / avg PV per session
| Metric | This Week | Last Week | Δ |
|---|---|---|---|
| Bounce rate | 61.7% | 56.0% | **+5.7pp ⚠️** |
| Avg PV/session | 3.04 | 3.20 | −0.16 |

### Top 10 countries (this week)
| Country | PV | Uniques |
|---|---|---|
| United States | 1,949 | 717 |
| Singapore | 1,428 | 1,230 |
| South Korea | 1,408 | 154 |
| India | 1,158 | 279 |
| Germany | 649 | 129 |
| China | 582 | 117 |
| Japan | 556 | 81 |
| Philippines | 472 | 51 |
| United Kingdom | 460 | 82 |
| Brazil | 457 | 79 |

### Device breakdown (this week)
| Device | PV | Uniques |
|---|---|---|
| Desktop | 12,374 | 3,535 |
| Mobile | 3,879 | 816 |
| Tablet | 237 | 19 |

### Flags
- Bounce rate worsened from 56.0% → 61.7% (+5.7pp, +10.2% relative). Likely correlated with the signup conversion collapse — traffic is arriving but not engaging.
- Self-referrer (llmgateway.io → llmgateway.io): 851 visits / 126 uniques = 6.75:1 — not suspicious; normal in-app navigation.
- Sweden: 426 PV / 29 uniques = 14.7:1 — borderline elevated, monitor next week.

---

## docs.llmgateway.io

**Headline:** PV 1,705 (−18.8%) | Uniques 543 (−47.8%) | Sessions 690 (−40.0%)

**⚠️ All three traffic metrics declined >15% WoW — see investigation section.**

### Top 10 pages (this week)
| Page | PV | Uniques |
|---|---|---|
| / | 512 | 305 |
| /self-host | 140 | 86 |
| /guides/cursor | 117 | 101 |
| /quick-start | 116 | 85 |
| /overview | 91 | 62 |
| /features/routing | 47 | 36 |
| /features/anthropic-endpoint | 33 | 27 |
| /v1_models | 29 | 22 |
| /features/api-keys | 26 | 23 |
| /features/reasoning | 18 | 16 |

### Top 10 referrers (this week)
| Referrer | Visits | Uniques |
|---|---|---|
| (direct) | 1,270 | 375 |
| www.google.com | 230 | 126 |
| llmgateway.io | 69 | 23 |
| docs.llmgateway.io (self) | 60 | 14 |
| chatgpt.com | 23 | 9 |
| devpass.llmgateway.io | 9 | 4 |
| t.co | 7 | 3 |
| gemini.google.com | 6 | 2 |
| duckduckgo.com | 5 | 1 |
| google (android) | 4 | 2 |

### Bounce rate / avg PV per session
| Metric | This Week | Last Week | Δ |
|---|---|---|---|
| Bounce rate | 61.9% | 76.1% | **−14.2pp ✓** |
| Avg PV/session | 2.47 | 1.83 | +0.64 ✓ |

Bounce rate improved sharply, suggesting the remaining traffic is higher quality; the lost visitors were likely low-intent (bot traffic / single-page scrapers) in LW.

### Top 10 countries (this week)
| Country | PV | Uniques |
|---|---|---|
| United States | 258 | 130 |
| Japan | 193 | 16 |
| India | 156 | 47 |
| South Korea | 126 | 36 |
| Germany | 102 | 20 |
| China | 80 | 49 |
| Singapore | 73 | 17 |
| United Kingdom | 49 | 16 |
| The Netherlands | 43 | 13 |
| Taiwan | 42 | 6 |

### Device breakdown (this week)
| Device | PV | Uniques |
|---|---|---|
| Desktop | 1,454 | 447 |
| Mobile | 242 | 98 |
| Tablet | 9 | 2 |

### Flags
- **⚠️ −47.8% uniques WoW.** The LW bounce rate was 76.1% (now 61.9%), suggesting LW had a volume spike of low-quality traffic that has since cleared. Check whether LW had an unusual SEO bot crawl, HN/Reddit link, or AI aggregator hit.
- Japan: 193 PV / 16 uniques = 12.1:1 — elevated but below threshold; monitor.

---

## devpass.llmgateway.io (code.llmgateway.io)

**Headline:** PV 5,159 (+21.8%) | Uniques 404 (+7.4%) | Sessions 1,070 (−0.8%)

Note: Headline PV is likely inflated by a South Korean bot cluster (see Flags). Sessions flat WoW despite +21.8% PV growth.

### Top 10 pages (this week)
| Page | PV | Uniques |
|---|---|---|
| /dashboard | 2,614 | 151 |
| / | 885 | 338 |
| /login | 429 | 39 |
| /pricing | 245 | 155 |
| /dashboard/billing | 229 | 57 |
| /coding-models | 158 | 74 |
| /dashboard/settings | 141 | 42 |
| /profile | 134 | 42 |
| /signup | 131 | 73 |
| /guides | 52 | 31 |

Notable: `/dashboard` 2,614 PV from 151 uniques = 17.3:1 — high but expected for a dashboard product. `/login` 429 PV from 39 uniques = 11:1 — worth checking for auth loops.

### Top referrers (this week)
| Referrer | Visits | Uniques |
|---|---|---|
| (direct) | 4,564 | 328 |
| devpass.llmgateway.io (self) | 213 | 25 |
| www.google.com | 198 | 28 |
| checkout.stripe.com | 56 | 6 |
| t.co | 42 | 22 |
| accounts.google.com | 33 | 5 |
| com.linkedin.android | 18 | 9 |
| www.linkedin.com | 14 | 9 |

Notable: `checkout.stripe.com` returning 56 visits (6 uniques) confirms the payment → dashboard return flow is active.

### Bounce rate / avg PV per session
| Metric | This Week | Last Week | Δ |
|---|---|---|---|
| Bounce rate | 41.8% | 43.7% | −1.9pp ✓ |
| Avg PV/session | 4.82 | 3.92 | +0.90 ✓ |

### Top 10 countries (this week)
| Country | PV | Uniques |
|---|---|---|
| South Korea | 3,148 | 108 |
| United Kingdom | 334 | 17 |
| United States | 324 | 50 |
| Germany | 179 | 16 |
| France | 143 | 9 |
| Japan | 109 | 14 |
| Cyprus | 101 | 1 |
| Greece | 85 | 2 |
| Morocco | 84 | 27 |
| Ecuador | 75 | 2 |
| Taiwan | 56 | 4 |
| India | 50 | 17 |

### Device breakdown (this week)
| Device | PV | Uniques |
|---|---|---|
| Desktop | 3,263 | 274 |
| Mobile | 1,886 | 144 |
| Tablet | 10 | 3 |

### Flags
- **⚠️ South Korea: 3,148 PV / 108 uniques = 29:1** — a handful of accounts are driving ~61% of all devpass pageviews. True organic PV without KR cluster is ~2,011.
- **⚠️ Cyprus: 101 PV / 1 unique = 101:1**
- **⚠️ Greece: 85 PV / 2 uniques = 42.5:1**
- **⚠️ Ecuador: 75 PV / 2 uniques = 37.5:1**
- `/login` 429 PV / 39 uniques = 11:1 — investigate for auth redirect loops.

---

## chat.llmgateway.io

**Headline:** PV 1,161 (+38.9%) | Uniques 383 (+59.6%) | Sessions 514 (+51.6%)

ProductHunt referral surge (122 visits / 50 uniques) is the likely driver.

### Top 10 pages (this week)
| Page | PV | Uniques |
|---|---|---|
| / | 751 | 361 |
| /pricing | 152 | 76 |
| /signup | 88 | 77 |
| /video | 32 | 20 |
| /image | 32 | 19 |
| /group | 30 | 15 |
| /login | 21 | 16 |
| /canvas | 15 | 12 |
| /audio | 14 | 9 |
| /compare | 13 | 8 |

### Top 10 referrers (this week)
| Referrer | Visits | Uniques |
|---|---|---|
| (direct) | 928 | 301 |
| www.producthunt.com | 122 | 50 |
| www.google.com | 22 | 6 |
| chat.llmgateway.io (self) | 21 | 3 |
| t.co | 17 | 7 |
| com.google.android.gm (Gmail) | 16 | 6 |
| llmgateway.io | 11 | 6 |
| huntscreens.com | 4 | 2 |

### Bounce rate / avg PV per session
| Metric | This Week | Last Week | Δ |
|---|---|---|---|
| Bounce rate | 59.3% | 57.8% | +1.5pp |
| Avg PV/session | 2.26 | 2.47 | −0.21 |

### Top 10 countries (this week)
| Country | PV | Uniques |
|---|---|---|
| United States | 163 | 97 |
| India | 120 | 38 |
| South Korea | 94 | 13 |
| Poland | 84 | 4 |
| Germany | 66 | 17 |
| Philippines | 56 | 10 |
| Sweden | 54 | 7 |
| Vietnam | 47 | 14 |
| United Kingdom | 45 | 10 |
| Brazil | 31 | 14 |

### Device breakdown (this week)
| Device | PV | Uniques |
|---|---|---|
| Desktop | 889 | 294 |
| Mobile | 261 | 91 |
| Tablet | 11 | 4 |

### Flags
- ProductHunt traffic (122 visits) likely one-time; watch next-week retention to gauge stickiness.
- **⚠️ Poland: 84 PV / 4 uniques = 21:1** — over threshold at 84 PVs; possible bot or power user.

---

## Product Events (this week vs last week)

| Event | TW Events | TW Users | LW Events | LW Users | WoW Events | WoW Users |
|---|---|---|---|---|---|---|
| **user_signed_up** | 62 | 62 | 125 | 125 | **−50.4% ⚠️** | **−50.4% ⚠️** |
| user_logged_in | 46 | 27 | 45 | 33 | +2.2% | −18.2% |
| onboarding_completed | 38 | 36 | 41 | 37 | −7.3% | −2.7% |
| onboarding_try_success | 17 | 14 | 19 | 19 | −10.5% | −26.3% |
| api_key_created | 275 | 213 | 134 | 114 | **+105.2%** | +86.8% |
| credits_purchased | 100 | 1 | 109 | 1 | −8.3% | flat |
| subscription_created | 6 | 1 | 3 | 1 | +100% | flat |
| dev_plan_started | 41 | 1 | 27 | 1 | +51.9% | flat |
| dev_plan_subscribe_started | 59 | 43 | 48 | 37 | +22.9% | +16.2% |
| dev_plan_renewed | 5 | 1 | 8 | 1 | −37.5% | flat |
| dev_plan_tier_changed | 11 | 10 | 17 | 15 | −35.3% | −33.3% |
| playground_chat_sent | 409 | 13 | 315 | 32 | +29.8% | −59.4% |
| playground_image_generated | 14 | 1 | 21 | 4 | −33.3% | −75.0% |
| playground_video_generated | 11 | 5 | 13 | 2 | −15.4% | +150% |
| playground_group_chat_started | 5 | 2 | 2 | 2 | +150% | flat |
| provider_key_added | 31 | 11 | 36 | 11 | −13.9% | flat |
| pricing_plan_clicked | 37 | 29 | 34 | 28 | +8.8% | +3.6% |
| **topup_completed** | 16 | 13 | 32 | 19 | **−50.0% ⚠️** | **−31.6% ⚠️** |
| cta_clicked | 341 | 148 | 274 | 148 | +24.5% | flat |

**Data-quality notes on product events:**
- `credits_purchased`: 100 events from **1 user** (TW) — single user or automation driving all purchases.
- `dev_plan_started`: 41 events from **1 user** (TW); `subscription_created` 6 from 1 user — same pattern; likely internal testing or a retry loop.
- `playground_chat_sent`: 409 events from 13 users (TW) vs 315 from 32 users (LW) — the user base dropped 59% but event volume rose 30%; a few heavy users are inflating the count.

---

## Top 3 Things to Investigate This Week

1. **user_signed_up −50.4% (62 vs 125)** while llmgateway.io traffic is up +26% and the /signup page served 695 PVs to 534 uniques. That implies a ~11.6% page-to-signup conversion rate vs ~23% LW. Check the full signup funnel: /signup page load → form submit → email verification → account creation. If the form submit or email verification step is broken, sign-ups would vanish without a visible error in analytics.

2. **topup_completed −50.0% (16 vs 32) and credits_purchased −8.3% (100 vs 109).** Revenue-critical events are falling even as traffic grows. The `credits_purchased` 1-user anomaly (100 events, 1 unique) likely masks the real trend — strip that user out and the true purchase count is close to zero. Check Stripe for failed charges, a broken checkout redirect, or a pricing/quota change that dampened demand.

3. **docs.llmgateway.io uniques −47.8% WoW (543 vs 1,041).** The simultaneous bounce-rate improvement (76.1% → 61.9%) suggests last week's high unique count was driven by low-quality traffic (bots, scrapers, or a one-time social spike). Cross-reference with Google Search Console for ranking changes on `/self-host`, `/guides/cursor`, and `/quick-start` — the three highest-traffic pages. If organic ranks held, the LW spike was anomalous and this week is the baseline.

---

## Bot / Data-Quality Flags

### Pages with >20:1 view-to-unique ratio (≥50 pageviews)
| Host | Page | PV | Uniques | Ratio |
|---|---|---|---|---|
| llmgateway.io | /dashboard/s9O0cesCCD358r5xEEaK/…/activity | 54 | 1 | **54:1** |

Consistent with a single user or headless client repeatedly polling their activity page.

### Referrers with suspicious ratios (≥20 visits)
| Referrer | Visits | Uniques | Ratio |
|---|---|---|---|
| ph.search.yahoo.com | 28 | 1 | 28:1 |
| ca.search.yahoo.com | 20 | 1 | 20:1 |
| m.search.naver.com | 21 | 2 | 10.5:1 |
| huntscreens.com | 33 | 3 | 11.0:1 |

Yahoo regional search crawlers (`ph`, `ca`) are the likely source of the 28:1 and 20:1 referrer rows.

### Geo clusters with bot-like patterns
| Host | Country | PV | Uniques | Ratio |
|---|---|---|---|---|
| devpass.llmgateway.io | South Korea | 3,148 | 108 | **29:1** |
| devpass.llmgateway.io | Cyprus | 101 | 1 | **101:1** |
| devpass.llmgateway.io | Greece | 85 | 2 | **42.5:1** |
| devpass.llmgateway.io | Ecuador | 75 | 2 | **37.5:1** |
| chat.llmgateway.io | Poland | 84 | 4 | **21:1** |

The South Korea cluster on devpass is the most impactful: 3,148 of 5,159 total PVs (61%) come from 108 users — a 29:1 ratio. Without this cluster, devpass organic PVs drop to ~2,011 and the WoW growth narrative changes. Investigate whether these are power-user developers, CI/CD pipeline calls, or an uptime monitoring bot from a Korean host.
