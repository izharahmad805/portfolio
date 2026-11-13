# Izhar Ahmad · Portfolio

Personal portfolio of **Izhar Ahmad**, embedded engineer from Peshawar, Pakistan.

It covers my final-year CubeSat with an on-board solar-cell curve tracer (3rd of 50+ projects), the student teams I worked on at GIKI (RoboCup SSL, Team Hammerhead, Team Invictus), my bench work, and my firmware work at Xcelerium.

## Structure

```
index.html        the whole site (HTML, CSS and a small script in one file)
assets/img/       photos, resized for the web
assets/vid/       short compressed clips with poster frames
.nojekyll         tells GitHub Pages to serve files as they are
```

No build step and no dependencies. Fonts load from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Live site

https://izharahmad805.github.io/portfolio/

## Publish on GitHub Pages

This repository is a project site, separate from `izharahmad805.github.io`.

1. Push these files to the `main` branch of `izharahmad805/portfolio`.
2. In the repository, open **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.

The site is live a minute or two later at the address above.
