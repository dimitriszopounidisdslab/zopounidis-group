# Zopounidis Group

Static website for Zopounidis Group, the collective name for the ventures founded by Dimitris Zopounidis:

- Zopounidis Analytics & Advisory
- Crete Aviation Observatory
- Aviationlife.gr

## Publish on GitHub Pages

1. Create a public repository named `zopounidis-group` under the `dimitriszopounidisdslab` account.
2. Upload the contents of this folder (keep `index.html` at the root, together with `assets/` and `.nojekyll`).
3. In the repository: Settings > Pages > Build and deployment > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
4. The site will be served at `https://dimitriszopounidisdslab.github.io/zopounidis-group/`.

If you choose a different repository name, update the `og:url` and `og:image` addresses in the `<head>` of `index.html`.

## Structure

```
index.html                 the page
assets/brand/              Zopounidis Group wordmarks and monogram (SVG, outlined)
assets/img/                venture logos, favicon, social preview image
.nojekyll                  serve files as they are
```

Fonts (IBM Plex Serif, Sans, Mono) load from Google Fonts.
