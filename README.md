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

## License

Copyright © 2026 Adrian Pascu.

Split by what it is. The markup, CSS and any scripts under `public/` are MIT, in [`LICENSE`](LICENSE),
so anyone can borrow how the page is built. The prose, images and other page content are
[Creative Commons Attribution-ShareAlike 4.0](LICENSE-CONTENT), so a copy of the writing has to
carry attribution and stay under the same terms.

Names, logos and the Peblum wordmark are not covered by either. The projects the page links to keep
their own licences.
