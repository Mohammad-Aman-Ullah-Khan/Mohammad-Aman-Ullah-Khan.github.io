# Portfolio Site

A static, no-build academic portfolio (plain HTML/CSS — no Node.js or Astro needed).

## Files
- `index.html` — home page
- `publications.html` — full publication list
- `research.html` — research experience, projects, teaching, service, skills
- `style.css` — shared styles
- `assets/resume.pdf` — your CV, linked from every page

## Deploy on GitHub Pages (5 minutes)

1. Create a new repository on GitHub, e.g. `portfolio` (or `yourusername.github.io` if you want it at the root of your GitHub domain).
2. Upload all the files in this folder to the repo, keeping the same structure (including the `assets/` folder).
   - Easiest way: on the repo page, click **Add file → Upload files**, drag in everything, and commit.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. After a minute or two, your site is live at:
   `https://yourusername.github.io/portfolio/`
   (or `https://yourusername.github.io/` if you named the repo `yourusername.github.io`)

## Before you share it

- Replace the placeholder GitHub/LinkedIn URLs in `index.html`, `publications.html`, `research.html`, and the footer with your real profile links if they differ.
- Swap `assets/resume.pdf` for an updated CV whenever it changes — the filename must stay `resume.pdf`, or update the links to match.
- Optional: add a photo. Drop an image into `assets/` (e.g. `assets/photo.jpg`) and add
  `<img src="assets/photo.jpg" class="hero-photo" alt="Portrait">` next to the heading in `index.html`.
