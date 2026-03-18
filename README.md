# SwiftDrop Nigeria — Logistics Analytics Case Study

## Overview

A complete end-to-end product analytics project for a fictional Nigerian
logistics and delivery company called SwiftDrop, analysing 25,000 customers,
196,191 orders, and 143,661 funnel events across October 2023 to September 2024.

This project demonstrates logistics data analytics — from revenue decline
root cause analysis and churn prediction to funnel optimisation and
channel quality scoring.

---

## Business Problems Solved

| Problem | Description |
|---|---|
| Revenue Decline | Why is revenue declining despite growing user numbers? |
| Churn Prediction | Which customers are most likely to churn next month? |
| Funnel Drop-off | Where is the product losing customers in the booking journey? |
| Channel Quality | Which marketing channel brings the best customers? |
| Repeat Orders | How do we increase repeat usage and customer lifetime value? |

---

## Key Findings

- Discount removal in April 2024 caused mass churn — revenue per user actually increased but marginal users left immediately
- A payment UX change in February 2024 collapsed end-to-end funnel conversion from 8.2% to 2.8% — a 66% deterioration
- TikTok Ads users have an average LTV of ₦22,892 vs Referral users at ₦47,257 — a 2x difference
- 19,451 customers (77.8%) have a churn risk score above 70
- E-commerce Sellers average 12.8 orders and ₦60,715 LTV — 17x more than Individual Senders

---

## Project Files

| File | Description |
|---|---|
| `SwiftDrop_Analysis.ipynb` | Full Python analysis in Jupyter notebook |
| `SwiftDrop_Dashboard.html` | Interactive dashboard — download and open in any browser |
| `swiftdrop_users.csv` | 25,000 synthetic customer records |
| `swiftdrop_orders.csv` | 196,191 order records across 5 delivery types |
| `swiftdrop_funnel.csv` | 143,661 funnel events from app open to order placed |

---

## How to View the Dashboard

1. Download `SwiftDrop_Dashboard.html`
2. Open it in any browser — Chrome, Firefox, or Edge
3. No installation or internet connection needed

---

## How to Run the Analysis
```bash
pip install pandas numpy matplotlib jupyter

jupyter notebook
```

Open `SwiftDrop_Analysis.ipynb` and run all cells from top to bottom.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Python with pandas | Data generation, cleaning, and analysis |
| matplotlib | Data visualisation and chart generation |
| Jupyter Notebook | Analysis environment |
| Chart.js | Interactive dashboard visualisations |
| GitHub | Version control and portfolio hosting |

---

## Dataset Note

This is a synthetic dataset generated with realistic Nigerian logistics
patterns — including discount policy effects on churn, payment UX friction
introduced mid-year, channel-based LTV differences, and segment-specific
repeat order behaviour. All names, IDs, and figures are fictional.

---

## Skills Demonstrated

Churn analysis, funnel analysis, cohort analysis, channel LTV scoring,
repeat order analysis, discount impact modelling, revenue trend analysis,
Python, matplotlib, Jupyter, Chart.js.
```

---
