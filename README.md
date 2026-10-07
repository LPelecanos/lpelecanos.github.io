# Loizos Pelecanos academic website

A lightweight static academic site designed for GitHub Pages. No build system is required.

## Recommended deployment

1. Create a GitHub account if needed.
2. Create a repository named `<your-github-username>.github.io`.
3. Upload the contents of this folder to the repository root.
4. In GitHub: **Settings → Pages**, publish from the main branch/root if it is not enabled automatically.
5. The site will appear at `https://<your-github-username>.github.io/`.

## Custom domain

A personal domain such as `loizospelecanos.com` or `loizospelecanos.org` can later point to GitHub Pages. Check availability before purchase. In GitHub Pages settings, add the chosen custom domain and verify it in your GitHub account.

## Before publishing

- Replace the circular `LP` placeholder in `index.html` with a preferred professional headshot if desired.
- Check the current role/affiliation wording.
- Add a PDF CV and a `CV` navigation link if desired.
- Curate 6–10 flagship publications rather than trying to reproduce the full Scholar list.
- Add major funded projects, PhD students/alumni and keynote/lecture material if desired.
- Add a custom-domain URL to the OpenGraph and structured-data metadata once the domain is known.

## Easy photo replacement

Replace:

```html
<div class="portrait-placeholder" aria-label="Profile photograph placeholder">LP</div>
```

with:

```html
<img class="profile-photo" src="assets/loizos-pelecanos.jpg" alt="Dr Loizos Pelecanos" />
```

and add this rule to `assets/styles.css`:

```css
.profile-photo { width: 140px; height: 140px; object-fit: cover; border-radius: 50%; margin-bottom: 26px; }
```

## SEO

The homepage already includes:
- descriptive page title and metadata;
- `Person` schema.org structured data;
- links to Bath, ORCID, Scholar, ResearchGate, LinkedIn, YouTube and Academia.edu;
- research keywords including University of Bath / Loizos Pelecanos.

