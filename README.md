# Shahzaib – Portfolio

Static portfolio site (single `index.html`, no build step).

## Deploy on GitHub Pages

1. Create a repo named `<your-username>.github.io` (or any name).
2. Upload everything in this folder, or run:
   ```
   git init && git add . && git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
3. In the repo go to **Settings → Pages → Source** and choose **GitHub Actions**.
4. Push to `main`. The workflow publishes the site at `https://<your-username>.github.io/` (or `/<repo>/`).

## Edit
Change text, links and projects directly in `index.html`.
