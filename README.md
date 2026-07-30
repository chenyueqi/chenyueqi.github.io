# chenyueqi.github.io

Personal academic homepage of Yueqi Chen — **<https://chenyueqi.github.io/>**

A plain static site served by GitHub Pages. No build step, no framework.

## Layout

```
index.html       The entire page — bio, publications, talks, teaching
files/           Stylesheet, photos, CV
publications/    Paper PDFs and slide decks
talks/           Talk slides
.nojekyll        Tells Pages to serve files as-is, skipping Jekyll
```

## Updating

Edit `index.html`, commit, and push to `main`. GitHub Pages redeploys
automatically, usually within a minute.

```bash
git add -A && git commit -m "..." && git push
```

To add a paper, drop the PDF in `publications/` and link it from the
publication list in `index.html`.

## Notes

- Keep the file named `index.html`. GitHub Pages does not serve `index.htm`
  as a directory index.
- Do not delete `.nojekyll`. Without it, Pages runs the site through Jekyll,
  which ignores any path beginning with `_`.
- Previously hosted at `cusecurity.cs.colorado.edu/yueqichen/`.
