# BenBullinger.github.io

Personal website of Ben Bullinger, served by GitHub Pages at https://benbullinger.github.io.

Plain static files. GitHub Pages serves the `main` branch from the repository root, and `.nojekyll` turns off the Jekyll build.

## Preview

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765.

## Publish

Do not publish yet. A paper is under double-blind review, and the site must stay offline until that review has ended.

Until then the site lives in the private repository `BenBullinger/personal-website`. The name is deliberate: a repository called `BenBullinger.github.io` can be served by GitHub Pages as a public site, even when the repository is private.

When the review is over, rename the repository to `BenBullinger.github.io`, make it public, and turn on GitHub Pages for the `main` branch.
