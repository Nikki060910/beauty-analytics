# Beauty & Personal Care Sales Analytics

An end-to-end exploratory data analysis of a beauty & personal care sales dataset — uncovering which sales channels, brands, product categories, and cities actually drive revenue, and where the money is being left on the table.

📄 **Read the full business case study → [CASE_STUDY.md](CASE_STUDY.md)**

## The question

Beauty & personal care brands sit on rich sales data (channel, pricing, ratings, marketing spend, returns) but rarely turn it into a clear view of *where growth is actually coming from*. This project answers that question end-to-end: from raw, messy sales data to a set of concrete, decision-ready recommendations.

## What's inside

- `data_analysis.ipynb` — full analysis notebook: data cleaning, exploratory analysis, channel/brand/product/geography breakdowns, correlation analysis, and visualizations
- `CASE_STUDY.md` — business-facing write-up of the findings and recommendations, written for a founder or marketing lead (not a data scientist)
- `images/` — key charts referenced in the case study
- `requirements.txt` — Python dependencies to reproduce the analysis

## Key findings (short version)

- **Instagram Shop** is the best-performing channel — highest revenue, best repeat-purchase rate (43.7%), and lowest return rate (18.0%)
- **Fragrance** subcategories generate outsized revenue relative to unit volume — a margin story, not just a volume one
- Marketing efficiency varies sharply by brand (₹1.89 revenue per ₹1 spend for the best performer vs. ₹1.53 for the weakest) — budget size doesn't guarantee returns
- Revenue leadership doesn't follow the usual "Tier-1 city" assumption — Chennai outperforms Delhi and Hyderabad

Full details, charts, and business recommendations are in [CASE_STUDY.md](CASE_STUDY.md).

## How to run it

```bash
pip install -r requirements.txt
jupyter notebook data_analysis.ipynb
```

## Tech stack

Python · pandas · NumPy · Matplotlib · Seaborn

## About

This project is part of a broader focus on data-driven analytics for beauty and personal care brands. If you run a beauty/D2C brand and want a similar teardown of your own sales data, feel free to reach out.
