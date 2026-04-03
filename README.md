# IGYM Website

Static multi-page website for GitHub Pages.

## Pages

- Home
- About Us
- IGYM - Prayoga: 2025
- IGYM - Himalayan Outreach
- IGYM - Prayoga: 2026
- Contact Us

## Deploy on GitHub Pages

1. Initialize git if needed:
   `git init`
2. Add the GitHub remote:
   `git remote add origin https://github.com/manansethia/Igym-Igeo.git`
3. Commit and push:
   `git add .`
   `git commit -m "Initial IGYM website"`
   `git branch -M main`
   `git push -u origin main`
4. In GitHub:
   Go to `Settings` → `Pages` → `Build and deployment`
5. Set:
   Source: `Deploy from a branch`
   Branch: `main`
   Folder: `/ (root)`

Your site will then publish at:
`https://manansethia.github.io/Igym-Igeo/`

## Notes

- Replace placeholder text in the content pages with your final copy.
- Update contact information in `contact.html`.
