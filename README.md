# Felix Li — Engineering Portfolio

A responsive static HTML/CSS portfolio for engineering and research projects. The site has no build step or framework.

## Preview locally

Open `index.html` in a browser, or serve this folder with the VS Code Live Server extension.

## Site structure

- `index.html` — homepage, featured CERN CMS work, selected projects, about, and contact
- `projects/` — individual engineering and research case studies
- `assets/` — approved project imagery, figures, and the linked CV
- `styles.css` and `projects/project.css` — site styles

## GitHub Pages

Publish the repository's `main` branch from the root folder (`/`) in the repository's **Settings → Pages**. Keep `index.html` at the repository root so Pages can serve it as the landing page.

The `.gitignore` excludes the unpublished surrogate-modeling source report, unused internal assets, and unfinished draft project pages. These local files are not needed to render the website.
