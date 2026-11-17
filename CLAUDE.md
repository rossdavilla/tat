# TAT Images (`tat`)

Picture cards for a Thematic Apperception Test demonstration, used as a textbook/teaching
resource. Live at <https://rossdavilla.github.io/tat/>.

## What is actually here

```
TATimage1.png   the three picture cards
TATimage2.png
TATimage3.png
index.html      effectively empty (2 bytes) — there is no page
LICENSE
```

**This repo is an image host, not an app.** The cards are linked directly, e.g.
<https://rossdavilla.github.io/tat/TATimage1.png>, which is why the site directory's entry points
at `TATimage1.png` rather than `index.html`.

If Ross asks for a page here — a slideshow, a single-card-at-a-time view — that is a new app, and
it needs its own entry in `data/sites.json` in the
[`rossdavilla.github.io`](https://github.com/rossdavilla/rossdavilla.github.io) repo. Until then,
do not "fix" the empty `index.html` by inventing a landing page.

Adding a card means adding `TATimage<N>.png` and nothing else.

## Publishing

GitHub Pages serves `main` from the repository root, so a push to `main` is the deploy.
