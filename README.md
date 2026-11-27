# CCS-D³ Bridge 2027 × QiLS

Predictive Molecular Science Forum — March 4–6, 2027 · CCS, University of Tsukuba

## Publish on GitHub Pages
1. Create a repository and upload **everything in this folder** (keep the `assets/` folder structure).
2. Repository → Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. The site appears at `https://<username>.github.io/<repo>/` after a minute.

## Edit common things
Open `index.html` and search for:
- Form links: `forms.gle`
- Open / closed submissions: `registerOpen`, `abstractOpen`, `posterOpen` (in the `data-props` JSON near the bottom — change `"default": true/false`)
- Deadlines: `regCards: [`
- Program: `days: [`

Requires internet access for fonts (Google Fonts) and React (unpkg CDN).
