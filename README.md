# rygarlabs.com

Source for the RyGar Labs studio site, hosted on GitHub Pages with a custom domain (`rygarlabs.com`).

## Local development

Static HTML. Open `index.html` directly in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

## Deploy

Push to `main`. GitHub Pages rebuilds within ~60 seconds.

## DNS

Apex domain `rygarlabs.com` managed via Cloudflare (DNS-only, no proxy). A records point to GitHub Pages IPs (`185.199.108.153` through `185.199.111.153`).
