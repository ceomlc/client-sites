# Client Sites

This repository is a collection of static website concepts and client previews created by More Life Consulting for local service businesses. It was built to keep self-contained HTML prototypes in one place so they can be reviewed, demonstrated, and deployed independently.

## Included sites

- `honest-hvac/` — a multi-section site for Honest HVAC Plumbing & Home Diagnostic in Baltimore
- `md-plumbing/` — a plumbing and heating site for MD Plumbing & Heating LLC
- `peterson-exteriors/` — a roofing, waterproofing, siding, and exterior-services site for Peterson Exteriors LLC
- `index.html` — a landing page for browsing the available client previews

Each site includes its own HTML and image assets. Styling and interaction logic are embedded in the pages, so there is no build step or package installation.

## Run locally

You can open `index.html` directly in a browser, or serve the repository with any static HTTP server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Structure

```text
client-sites/
├── index.html
├── honest-hvac/
├── md-plumbing/
└── peterson-exteriors/
```

To add another preview, create a new directory containing an `index.html` file and its local assets, then add a link from the root index.
