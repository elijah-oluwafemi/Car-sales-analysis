# Car-Sales-Overview
This dataset appears to represent sales data for 10,000 car units across 10 major manufacturers from 2010 to 2020. The total revenue (sum of Price USD) is approximately $474 million, with an average price per unit of $47,398 (or ~$47.4K). Sales are fairly evenly distributed across manufacturers, but with notable variations in units sold, average pricing, and year-over-year performance. The data focuses on revenue rather than volume in most pivots, so insights will emphasize revenue trends while cross-referencing unit counts for context.

# Analysis Approach
I started with Excel pivot tables to aggregate and slice the data efficiently – a go-to tool for quick, iterative EDA. This allowed me to:
Summarize Revenue: By year, manufacturer, model, and engine size.
Calculate Metrics: Totals, averages, counts, and growth rates.
Data Visualizations: Using charts, slicers and timelines to get visual dynamic data.

# Key Insights
Drawing from the pivot tables, here are the most engaging findings – presented with tables and bullets for quick scanning. These insights highlight market shifts, competitive edges, and opportunities, much like I'd deliver in a business report.

1. Manufacturer Market Share & Performance
Nissan and Volkswagen dominate with ~10.4% market share each, generating $49.5M and $49.4M in revenue.
Premium brands like Mercedes-Benz achieve high revenue per unit ($48K avg.) despite fewer sales, showcasing pricing power.
Hyundai shows impressive growth: Revenue up 3% CAGR, surging 13% YoY in 2020 – a "rising star" in affordability.

2. Temporal Trends (2010–2020)

Overall market stable at ~$43M/year average, but with fluctuations (e.g., 2015 peak at $46M).
Declines for luxury brands post-2015 (BMW down 33% from peak), while Hyundai/Honda gained ground.
2020 Dip: Possible pandemic effects, but Hyundai bucked the trend with a record $5.3M.

3. Engine Size & Model Breakdown

Revenue evenly spread across 1–4L engines (~$11–13M per 0.1L bin), but 5L lags at $6.9M – hinting at a shift to efficient models.
Top Models: Chevrolet Malibu ($11M), Volkswagen Golf ($10.8M) – sedans still king (42% of revenue) over SUVs (32%).
Eco-Trend: Toyota Prius revenue grew 11% YoY in 2020, aligning with hybrid demand.

Learnings & Future Work
This project honed my ability to:

Handle large datasets with aggregations.
Spot trends in competitive markets.
Communicate findings engagingly (e.g., via Markdown & visuals).
