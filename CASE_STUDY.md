# Case Study: Turning Beauty Brand Sales Data Into Growth Decisions

## The Situation

Most beauty and personal care brands sell across multiple channels — D2C websites, Instagram Shop, Amazon, Nykaa, Quick Commerce, and offline retail — and generate a steady stream of sales, pricing, ratings, and marketing spend data along the way. Very few actually mine that data to answer the questions that matter most:

- Which channel should we double down on?
- Which brands/products are converting marketing spend into revenue efficiently — and which aren't?
- Are we assuming the wrong cities are our growth priority?

This analysis works through a real beauty & personal care sales dataset to answer exactly those questions — the kind of teardown any brand sitting on similar data could benefit from.

## Approach

1. **Cleaned and validated the dataset** — handled missing values, corrected data types, removed duplicates
2. **Explored channel, brand, product, and geographic performance** independently
3. **Cross-referenced marketing spend against revenue** to surface efficiency, not just scale
4. **Ran a correlation analysis** across 17 numeric variables to find relationships hiding beneath the surface
5. **Converted every finding into a specific, actionable recommendation** — not just an observation

## Key Findings

### 1. Instagram Shop is quietly your best channel

Instagram Shop leads on revenue, has the highest repeat-purchase rate (43.7%), and the lowest return rate (18.0%) of all six channels analyzed. Retail/Offline, by contrast, has the highest return rate (20.8%) and is losing ground.

![Channel distribution](images/plot_04.png)

**Why it matters:** brands often allocate marketing budget based on channel *size* or habit, not on which channel actually retains customers with the fewest returns. Instagram Shop is doing both — and may be underfunded relative to its performance.

### 2. Marketing spend efficiency varies sharply by brand — and it's not about budget size

The most efficient brand analyzed generated ₹1.89 in revenue for every ₹1 of marketing spend; the least efficient generated only ₹1.53 — despite having one of the *highest* budgets in the dataset.

**Why it matters:** without this analysis, a brand would likely conclude "we need to spend more." The data says the opposite — it needs to spend *smarter*. This is a reallocation opportunity, not a budget-increase one.

### 3. Fragrance is a margin category hiding in plain sight

Fragrance subcategories (Eau de Parfum, Attar, Eau de Toilette, Body Mist) occupy the top 4 revenue spots in the entire dataset — despite only mid-pack unit sales. Serum, meanwhile, sells the most *units* but ranks just 5th in revenue.

**Why it matters:** a brand optimizing purely for "what sells the most" would over-invest in Serum and under-invest in Fragrance — missing the higher-margin opportunity entirely.

### 4. Geography defies the "Tier-1 city" assumption

Revenue is fairly even across cities (₹5.63cr–₹6.63cr), but **Chennai leads the pack**, while Delhi and Hyderabad — typically treated as default growth priorities — rank near the bottom.

**Why it matters:** expansion budgets allocated by city "reputation" rather than actual performance data risk missing the brand's real growth markets.

### 5. Rating and repeat purchase are meaningfully linked

A correlation analysis across all numeric variables in the dataset shows average rating is positively correlated with repeat purchase rate (0.58) and negatively correlated with return rate (-0.38) — one of the strongest relationships in the entire dataset.

![Correlation heatmap](images/plot_07.png)

**Why it matters:** product quality (as reflected in ratings) isn't just a brand-perception metric — it's a measurable driver of repeat revenue and reduced returns, which makes it a legitimate lever for growth, not just customer service.

## Recommendations

1. **Shift incremental marketing spend toward Instagram Shop and away from Retail/Offline**, given its loyalty and low-return combination.
2. **Audit the lowest-efficiency brands' marketing spend** — high budget isn't converting to proportional revenue; study what the most efficient brands are doing differently.
3. **Treat fragrance as a margin/revenue priority category**, not just a volume one, when planning inventory and marketing focus.
4. **Don't default to Tier-1 cities for expansion** — Chennai and other outperforming cities deserve a deeper regional look before budget is allocated.
5. **Treat product rating as a growth lever, not just a satisfaction metric** — improvements here plausibly compound into higher repeat-purchase rates and lower returns.

## Why This Matters for Your Brand

Every one of the findings above came from data most beauty and personal care brands already have sitting in their Shopify, POS, or marketplace exports — it just isn't being asked the right questions. This is exactly the kind of analysis I do: turning data you already collect into decisions you can act on this quarter, not just interesting charts.

If you'd like a similar teardown of your own sales data — no strings attached — I'm happy to put together a free 1-page analysis so you can see what's possible before committing to anything further.

---
*Full analysis and code: [data_analysis.ipynb](data_analysis.ipynb)*
