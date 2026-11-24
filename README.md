# DevDefend · Public Article Edition

**[Open DevDefend and read the articles →](https://techieengineer.github.io/devdefend-preview/)**

This is the lightweight public edition of DevDefend, a blog about software and security. Choose an article from the homepage to read its text, code examples, callouts, and illustrations. No account is required.

## Looking for the application?

The [DevDefend source repository](https://github.com/TechieEngineer/DevDefend) contains the interactive platform: reader accounts, comments, likes, the Markdown author workspace, image uploads, moderation, and the admin audit dashboard.

**[Fork the full DevDefend application](https://github.com/TechieEngineer/DevDefend/fork)** · **[Fork this static preview](https://github.com/TechieEngineer/devdefend-preview/fork)**

| If you want to… | Go here |
|---|---|
| Read the published articles | [Open the website](https://techieengineer.github.io/devdefend-preview/) |
| Understand the stack or run your own blog | [Read the application README](https://github.com/TechieEngineer/DevDefend#readme) |
| Inspect the exported HTML and media | Browse this repository |

## How this edition is published

The maintainer exports published articles from DevDefend, reviews the generated files, and publishes the snapshot through GitHub Pages. Uploaded images used by the exported posts are copied into `media/`. Edits and unpublishing decisions appear here after the next export is published.

`index.html` is the article index. Individual `article-*.html` files are reading pages. `.nojekyll` tells GitHub Pages to serve the generated files directly.

## Preview a fork locally

From the cloned repository, run:

    python -m http.server 4173 --bind 127.0.0.1

Then open `http://127.0.0.1:4173`. A database, account, and API server are unnecessary for this edition.

Source-code reuse and republication of written articles may have different licensing terms. Check the relevant license before redistributing content.