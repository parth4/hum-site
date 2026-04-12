# hum-site

Public static site for **hum** (privacy policy, support). The main app repo stays private.

## GitHub Pages

1. Push this repo to GitHub (see below).
2. On GitHub: **Settings → Pages → Build and deployment → Source:** **Deploy from a branch**.
3. Branch **main**, folder **/** (root), Save.
4. Site URL: `https://<user>.github.io/<repo>/`

Use these in App Store / Google Play and in the app (`humInviteUrl`):

- Home: `https://<user>.github.io/<repo>/`
- Privacy: `https://<user>.github.io/<repo>/privacy.html`

## First push (replace YOUR_USER)

```bash
cd hum-site
git init
git add .
git commit -m "Initial public site for hum"
git branch -M main
git remote add origin https://github.com/YOUR_USER/hum-site.git
git push -u origin main
```

If the empty repo already exists on GitHub, use its URL as `origin`.
