# Personal website

Personal website of Ben Bullinger, served by GitHub Pages.

Plain static files. GitHub Pages serves the `main` branch from the repository root, and `.nojekyll` turns off the Jekyll build.

## Preview

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765.

## Site on and off

On: Settings, Pages, "Deploy from a branch", branch `main`, folder `/ (root)`.

Off: Settings, Pages, the "..." menu next to the site address, "Unpublish site".
