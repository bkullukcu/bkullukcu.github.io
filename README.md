# Berkay Kullukçu Portfolio Website

Static bilingual portfolio website for GitHub Pages.

## Languages

English is the default language. Visitors can switch between English and German using the EN/DE control. The selected language is stored in the browser.

## Main content files

- `config.json`: English home, about, projects, conference presentations, timeline, footer, and contact content
- `config-de.json`: German translation of the website content, including the conference-presentations page
- `resume.json`: English résumé and publication data
- `resume-de.json`: German résumé and publication data
- `Berkay_Kullukcu_CV_EN.pdf`: English downloadable CV
- `Berkay_Kullukcu_CV_DE.pdf`: German downloadable CV
- `videos/`: conference-presentation recordings and poster images
- `CONFERENCE_VIDEO_GUIDE.md`: instructions for adding future local or YouTube videos

## Local preview

Run this command in the website directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

Place `index.html` and all accompanying files directly in the root of the `bkullukcu.github.io` repository.
