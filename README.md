# hum-site

Public static site for **hum** (privacy policy, support). The main app repo stays private.

Support email: **humansaiops@gmail.com** (also on [support.html](support.html) and in the privacy policy).

## Live site

- **Home:** [https://parth4.github.io/hum-site/](https://parth4.github.io/hum-site/)
- **About:** [https://parth4.github.io/hum-site/about.html](https://parth4.github.io/hum-site/about.html)
- **Privacy policy:** [https://parth4.github.io/hum-site/privacy.html](https://parth4.github.io/hum-site/privacy.html)
- **Support:** [https://parth4.github.io/hum-site/support.html](https://parth4.github.io/hum-site/support.html)

The Expo app reads `expo.extra.humInviteUrl` in the main **hum** project — set to the home URL above so **Share hum** includes this link.

## GitHub Pages

Source: branch **main**, folder **/** (root).

## Brand icon

Favicon and header mark use **`assets/icon.png`** — the same file as the hum app’s Expo `icon` / launcher artwork.

- After updating **`hum/assets/icon.png`**, run **`D:\hum\scripts\sync-hum-site-icon.ps1`** (or copy that PNG into `assets/` here).
- Notes: `assets/ATTRIBUTION.txt` (legacy CC hummingbird vector is documented in the main **hum** repo only).

## Clone & edit

```bash
git clone https://github.com/parth4/hum-site.git
cd hum-site
# edit HTML/CSS, then:
git add -A && git commit -m "Update site" && git push
```
