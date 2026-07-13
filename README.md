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
- `resume.json`: structured resume page content, including all journal articles, conference papers, and the master's thesis.
- `Berkay_Kullukcu_CV.pdf`: downloadable CV.
- `projects/` and `timeline/`: portfolio images.

The displayed web pages use only city-level location and omit the phone number and postal code. The downloadable CV is the original supplied PDF and therefore retains its full contact details.


## Publications and links

The Publications section contains all 13 journal articles, conference papers, and the master's thesis listed in the supplied CV. Publication titles and their action chips are clickable. Exact publication URLs embedded in the CV were transferred to `resume.json` and reused on the About and Projects pages. The ICSV32 2026 paper is listed without a link because the supplied CV does not contain a hyperlink for that entry.


## Bilingual website

English is the default language. Visitors can switch between English and German using the EN/DE button in the navigation bar. The choice is stored locally in the browser. German content is stored in `config-de.json` and `resume-de.json`; publication URLs remain identical in both language versions.
