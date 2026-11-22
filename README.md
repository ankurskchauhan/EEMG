# EEMG @ IISc: group website

Static website for the Extreme Environments Materials Group (EEMG), Department of Materials Engineering, IISc Bengaluru.
Plain HTML and CSS, no build step. Served with GitHub Pages.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for a personal site, name it `<username>.github.io`).
2. Upload everything in this folder to the repository root (`index.html` must be at the top level).
3. Go to **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. The site is live at `https://<username>.github.io/` (or `https://<username>.github.io/<repo>/` for other repository names) within a minute or two.

## Custom domain (optional)
Add your domain under **Settings > Pages > Custom domain** and create the DNS records GitHub shows you.

## Editing
- `news.html`: add new items at the top of the current year's `<div class="timeline">`.
- `research.html`: add `<li>` entries inside the matching `<ol class="pubs">`.
- `people.html`: edit the cards or lists.
- `assets/style.css`: colours are CSS variables at the top (`--accent`, `--hero1`, `--hero2`).
