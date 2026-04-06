# joelrajakumar.github.io

Personal site (GitHub Pages + Jekyll, [minimal theme](https://github.com/pages-themes/minimal)). **About**, **Research**, **CV**, and **Music** are separate pages (`index.html`, `research.html`, `cv.html`, `music.html`); shared navigation lives in `_includes/site-nav.html`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Editing

- **About:** `index.html` (profile links are at the bottom).
- **Research:** `research.html` (paper list and arXiv links).
- **CV:** `cv.html` and the PDF at `assets/cv.pdf`.
- **Music:** `music.html`.

## If `git push` says the remote has new commits

You probably edited or uploaded files on GitHub. From this folder run:

```bash
git pull origin main --no-rebase
```

Fix any merge conflicts (keep the version you want), then `git add` the files and `git commit`, then `git push`.

## CV file

The site links to `assets/cv.pdf`. Replace that file in the repo when you update your CV.
