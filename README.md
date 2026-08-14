# The Working Cookbook

Personal recipes published with [Julia](https://github.com/aleivag/julia), a
static cookbook generator and local-first cooking companion.

[Browse the published cookbook on GitHub Pages.](https://aleivag.github.io/the-working-cookbook/)

## Local preview

```bash
python -m pip install git+https://github.com/aleivag/julia.git
julia serve .
```

The static site is deployed to GitHub Pages whenever `main` changes.

## Feasts

Authored menus live in `feasts/`. Build them with:

```bash
julia feast build .
```

Each feast produces a guest menu, kitchen booklet, and shopping list alongside
its web page.
