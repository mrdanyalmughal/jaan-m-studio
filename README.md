# Jaan M. Studios

Marketing website for **Jaan M. Studios** — painting & interior design, Lahore, since 1984.

A single, self-contained `index.html` (HTML/CSS/JS, no build step) featuring an
Apple/Nike-style scroll experience: a tilt-reveal hero and a real-photo,
scroll-scrubbed "raw → painted → furnished" transformation.

## Deploy

- Hosted on **Netlify** with continuous deployment from this repo.
- Any push to `main` automatically publishes the live site.

## Editing

Everything lives in `index.html`. Search for `IMG:` to find every photo slot.
The 5 transformation frames are the `.tx-img` elements (and labels in the
`TX_STAGES` array in the script) — swap those URLs for your own room sequence.

## Local preview

Just open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
