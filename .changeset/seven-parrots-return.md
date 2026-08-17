---
'astro': patch
---

Fixes `astro build` failing with `TypeError: Missing parameter` for dynamic routes when using `build.format: 'preserve'` with `trailingSlash: 'always'`
