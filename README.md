# SuperInvesting • Cohort Telemetry & Usage Analytics

A high-performance, static analytics dashboard comparing product usage, feature adoption, and retention between **Batch 1 (2,984 users)** and **Batch 2 (2,395 users)** across **12.78 Million telemetry events** and real-time broker holdings.

## Key Executive Findings

| Dimension | Batch 1 | Batch 2 | Variance |
| :--- | :---: | :---: | :---: |
| **Cohort Size** | 2,984 users | 2,395 users | +589 |
| **Active Users ($\ge 1$ Event)** | 2,772 (92.9%) | 2,078 (86.8%) | +6.1% |
| **Total Event Triggers** | 11,856,503 | 925,918 | +10,930,585 |
| **Avg Events / Active User** | 4,277.2 | 445.6 | +3,831.7 |
| **Active Days / Active User** | 25.2 days | 12.0 days | +13.2 days |
| **7-Day Recency (Oct 7–14)** | 1,344 (45.0%) | **1,550 (64.7%)** | **-19.7% (B2 higher)** |
| **Paid Subscribers** | 2,794 (93.6%) | 2,154 (89.9%) | +3.7% |
| **Broker Portfolio Synced** | 1,516 (50.8%) | 1,195 (49.9%) | +0.9% |

- **Batch 1** is an established, high-maturity cohort with massive cumulative event depth (11.86M events).
- **Batch 2** is significantly more active currently, leading 7-day recency by **+19.7%** (64.7% active vs 45.0%).
- Both cohorts have an identical **~50%** broker portfolio sync rate.

## Dashboard Features

- **Monochrome Architectural Palette**: Clean Graphite & Titanium light mode design without oversaturated accents or AI slop.
- **Side-by-Side Feature Penetration**: Compares unique user adoption across Stock Analysis, AI Chat, Stock Searches, Thematic Baskets, Watchlist, and Live Masterclasses.
- **Granular Event Explorer**: 197 telemetry events with instant real-time search, category filtering, and bidirectional sorting.
- **User Explorer**: Instant search by Name, Phone, or User ID across all 5,379 cohort users with quick filters (Active, 7-Day Recent, Portfolio Synced, Paid).
- **Direct Workbook Download**: One-click download of the complete multi-tab `Batch_Wise_Usage_Analysis.xlsx`.

## Deployment to Vercel

### Option 1: Via Vercel Web Dashboard (1-Click)
1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and select the **`KindaJayant/et-batch-wise`** repository.
3. Leave **Framework Preset** as **Other** (Static HTML).
4. Click **Deploy**. Vercel will instantly publish the dashboard to a live URL (e.g. `https://et-batch-wise.vercel.app`).

### Option 2: Via Vercel CLI
```bash
npm i -g vercel
cd et-batch-wise
vercel --prod
```
