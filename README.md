# slugging-goose

Personal portfolio source for [keeganstimeseries.com](https://keeganstimeseries.com). The **slugging-goose** repository name is intentionally retained.

## Positioning

Applied economics spanning firm-level workforce decisions and aggregate labor markets. Personal portfolio and independent OWAS methodology are distinct publications.

## Architecture

Hugo Blox / Hugo, Netlify deployments, Markdown project pages, and legacy R Markdown source retained in Git history.

## Screenshots

Four vetted OWAS visual assets are referenced in the portfolio pages. Upload the following files to `static/images/owas/` **on the feature branch**:

- `macro-overview.webp`
- `workforce-movement.webp`
- `compensation.webp`
- `enterprise-semantic-model.webp`

The `portfolio-image` shortcode checks for the asset's existence; it will not display a broken image if an asset has not yet been uploaded. The screenshots are examples from OWAS v0.4 and the synthetic enterprise model, not screenshots of a live public dashboard.

## Content controls

- Never equate CES jobs with CPS persons, or compensation indexes with observed earnings levels.
- Preserve the difference between public macro statistics and simulated enterprise data.
- Do not claim ISO/SHRM endorsement of OWAS recommendations.
- Do not publish confidential employer records, proprietary models, or employee microdata.
- Only publish a resume PDF after explicitly approving public display of the included contact details.

## Publication flow

Feature branch → Netlify preview → review → merge to main.

## Planned additions

- Publish annotated R validation and quality-control examples.
- Add an updated public macro model diagram and reproducible source registry.
- Add research articles only after analysis and limitations are documented.
