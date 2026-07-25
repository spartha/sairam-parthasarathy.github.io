# Sairam Parthasarathy Academic Website

A responsive static academic website designed for GitHub Pages.

## Files

- `index.html` — website content
- `styles.css` — design and responsive layout
- `script.js` — mobile menu and footer year
- `assets/` — add your headshot, CV, and other downloadable files here

## Before publishing

1. Replace `YOUR_EMAIL@arizona.edu` in `index.html`.
2. Replace the placeholder links for PubMed, Google Scholar, ORCID, institutional profile, and center website.
3. Add your CV as:
   `assets/Sairam_Parthasarathy_CV.pdf`
4. To use a headshot, place it in `assets/headshot.jpg` and replace the `portrait-placeholder` block in `index.html` with:

```html
<img class="profile-photo" src="assets/headshot.jpg" alt="Sairam Parthasarathy, MD">
```

Then add this to `styles.css`:

```css
.profile-photo {
  width: 100%;
  aspect-ratio: 4 / 4.3;
  object-fit: cover;
}
```

## Publish with GitHub Pages

1. Sign in to GitHub.
2. Create a new public repository named `sairam-parthasarathy.github.io`.
3. Upload all files in this folder to the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
6. Save.

Your website should then be available at:

`https://sairam-parthasarathy.github.io`

## Custom domain

A custom domain can be connected later under **Settings → Pages → Custom domain**.
