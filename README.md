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

Deploy to Netlify:

1. Drag and drop the `webprofile` folder into Netlify Sites (free plan) or connect your GitHub repo.

Replace `YOUR_FORM_ID` in `index.html` form `action` with your Formspree form id if you want contact form submissions.

Replace the placeholder images in `assets/` and add `cv/JohnKhylle_Dumlao_CV.pdf`.
