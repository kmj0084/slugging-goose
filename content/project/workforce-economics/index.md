---
title: "Workforce Economics: Public Data and Semantic Modeling"
date: 2026-11-02
summary: "Making multiple labor-market statistical programs analytically usable without erasing their differences."
tags: ["Labor Economics", "R", "Power BI", "Data Architecture"]
---
## The question

What can we infer about labor-market adjustment when employment, labor flows, compensation, and business dynamics are viewed together?

## Implemented architecture

The current macro workflow draws on BLS CES, CPS, JOLTS, and ECI, and Census QWI and J2J, with BED and BDS being added. These programs describe different universes and vary in grain, temporal coverage, and seasonal adjustment.

Work completed includes:
- R ingestion and cleaning with source-specific checks.
- Validation of observation periods and metric metadata.
- Parquet outputs for a Power BI dimensional model.
- Reporting views for macro overview, workforce movement, and compensation.

## Why modeling decisions matter

There is no universal join key that makes quarterly establishment flows, monthly household employment, and quarterly employer compensation directly comparable. A careful model preserves source and measurement context and treats transformations as analysis rather than invisible preprocessing.

## Next publication steps

Add a schema diagram, reproducible QA summary, dashboard screenshots, and one focused research question supported by the verified outputs.

**Evidence status:** Architecture and reporting are in development. No causal findings are asserted here.
