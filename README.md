# Berkay Kullukçu Portfolio Website

This is a static, ready-to-deploy website customized from the supplied template.

## Local preview

Run a local web server from this folder (opening `index.html` directly may block JSON loading):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment

1. Replace the files in your `bkullukcu.github.io` repository with the contents of this folder.
2. Commit and push to the default branch.
3. In GitHub repository settings, enable Pages from the repository root if it is not already enabled.

## Main editable files

- `config.json`: home, about, projects, timeline, footer, and contact content.
- `resume.json`: structured resume page content.
- `Berkay_Kullukcu_CV.pdf`: downloadable CV.
- `projects/` and `timeline/`: portfolio images.

The displayed web pages use only city-level location and omit the phone number and postal code. The downloadable CV is the original supplied PDF and therefore retains its full contact details.
