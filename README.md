# Webprofile — John Khylle C. Dumlao

This is a static portfolio site for John Khylle C. Dumlao. It includes an optimized `index.html`, a place for `cv/` and `assets/`.

Quick steps to deploy locally and to GitHub Pages / Netlify.

Local preview (PowerShell):

```powershell
cd "C:\Users\Dumlao\Desktop\WEB PROFILE\webprofile"
# start a simple static server (Python 3)
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Deploy to GitHub Pages:

1. Create a new GitHub repository and push this folder.
2. In repository Settings → Pages, set branch to `main` and folder to `/ (root)`.

Live site
---------

The site is published via GitHub Pages at:

https://ItsKayl05.github.io/webprofile/

Replace placeholder images in `assets/` with your real screenshots (WebP/AVIF recommended) and re-deploy.

Deployment (quick): if you need to re-publish to GitHub Pages from `main` branch, run:

```powershell
# create and push gh-pages from current files
git checkout --orphan gh-pages
git add -A
git commit -m "Publish site to gh-pages"
git push -u origin gh-pages --force
git checkout main
```

Deploy to Netlify:

1. Drag and drop the `webprofile` folder into Netlify Sites (free plan) or connect your GitHub repo.

Replace `YOUR_FORM_ID` in `index.html` form `action` with your Formspree form id if you want contact form submissions.

Replace the placeholder images in `assets/` and add `cv/JohnKhylle_Dumlao_CV.pdf`.
