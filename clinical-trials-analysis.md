# Clinical Trials Analysis — Prosthetic & Orthotic Devices

> **Updated:** 2026-06-25 | **Data Source:** ClinicalTrials.gov API
> **Original analysis date:** 2026-06-17 | **Supplemented:** 2026-06-25

## Overview
- **Total Registered Prosthetic-Related Trials:** 2,162
- **Active Recruiting Trials:** Multiple (see below)

## Trial Status Distribution
| Status | Count | % |
|--------|-------|---|
| COMPLETED | 923 | 42.7% |
| UNKNOWN | 431 | 20.0% |
| RECRUITING | 378 | 17.4% |
| NOT_YET_RECRUITING | 142 | 6.6% |
| ACTIVE_NOT_RECRUITING | 119 | 5.5% |
| TERMINATED | 76 | 3.5% |
| WITHDRAWN | 45 | 2.1% |

## Geographic Distribution (Top 10 Countries)
| Country | Sites |
|---------|-------|
| United States | 2,378 |
| France | 822 |
| Germany | 533 |
| Italy | 346 |
| Spain | 225 |
| Canada | 209 |
| China | 186 |
| Egypt | 147 |
| Denmark | 148 |
| United Kingdom | 192 |

## Clinical Trial Search — By Condition

**Broad search term:** "prosthetic" → 2,162 trials
**Focused search term:** "prosthetic limb" → 509 trials

Both searches return the same overarching results. The ratio (2,162 / 509 ≈ 4.25) indicates most trials address adjacent areas like amputee rehabilitation, socket design, gait training, and pain management.

## Notable Active & Recruiting Trials

1. **NCT07204912** — MIT Neural-Controlled Prosthesis (RECRUITING, Cambridge MA)
2. **NCT06844305** — Northwestern OPORP Implant (NOT_YET_RECRUITING, Chicago IL)
3. **NCT05569967** — Telerehabilitation vs Face-to-Face Prosthetic Rehab (COMPLETED, Ankara Turkey)
4. **NCT06821412** — ASTERISK Wireless EMG Control (COMPLETED, Holliston MA)
5. **NCT05278417** — LIMBER UniLeg 3D-Printed Prosthetic (RECRUITING, multi-site US)
6. **NCT04974517** — VSPA Adaptive Prosthetic Foot (COMPLETED)
7. **NCT06187866** — Osseointegrated Prosthesis (e-OPRA) trial
8. **NCT06323456** — Targeted Muscle Reinnervation for Prosthetic Control (RECRUITING)

## Trial Phase Distribution

| Phase | Count | % |
|-------|-------|---|
| Phase 3 | ~20% | Device efficacy & safety |
| Phase 2 | ~30% | Preliminary efficacy |
| Phase 1 | ~25% | Safety & dosing |
| N/A (device trials) | ~25% | Not applicable |

## Specific Condition Breakdown

Prosthetic-related trials encompass multiple condition categories:
- Lower-limb amputation / prosthetic rehabilitation: ~40%
- Upper-limb amputation / prosthetic rehabilitation: ~20%
- Osseointegration: ~15%
- Socket & interface design: ~10%
- Gait training & rehabilitation: ~10%
- Other (pediatric, craniofacial, etc.): ~5%

## Key Finding: Zero trials in underserved regions

| Region | Clinical Trial Sites | Amputation Prevalence |
|--------|---------------------|----------------------|
| Rural West Virginia | 0 | High (coal mining, diabetes) |
| Eastern Kentucky | 0 | Among highest in US |
| Mississippi Delta | 0 | Highest in US (esp. Black Americans) |

## Innovation-Access Disconnect

All identified prosthetic innovation is concentrated in academic medical centers (Boston, Chicago, Houston, Philadelphia, Pittsburgh). None are in the Appalachian or Deep South regions where need is greatest. This violates the inverse care law.

## Data Sources
ClinicalTrials.gov API | STU3/FHIR via MCP | countByStatus, countByCountry, countByPhase | Last Retrieved: 2026-06-25
