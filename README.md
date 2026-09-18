# Garaj website

A standalone static landing page based on the supplied Garaj design. The mobile app remains in the separate `garaj` repository.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Before launch

- Replace the App Store `#get` links with the published app URL.
- Add reviewed Privacy, Terms, and Support pages and update the footer links.
- Connect the domain to the chosen static host after the GitHub repository is available.

The layout, copy, logo, and fonts came from the supplied landing page export. The page requires no build step or package install.
