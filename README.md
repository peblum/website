# peblum.org

The landing page for [Peblum](https://github.com/peblum/Peblum), a fully open source fork of PebbleOS.

Static HTML and CSS with no build step. Everything lives in `public/`.

## Local preview

```sh
python3 -m http.server -d public 8000
```

## Deploy

Published to Cloudflare Pages:

```sh
wrangler pages deploy public --project-name peblum-site
```
