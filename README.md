# Zeke Horton — Portfolio Site

A single-page personal site built with plain HTML, CSS, and JavaScript — no
build tools required.

## Structure

- `index.html` — page content
- `styles.css` — styling (responsive, light/dark aware)
- `script.js` — mobile nav toggle + footer year
- `assets/Zeke_Horton_Resume.pdf` — downloadable resume

## Running locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`.
4. Save — the site will be live at `https://<username>.github.io/<repo>/`
   within a minute or two.
