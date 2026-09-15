# fayepapadopoulos.com

Portfolio site for Sofia Faye Papadopoulos, graphic designer, Berlin.

One static page, no build step. `index.html` carries its own CSS and JS.

## Local preview

Any static server from the repo root, for example:

    npx serve .

## Deployment

GitHub Pages serves `main` from the repo root. `.nojekyll` turns off Jekyll
processing.

Asset paths are relative, so the page works both under a project-site subpath
and at a domain root. Once fayepapadopoulos.com is registered, add a `CNAME`
file containing that domain and point its DNS at GitHub Pages.
