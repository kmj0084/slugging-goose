---
title: "Enterprise Workforce Laboratory"
date: 2026-11-02
summary: "Synthetic employment data for firm-level measurement, semantic modeling, and predictive analysis."
tags: ["Microeconomics", "Synthetic Data", "Workforce Analytics", "Survival Analysis"]
---
## A deliberately separate firm-level model

Economy-wide labor statistics describe the aggregate outcome of decisions, while enterprise systems record the administrative details of employment relationships. This project uses **synthetic enterprise records**, not confidential employer data, to demonstrate how those details can be modeled.

## Enterprise semantic model

{{< portfolio-image src="images/owas/enterprise-semantic-model.webp" alt="Power BI model diagram with person, job, organization, and date dimensions alongside assignment history, month-end headcount, employment spells, compensation events, leave episodes, and recruiting applications." caption="Synthetic enterprise Power BI model (development snapshot). Dimensions and event/snapshot facts remain separate to preserve their distinct grains. Some date relationships are inactive and must be addressed deliberately in measures." >}}

The model distinguishes **people, employment spells, assignments, time-bound snapshots, compensation events, leave episodes, and applications**. These entities represent different analytical units and should not be merged into a single generic employee table.

The diagram includes:
- Dimensions for person, job, organization, and date.
- Employment spell, assignment history, and workforce month-end facts.
- Compensation events, leave episodes, and recruiting applications.
- DAX measures for headcount, hires, separations, and workforce reconciliation.

## Analytical questions

How sensitive is turnover to the selected separation events and denominator? How do month-end counts differ from exposure-based measures? What changes when a model uses employment spells and time-varying covariates rather than a one-row-per-person extract?

## Modeling roadmap

The synthetic dataset is intended to support reproducible data-quality tests, descriptive dashboards, survival modeling, and predictive diagnostics. Any reported model performance will require actual fitted results and documented validation.

**Status:** Architecture under development. The diagram demonstrates structure; it does not claim deployed forecasting or prediction performance.
