# Guardian landing page

The public landing page for Guardian, an open-source guardian for WordPress sites, by Double Geste. Early development: nothing is on sale yet.

One static file, `index.html`, with no build step and no external requests.

## Preview

```bash
python3 -m http.server 8000
```

## Waitlist

The form does nothing until `WAITLIST_ENDPOINT` is set at the top of the script in `index.html`. It sends a JSON POST with `email` and `role`. If you use a third-party form service, mention it in your privacy policy.

## Publishing

GitHub Pages serves the `main` branch from the repository root. Pushing to `main` updates the site.
