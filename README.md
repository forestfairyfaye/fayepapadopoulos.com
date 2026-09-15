# fayepapadopoulos.com

Portfolio site for Sofia Faye Papadopoulos, graphic designer, Berlin.

One static page, no build step. `index.html` carries its own CSS and JS.

## Local preview

Any static server from the repo root, for example:

    npx serve .

## Deployment

Netlify deploys this repo from `main`. There is no build step: `netlify.toml`
publishes the repo root.

Asset paths are relative, so the page works at a domain root and under a
subpath. Once fayepapadopoulos.com is registered, add it as a custom domain
in Netlify.
