# Forticam secure services

Smart Surveillance, Smarter Protection For A Safer Spaces.

Static website for Forticam CCTV and smart security. No build step.

- `index.html` is the page and `assets/` holds the catalog images and promo video.
- `forticam-website-source (1).zip` is the original source archive, kept for reference.
- `netlify.toml` tells Netlify to publish the repo root with no build command.

## Run locally

```bash
python3 -m http.server 8000
```

## Publish on Netlify

Import this repo in Netlify, leave the build command empty and set the publish directory to `.`. Every push to `main` then deploys automatically.
