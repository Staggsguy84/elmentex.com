# ElmenTex Creations Website

Static site for GitHub Pages — rustic western theme.

## Pages
- `index.html` — Home + services
- `gallery.html` — Project photos (easy to add more)
- `request.html` — Contact / project request form
- `about.html` — About

## Setup for GitHub Pages
1. Create a new GitHub repository (e.g. `elmentex-site` or use an existing one).
2. Upload all these files and folders (keep the structure: css/, js/, images/).
3. In the repo Settings → Pages → Source: Deploy from branch `main` (or `gh-pages`), folder `/ (root)`.
4. Point your custom domain `elmentex.com` to the GitHub Pages site (add the CNAME file if needed, or set it in the Pages settings).

## Form (project requests)
The form on `request.html` is set up for Formspree.
1. Go to https://formspree.io → sign up (free).
2. Create a new form.
3. Replace `YOUR_FORM_ID` in `request.html` with the real form ID from Formspree.
4. Connect it to elmentexcreations@gmail.com so submissions arrive there.

For image uploads right now: customers are instructed to email photos/files to elmentexcreations@gmail.com. Formspree’s free plan does not include file uploads; paid plans do if you want that later.

## Adding gallery photos
1. Put new images in the `images/` folder.
2. Open `gallery.html` and copy one of the `.gallery-item` blocks.
3. Update the `src` and the caption text.
4. Commit and push — the site updates automatically.

## Logo
A simple oak-tree / western logo is included in `images/logo.jpg`. Replace it anytime with a better version.

---
Built for ElmenTex · San Antonio / Elmendorf, Texas
