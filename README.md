# Liebherr CRS Dimensioning Tool

This repository contains the standalone Liebherr CRS Dimensioning Tool from
the offline bundle. It is separate from the SpecMatrix compliance-matrix
application.

The app and its bundled fonts and report libraries are published with GitHub
Pages at <https://shubham191000.github.io/liebherr-crs-dimensioning-tool/>.
GitHub Actions deploys the repository root on every push to `main`.

To run it locally, serve this directory over HTTP (the app uses `fetch` for
font embedding in PDF exports):

```bash
python -m http.server 8000
```

Open <http://localhost:8000>.
