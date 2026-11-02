---
title: "Keegan Johnson | Applied Analytics"
type: landing
sections:
  - block: hero
    content:
      title: "Workforce analytics, econometrics & data engineering"
      text: |
        I build analytical systems that connect reliable data, statistical methods, and decisions. My work spans people analytics, labor economics, predictive modeling, and business intelligence.

        **Explore the projects below** for methodology, implementation details, and links to source material.
      cta:
        label: "Explore projects"
        url: "#projects"
      cta_alt:
        label: "GitHub"
        url: "https://github.com/kmj0084"
    design:
      background:
        gradient_start: "#12304a"
        gradient_end: "#24627c"
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: "About"
      username: admin
  - block: markdown
    id: projects
    content:
      title: "Selected work"
      text: |
        ### [Open Workforce Analytics Standard (OWAS)](/project/owas/)
        **Measurement systems · R · SQL · Power BI · reproducible data pipelines**

        An independent, evidence-based effort to make workforce metrics more transparent and implementable. The project distinguishes authoritative sources from methodological choices and recommendations.

        ### [Workforce economics dashboard and data architecture](/project/workforce-economics/)
        **BLS · Census · R · Parquet · dimensional modeling · Power BI**

        A multi-source macro workforce data model covering employment, labor flows, compensation, and business dynamics, with explicit attention to geography, industry, periodicity, and seasonal adjustment.

        ### [Enterprise workforce modeling laboratory](/project/enterprise-workforce/)
        **Synthetic data · event modeling · time series · survival analysis**

        A developing environment for demonstrating workforce event models, headcount reconstruction, turnover measures, and predictive analyses without exposing employer records.

        ### [Empirical Bayes baseball analysis](/post/2023-12-31-estimating-obp-with-empirical-bayes/)
        **R · statistical estimation · sabermetrics**

        An earlier applied statistics project retained as part of the broader portfolio.
    design:
      columns: "1"
  - block: markdown
    id: methods
    content:
      title: "How I work"
      text: |
        **Analytics:** econometrics, survival analysis, experimental methods, forecasting, and statistical inference.

        **Engineering:** SQL, R, Python, Snowflake, dbt, reproducible pipelines, data quality tests, and semantic modeling.

        **Delivery:** Power BI, Tableau, technical documentation, stakeholder-facing reporting, and privacy-aware analytics.

        I emphasize definitions, eligible populations, time structure, reproducibility, and the limitations of the available evidence.
    design:
      columns: "1"
  - block: collection
    id: writing
    content:
      title: "Writing and research"
      count: 6
      filters:
        folders:
          - post
        exclude_future: true
      order: desc
    design:
      columns: "2"
      view: compact
  - block: markdown
    id: contact
    content:
      title: "Connect"
      text: |
        See my [GitHub](https://github.com/kmj0084) and [LinkedIn](https://www.linkedin.com/in/kmj0084/) for current work and professional contact.
    design:
      columns: "1"
---
