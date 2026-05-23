# SUPER IRNET Hugo Site

This repository contains a Hugo rebuild of the copied site in `superirnet_mirror`.

## Local Preview

Install Hugo, then run:

```sh
hugo server --disableFastRender
```

The site keeps the original `.html` URLs through `uglyURLs = true`, so links such as `about.html` and `workshop2026.html` continue to work.

## Structure

- `content/`: pages extracted from the mirrored HTML files
- `layouts/`: shared Hugo templates
- `assets/css/site.css`: rebuilt responsive visual design
- `static/`: copied images, PDFs, posters, talks, and travel forms
