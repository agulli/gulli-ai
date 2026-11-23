# gulli.ai

Personal website for Antonio Gullí — a static single-page site.

## Structure

- `site/index.html` — the page
- `site/assets/` — book cover images
- `netlify.toml` — tells Netlify to publish the `site/` folder

## Local preview

```bash
cd site
python3 -m http.server 8777
# open http://localhost:8777
```

## Deploy

Hosted on Netlify. Pushing to the `main` branch auto-deploys.
To edit the site, change files under `site/`, then commit and push.
