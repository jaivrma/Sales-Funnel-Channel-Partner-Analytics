# Sales Funnel & Partner Performance Analysis — Modular Kitchen Retail
An end-to-end analysis of the lead-to-order funnel for a modular kitchen retail business across Delhi NCR, built to identify where leads were being lost, which partners/channels actually drove revenue, and where regional focus should shift.
Business Problem

The business had leads flowing in from multiple channels and partners across Delhi NCR, but no clear visibility into:


Where leads were dropping off in the funnel (top of funnel vs. late-stage)
Which partners and lead sources were actually converting vs. just generating volume
Which geographic areas deserved more sales/marketing investment


Data


4 raw CSV files covering leads, quotes/orders, partner records, and regional/customer data (Jan 2024 – Dec 2024)
300 total leads tracked through the funnel over the year


Approach


Cleaned and joined the 4 CSVs into a single funnel-stage dataset (Lead → Quote → Order)
Built calculated measures in Power BI (DAX) for stage-wise conversion rates, revenue by partner, and lead source mix
Designed a multi-page dashboard: funnel overview, partner/revenue performance, lead source breakdown, geographic distribution, and monthly revenue trend


Key Findings

1. The real bottleneck is late-funnel, not lead generation


Lead → Quote conversion: 70% (300 → 210)
Quote → Order conversion: just 32.4% (210 → 68)
Overall lead-to-order conversion: 22.7%
→ The business doesn't have a lead problem, it has a quote-to-close problem. Sales follow-up/negotiation stage is where deals are lost, not awareness or initial interest.


2. Revenue is highly concentrated in a few partners


Top 3 partners (Delhi Modular Hub, KitchenStudio Delhi, ElegantHome Designs) generated ~₹19.6M of the ₹31M total revenue (~63%) from half the partner base
Delhi Modular Hub alone accounts for ~25% of total revenue (₹7.9M)
→ Partner relationship investment should be weighted toward top performers rather than spread evenly


3. Offline channels outperform digital for lead generation


Phone Call: 27.67% of leads (highest)
Walk-in: 21.67%
Website: 20%
Referral: 17.33%
Social Media: 13.33% (lowest)
→ Despite typical assumption that digital drives volume, phone and walk-in leads dominate — suggesting either strong local brand presence or under-optimized digital channels


4. Geographic demand is uneven


Saket leads in lead volume (57 leads), notably ahead of the next-highest areas (Karol Bagh, Dwarka, Janakpuri at ~39-40 each)
→ Signals where to prioritize showroom staffing, local marketing spend, or partner tie-ups


5. Premium deal size


Average deal value: ₹453.81K — indicates this is a premium/high-ticket segment, reinforcing why the quote-to-order stage (negotiation, trust-building) matters more than raw lead volume


Dashboard

The Power BI dashboard includes:


Funnel view — Leads → Quotes → Orders with stage-wise conversion
Partner performance — revenue by partner, ranked
Lead source breakdown — % share by channel
Geographic performance — leads and customers by area
Monthly revenue trend — Jan–Dec seasonality
Filters for Sales Person, Payment Status, and Order Date range


Tools Used

Power BI (Data Modeling, DAX, Interactive Dashboards) · Excel/CSV data prep
