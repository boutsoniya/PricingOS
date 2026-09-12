# PricingOS — Product Case Study

## Problem

Pricing decisions for AI products are unusually difficult because willingness-to-pay, conversion, usage and inference cost move together. A spreadsheet can calculate revenue, but it rarely helps a PM explain the tradeoff or define the experiment needed to validate it.

## Product hypothesis

A pricing decision workspace should connect four layers:

1. **Value** — what customers pay for and how that value scales.
2. **Demand** — how price changes affect conversion and retention.
3. **Economics** — how usage changes cost-to-serve and gross margin.
4. **Evidence** — how to test the recommendation before global rollout.

## Default scenario

The synthetic Pro-plan scenario models a move from $49/month to $59/month with 1,000 AI credits. The example assumes a conversion decline but materially higher ARPU and gross margin.

The interface deliberately labels the result as a scenario rather than a forecast. That distinction is important: pricing models should make assumptions visible and experiments should resolve uncertainty.

## PM decision

**Recommendation: TEST BEFORE ROLLOUT.**

Run a controlled 50/50 pricing experiment. Optimize for net revenue per visitor, with 30-day churn and AI cost per active account as guardrails.

## Success criteria

- Net revenue per visitor: at least +8%
- 30-day churn: no more than +0.5 percentage points
- Gross margin: remain above the 70% guardrail
- AI cost per active account: monitored by cohort

## Why this is portfolio-grade

PricingOS demonstrates commercial judgment, quantitative product thinking, experimentation, AI economics and executive communication in one workflow. It is intentionally more than a price calculator: it turns a monetization question into a decision and a validation plan.
