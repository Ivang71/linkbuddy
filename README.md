# Link Buddy

This repo contains:

- `TBCPL/`: the original static site and link data
- `LinkBuddy/`: a simpler, non-technical “clone” that lists the same links

## Preview Link Buddy

Because the page loads `links.json` with `fetch`, you should serve it with a local web server.

From the repo root:

```bash
python3 -m http.server 5173
```

Then open `http://localhost:5173/LinkBuddy/`.

