# Garaj website

A standalone static landing page based on the supplied Garaj design. The mobile app remains in the separate `garaj` repository.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Before launch

- Add the published App Store URL and enable the download buttons.
- Add reviewed Privacy, Terms, and Support pages before linking them in the footer.
- Point `garaj-app.com` to GitHub Pages in GoDaddy DNS:
  - Replace the current `@` A records with four A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
  - Set `www` as a CNAME to `meryemdag91.github.io`.
  - Keep any unrelated DNS records, including email records.
- After DNS resolves, enable **Enforce HTTPS** in GitHub Pages settings and verify domain ownership in the GitHub account's Pages settings.

The layout, copy, logo, and fonts came from the supplied landing page export. The page requires no build step or package install.
