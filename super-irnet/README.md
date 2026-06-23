# SUPER-IRNET Website

This repository manages the website of SUPER-IRNET.

## Local Preview

Install Hugo, then run:

```sh
hugo server --disableFastRender
```

The site keeps the original `.html` URLs through `uglyURLs = true`, so links such as `about.html` and `workshop2026.html` continue to work.

## Build

Generate the public site into `docs/`:

```sh
hugo --minify
```

The repository is configured with `publishDir = "docs"`, which is suitable for GitHub Pages deployments that serve from the `/docs` folder.

## Structure

- `content/`: pages extracted from the mirrored HTML files
- `layouts/`: shared Hugo templates
- `assets/css/site.css`: rebuilt responsive visual design
- `static/`: copied images, PDFs, posters, talks, and travel forms
- `docs/`: generated public site
