# lukemvu.github.io

Minimal personal website for GitHub Pages.

## Local preview
Open any HTML file in a browser, or run a tiny static server:

```bash
python3 -m http.server 8000
```

Then browse to <http://localhost:8000>.

## Custom domain (`lukevu.dev`)
This repository includes a `CNAME` file for `lukevu.dev`.

Configure Squarespace DNS with the standard GitHub Pages records:

- `A` @ `185.199.108.153`
- `A` @ `185.199.109.153`
- `A` @ `185.199.110.153`
- `A` @ `185.199.111.153`
- `CNAME` `www` -> `lukemvu.github.io`

In GitHub repository settings:

1. Go to **Settings → Pages**.
2. Set **Custom domain** to `lukevu.dev`.
3. Ensure **Enforce HTTPS** is enabled once certificate provisioning completes.
