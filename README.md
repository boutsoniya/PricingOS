# PricingOS

### AI-Powered Monetization Decision Engine

> **Price → Demand → Usage → AI cost → Margin → Experiment → Decision**

PricingOS is a product-management portfolio project for answering one practical question:

**Given customers, usage, costs and a proposed price change, what should we actually charge — and what happens if we change it?**

## What it demonstrates

- Pricing strategy across subscription, usage and hybrid models
- Revenue, ARPU, ARR and gross-margin simulation
- AI cost-to-serve and margin-compression analysis
- Customer segmentation by willingness-to-pay and usage
- Pricing experiments with explicit guardrails
- Executive-ready decision memos rather than calculator-only output

## Product thesis

AI products make pricing harder because customer value and delivery cost can both vary with usage. PricingOS treats monetization as a product decision: model the economics, expose the tradeoffs, then validate the recommendation with a controlled experiment.

## Core workflow

1. **Pricing Studio** — configure price, customer base, AI allowance and cost assumptions.
2. **Revenue Simulator** — translate demand assumptions into revenue and margin outcomes.
3. **Segments** — identify where willingness-to-pay and cost-to-serve diverge.
4. **Experiment Lab** — define primary metrics and guardrails before launch.
5. **Decision Memo** — turn the model into an executive recommendation.

## Default scenario

The synthetic workspace models a move from **$49 → $59/month + 1,000 AI credits**. The UI intentionally treats this as a scenario, not a financial forecast. The recommendation is to **test before rollout**.

## Portfolio documentation

- [Product Case Study](docs/PRODUCT_CASE_STUDY.md)
- [Metrics Framework](docs/METRICS.md)

## Stack

HTML • CSS • Vanilla JavaScript • Render

## Roadmap

- Scenario comparison and saved cases
- Cohort-level elasticity modeling
- Monte Carlo uncertainty ranges
- CSV import for real pricing data
- Pricing recommendation explainability
- AI-assisted decision memo generation

> All numbers in the default workspace are synthetic and intended to demonstrate product reasoning, not represent a real company's financial forecast.
