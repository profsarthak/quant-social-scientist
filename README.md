# The Quantitative Social Scientist — rendered site

This repository hosts the **published GitHub Pages site** for *The Quantitative Social
Scientist*, an intuition-first encyclopedia for quantitative social science research —
from basic probability through inference, econometrics, causal inference, and the
statistical-vs-predictive divide.

🔗 **Read it: [profsarthak.github.io/quant-social-scientist](https://profsarthak.github.io/quant-social-scientist/)**

## About this repo

The files here are **build output** — static HTML, figures, and assets rendered from a
[Quarto](https://quarto.org) project. They are generated, not edited by hand.

- **Source lives elsewhere** (private). All authoring, structure, and house style are
  maintained in the source repository; this repo only receives the rendered result.
- **Contents are overwritten on each publish.** Editing files here directly will be lost the
  next time the site is rendered and pushed.

## Structure

```
content/        Rendered articles, by track (overture, foundations, inference, …)
appendices/     Math and computing references
*.html          Top-level pages (home, about)
.nojekyll       Tells GitHub Pages to serve files as-is (no Jekyll processing)
```

For the philosophy, curriculum, and how the book is written, see the source project.
