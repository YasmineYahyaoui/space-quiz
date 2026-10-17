# Orbit: Space Exploration Quiz

Orbit is a single-page space exploration quiz. Answer ten multiple-choice questions, learn a space fact after each answer, and track your personal best between visits in your browser.

## Run locally

The app is a static website with no build step or dependencies. From the repository directory, start a local web server:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser. You can also open `index.html` directly, though using a local server more closely matches the deployed site.

## Deployment

The site is deployed to GitHub Pages by the workflow in `.github/workflows/pages.yml` whenever changes are pushed to `main`. Pull requests run the static-site build and validation without deploying. The deployment URL is available in the workflow run summary and in the repository's Pages settings.
