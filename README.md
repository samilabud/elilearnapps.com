# elilearnapps.com

Static site for **EliLearn Apps**, served by GitHub Pages at <https://elilearnapps.com>.

Replaces the WordPress site that was lost when the Hostinger hosting plan lapsed
(last live capture: 2026-06-08). Content and images were recovered from the
Internet Archive and rebuilt as plain static HTML — nothing to renew, patch, or
let expire.

## Layout

```
index.html               homepage
privacy-policy/          /privacy-policy/ — the URL referenced by the Google Play listing
es/privacy-policy/       /es/privacy-policy/ — Spanish translation, used by the App Store Spanish (Mexico) locale
404.html                 not-found page
assets/styles.css        all styling (brand palette sampled from the original logo)
assets/                  original images recovered from the archive
CNAME                    custom domain for GitHub Pages
```

## Editing

Plain HTML and CSS — edit the files and push to `main`. GitHub Pages redeploys
automatically. Preview locally with:

```sh
python3 -m http.server 8000
```

## Important

`/privacy-policy/` is the privacy policy URL registered in the Google Play
listing for **Animal Adventures** (`com.elilearnapps.animaladventures`).
Google requires it to resolve. Do not rename or remove that path.
