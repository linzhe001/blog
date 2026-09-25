# Research Notes — Linzhe Jiang

An independent blog at `https://linzhe001.github.io/blog/`, built with [AstroPaper](https://github.com/satnaing/astro-paper) (MIT). The publication and project lists live on my [academic homepage](https://linzhe001.github.io/) and [project site](https://linzhe001.github.io/projects/).

Write posts in `src/content/posts/`. The bilingual article uses a lightweight language switch in `src/layouts/Layout.astro`; the original Jekyll permalink is retained as a static alias under `src/pages/2026/`. The Astro `base` is `/blog`.

Run `npm ci && npm run build`; GitHub Actions publishes `dist/` to GitHub Pages. Please preserve references and revision histories when updating clinical or research claims.

### Article citations

For a citation preview and a link to the bibliography, give each reference list item a unique ID such as `ref-en-1` or `ref-zh-1`, then link the inline number with `<a class="citation-link" href="#ref-en-1" aria-label="Reference 1">1</a>` inside square brackets. Grouped citations link each number separately, e.g. `[3,4,5]`. Use the matching language prefix so the English and Chinese references cannot be confused. The post layout reads the cited reference text for mouse hover and keyboard focus previews; English HTML links still navigate without JavaScript (Chinese display already requires the language-switch script).
