---
title: "Open Workforce Analytics Standard (OWAS)"
date: 2026-11-02
summary: "Evidence-based workforce measurement linking clear definitions to implementation."
tags: ["Workforce Measurement", "Applied Economics", "Data Engineering"]
---
## The question

When two organizations report the same workforce metric, are they measuring the same thing?

OWAS is an **independent, evidence-based reference project** on workforce metrics, temporal structure, data architecture, and implementation. It distinguishes authoritative external standards, published research, common practices, OWAS recommendations, and open methodological questions. Its recommendations are not presented as ISO or SHRM requirements.

## From definition to implementation

The analytical approach specifies, as applicable, metric purpose, numerator, denominator, eligible population, grain, reference period, aggregation, variants, edge cases, data quality, privacy, and external sources.

Technical work developed alongside the reference includes:
- R ingestion, transformations, validations, and Parquet exports for public labor-market statistics.
- A Power BI semantic model that preserves source metadata and incompatible grains.
- A separate **synthetic enterprise** model covering persons, employment spells, workforce snapshots, and event-level facts.
- Dashboard views for employment, labor movement, and compensation.

## Examples of the implemented work

See [Workforce economics](/project/workforce-economics/) for the public-data dashboards and [Enterprise workforce laboratory](/project/enterprise-workforce/) for the synthetic semantic model. These examples demonstrate technical implementation; they are not themselves formal OWAS requirements.

## Why the micro/macro connection matters

Within a firm, headcount, hiring, separation, and compensation begin as administrative transactions. At the level of the economy, related phenomena appear as employment stocks, labor flows, and wage or cost indexes. Questions connecting these levels are useful, but inference must respect their very different data-generating processes.

**Status:** Independent work in active development. Evidence and methodology should be assessed at the specific metric or study level rather than as a blanket endorsement of the project.
