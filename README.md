# My Grandpa's Collection — The Julio Paez Collection

A tribute to Grandpa Julio's handmade cut-out books of Popular Mechanics DIY projects.

## Design

The public homepage is a scrapbook-style book cover with three decades as separate volumes. Projects are displayed as two-page spreads:

- **Original clipping (left):** a clearly labeled, newly created editorial recreation with actual catalog title, issue, starting page, inline visual, and link to the original issue.
- **Modern engineering notes (right):** five independent redesign considerations, separate from the original source.

There is one searchable catalog in `projects.json`. Decade and category filters require no build process or server.

### Original scanned pages

No full scans of copyright-protected Popular Mechanics pages have been added. The published clippings are **not** copied pages: they are typeset editorial recreations using short original titles and independently authored summaries. Full or substantial scanned clippings should be uploaded only if permission, license, or public-domain status permits. Each catalog entry should acquire optional `sourceImage`, `sourceImageLicense`, and `sourceImageAttribution` fields when rights are verified.

### Julio's photograph

The memorial layout provides a portrait slot at `assets/julio-paez.jpg`. The image is not bundled in this repository yet. Place the family-authorized photo at that exact path to show it on the public website. The page has an accessible placeholder until it is present.

## Publishing

GitHub Pages workflow: `.github/workflows/pages.yml`. Settings > Pages must use **GitHub Actions**. Every push to main should deploy after Pages is enabled. Verify successful Actions run and deployed URL before claiming a release.

## Curation

The scheduled ChatGPT curation task is separate from the GitHub workflow; it does not automatically commit articles. Append only source-verified records to `projects.json`, and mark plans pending until original article details have been inspected.

## Safety

No new annotation is a validated construction plan. Source documents and independent designs need modern engineering and safety assessment for any fabrication.

Not affiliated with Popular Mechanics or Hearst.
