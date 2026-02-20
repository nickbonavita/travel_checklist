# travel_checklist

Interactive travel checklist site with:
- 100 countries grouped by continent
- Click-to-expand country details
- Search/filter
- Visited-country highlighting with saved state

## Run locally

From the repo root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Publish as a website (GitHub Pages)

This repo now includes a GitHub Actions workflow in `.github/workflows/deploy-pages.yml`.

1. Push your latest changes to `main`.
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Wait for the `Deploy static content to Pages` workflow to finish.

Your site will be available at:
- `https://<your-username>.github.io/travel_checklist/`

If you later want a custom domain, you can add a `CNAME` file and configure DNS.
