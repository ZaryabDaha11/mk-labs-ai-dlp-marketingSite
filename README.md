# MK Labs AI DLP — marketing site

The public marketing site for **MK Labs AI DLP**, a local, zero-network data-loss
prevention browser extension for AI chat (ChatGPT, Claude, Perplexity). This repo is
just the static website — a single `index.html` — meant to be served with **GitHub
Pages** and used as the product's website (e.g. for an Acquire.com listing).

> The extension itself (source code) lives in a separate private repository.

## What's here

- `index.html` — the complete landing page (self-contained: all CSS is inline; fonts
  load from Google Fonts). No build step, no dependencies.

## Publish it with GitHub Pages (2 minutes)

1. Create a new GitHub repo (public), e.g. `ai-dlp-site`, and add these files
   (`index.html` + this `README.md`) to the default branch (`main`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
5. Wait ~1 minute. Your site goes live at:
   `https://<your-username>.github.io/<repo-name>/`
6. Paste that URL into the Acquire.com "website" field.

### Optional: custom domain
If you own a domain, add it under **Settings → Pages → Custom domain**, create the
DNS records GitHub shows, and enable **Enforce HTTPS**. GitHub will add a `CNAME`
file to the repo automatically.

## Editing

- **Contact email:** search `zaryabdaha111@gmail.com` and replace if needed.
- **Product name / copy:** edit the text directly in `index.html`.
- **Colors / fonts:** the palette is defined as CSS variables in the `:root` block
  near the top of the `<style>` (teal accent `#0b6b5f`); fonts are Fraunces + IBM
  Plex, matching the product's trust collateral.
- The page is responsive (works down to phone width) and supports light/dark
  automatically via `prefers-color-scheme`.

## Notes

- No analytics or trackers are included, consistent with the product's privacy stance.
- All product claims use "reduces risk / detect / redact" language — no guarantees —
  matching the extension's own copy policy.
