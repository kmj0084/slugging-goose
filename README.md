# slugging-goose

Source for [keeganstimeseries.com](https://keeganstimeseries.com), Keegan Johnson's applied analytics and research portfolio.

The repository name **slugging-goose** is intentionally retained.

## Site architecture

- Hugo / Hugo Blox Academic CV theme
- Content in `content/`, site settings in `config/_default/`
- Netlify configuration in `netlify.toml`
- Existing R Markdown posts and R project assets retained

## Portfolio refresh (2026)

The homepage is oriented toward project evidence: OWAS methodology, workforce economics data architecture, synthetic enterprise modeling, and earlier applied statistics work.

**OWAS is a separate initiative.** The portfolio introduces and links to it; it does not speak for external standards bodies. Work-in-progress pages intentionally avoid invented metrics, results, and deployment claims.

## Development

Install Hugo compatible with the site's theme/modules, then run:

```sh
hugo server -D
```

Netlify currently builds using `hugo` and publishes `public/`. Verify a Deploy Preview before merging changes to `main`. Do not add a resume PDF link unless an actual current PDF exists at `static/uploads/resume.pdf`.

## Publishing checklist

1. Verify Netlify deploy preview and internal links.
2. Update project pages with verified screenshots, reproducible examples, and direct OWAS repository links.
3. Review the bio and employment timeline against the current resume.
4. Add technical case studies only when their code, findings, and disclosure permissions are established.
