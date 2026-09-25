# Research Notes — Linzhe Jiang

An independent blog at `https://linzhe001.github.io/blog/`, built with [AstroPaper](https://github.com/satnaing/astro-paper) (MIT). The publication and project lists live on my [academic homepage](https://linzhe001.github.io/) and [project site](https://linzhe001.github.io/projects/).

Write posts in `src/content/posts/`. The bilingual article uses a lightweight language switch in `src/layouts/Layout.astro`; the original Jekyll permalink is retained as a static alias under `src/pages/2026/`. The Astro `base` is `/blog`.

Run `npm ci && npm run build`; GitHub Actions publishes `dist/` to GitHub Pages. Please preserve references and revision histories when updating clinical or research claims.
