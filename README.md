# GovFlow Website

This is the codebase for the GovFlow website.

It is built using [Hugo](https://gohugo.io).

# Quickstart

1. Install Hugo: https://gohugo.io/getting-started/quick-start/

2. Clone the repo

3. Run `hugo serve`

# Build and Deploy

1. The site is built using a GitHub Action on each deploy to main. See `.github/workflows/deploy.yml`. The output of the build process is commited to the `gh-pages` branch.

2. On commit to the `gh-pages` branch, the site is served immediately using [GitHub Pages](https://pages.github.com). The file at `static/CNAME` determines the domain that is mapped for the site.

# Content

Inside the `content` directory you will see a listing of markdown files. Each is mapped to a page. E.g.: `features.md` is served at `/features/` on the site domain.
