# Vaalmiki-Ramayana — published site

This repository contains **only the rendered static website** for the Valmiki Ramayana reading edition. It is published with GitHub Pages from the `main` branch, root directory.

The Quarto source files (`.qmd`, `_quarto.yml`, data, styles, scripts) are **not** stored here. They are kept separately while the content continues to be developed.

## Updating the site

From `E:\RamayanaNW`, run:

```powershell
.\publish.ps1
```

This renders the Quarto project, mirrors `_site` into this folder, and commits and pushes the result. Use `.\publish.ps1 -SkipRender` to publish the existing `_site` without re-rendering, and `.\publish.ps1 -NoPush` to commit locally only.

Live site: https://nmt2722.github.io/Vaalmiki-Ramayana/
