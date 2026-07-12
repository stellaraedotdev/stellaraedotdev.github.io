# Stellarae Company Website

-- This repository is under review --
It has appeared that the outside developer that has been hired for this site may have used gen-AI to create this site in it's entirety. We do not stand for this and as such a review is being conducted to substatiate these claims.
Myself (@Env-Ir0n) had no hand in creating this site and simply used my account to add the commits to github as they came into the internal repository.
Thank you for your patience and reporting.

## Pages

- `index.html`: Landing page
- `projects.html`: Open source projects for identity and authorization
- `about.html`: Company mission centered on open source commitment
- `solutions.html`: Adoption patterns for different team profiles
- `contact.html`: Contact channels for support and collaboration
- `styles.css`: Shared visual system

## Local Preview

From repository root:

```bash
python3 -m http.server 8787 --directory STELLARAE
```

Open `http://127.0.0.1:8787`.

## GitHub Pages

A dedicated workflow publishes this directory to GitHub Pages:

- `.github/workflows/company-pages.yml`

Note: If another Pages workflow is also active, the last deployed artifact becomes the active site.
