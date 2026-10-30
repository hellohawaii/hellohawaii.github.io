# Template provenance

- Direct source: https://github.com/gibrantaowu/homepage
- Imported commit: `90d93990f73bf77e919dd630425f5bf3db9bc1b2`
- GitHub fork parent: https://github.com/academicpages/academicpages.github.io
- License: MIT; original copyright and license preserved in `LICENSE`.

This version uses the reference repository's actual Jekyll templates. `_layouts/`, `_sass/`, `assets/css/main.scss`, and its bundled JavaScript are reused. The original layout, fonts, default light theme, author sidebar, and publication-card styling remain in use. The repository README and copied setup README have been removed at the user's request.

Personalization:

- Replaced the author configuration, biography, news, and publications with Shuzhi Liu's material. Unrelated demo pages, publications, portraits, and files were not imported.
- Retained the publication-card include, adding optional PDF, code, and downloadable BibTeX links.
- The optional CV download is disabled, and no CV document is included in this repository.
- Removed external MathJax, Mermaid, and polyfill scripts because this page contains no formulas or diagrams requiring them. The template's local JavaScript remains in use.
- Uses the user's photograph from https://natural-programming-lab.github.io/people/ .
- HyperPGNN's thumbnail uses Figure 2 from the final paper supplied by the user, with white margins to show the whole pipeline in the existing card component.
- News, Education & Experience, and Contact are retained in Markdown behind disabled front-matter flags, as requested.
- Set the production origin to https://hellohawaii.github.io and use an empty base path for the personal GitHub Pages site.

The same Jekyll source can be built with the original `Gemfile`, including `github-pages`. GitHub Actions builds the source and publishes `_site/` to GitHub Pages.
