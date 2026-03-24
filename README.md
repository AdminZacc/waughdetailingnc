# Waugh Detailing Website

Simple static site ready for GitHub Pages.

## Run locally

Open index.html in your browser, or run a quick local server from this folder:

- Python: python -m http.server 8000
- Node: npx serve .

Then visit http://localhost:8000

## Publish on GitHub Pages

1. Create a new GitHub repository (for example: waugh-detailing-site).
2. In this folder, run:
   - git init
   - git add .
   - git commit -m "Initial website"
   - git branch -M main
   - git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   - git push -u origin main
3. In GitHub, open Settings > Pages.
4. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
5. Save and wait about 1-2 minutes.
6. Your site will be live at:
   - https://YOUR_USERNAME.github.io/YOUR_REPO/

## Customize

- Edit index.html for text/content.
- Edit styles.css for colors, spacing, and layout.
