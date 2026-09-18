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
- Point `garaj-app.com` to the hosting service in GoDaddy DNS.

The layout, copy, logo, and fonts came from the supplied landing page export. The page requires no build step or package install.
