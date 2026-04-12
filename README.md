# hum-site

Public static site for **hum** (privacy policy, support). The main app repo stays private.

## Live site

- **Home:** [https://parth4.github.io/hum-site/](https://parth4.github.io/hum-site/)
- **Privacy policy:** [https://parth4.github.io/hum-site/privacy.html](https://parth4.github.io/hum-site/privacy.html)
- **Support:** [https://parth4.github.io/hum-site/support.html](https://parth4.github.io/hum-site/support.html)

The Expo app reads `expo.extra.humInviteUrl` in the main **hum** project — set to the home URL above so **Share hum** includes this link.

## GitHub Pages

Source: branch **main**, folder **/** (root).

## Brand icon

The hummingbird mark matches the mobile app (`assets/hummingbird-mark.svg`). Update it from the **hum** app repo when the icon changes:

- Run `D:\hum\scripts\sync-hum-site-icon.ps1`, or copy `hum/assets/hummingbird-mark.svg` into `assets/` here.
- License: `assets/ATTRIBUTION.txt` (CC BY 3.0, game-icons).

## Clone & edit

```bash
git clone https://github.com/parth4/hum-site.git
cd hum-site
# edit HTML/CSS, then:
git add -A && git commit -m "Update site" && git push
```
