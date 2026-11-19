# Daiku – official website

Static website for Daiku, published with GitHub Pages. It contains only public pages (no application code, configuration or credentials).

| File | Page | URL once GitHub Pages is enabled |
|---|---|---|
| `index.html` | Home | https://jaimegarciardgz-art.github.io/daiku-site/ |
| `terms/index.html` | Terms of Service | https://jaimegarciardgz-art.github.io/daiku-site/terms/ |
| `privacy/index.html` | Privacy Policy | https://jaimegarciardgz-art.github.io/daiku-site/privacy/ |
| `assets/style.css` | Shared styles | — |

All links are relative, so the site works under the `/daiku-site/` path. `.nojekyll` makes GitHub Pages serve every file as-is.

## GitHub Pages

Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)`.

## TikTok URL prefix verification

1. In TikTok for Developers, open the app → *URL properties* (verify a URL prefix) and enter `https://jaimegarciardgz-art.github.io/daiku-site/`.
2. Download the signature file TikTok provides (`tiktok…txt`).
3. Add it unchanged to the repository root (next to `index.html`), commit and push.
4. Check that `https://jaimegarciardgz-art.github.io/daiku-site/<file name>` shows the file, then press *Verify* in TikTok.

The file must stay in the repository after verification.
