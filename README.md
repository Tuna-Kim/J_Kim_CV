# Jihwan Kim CV website

A responsive, static CV website for GitHub Pages. No build step or package installation is required.

## Upload to GitHub

1. Open the existing CV website repository on GitHub and choose **Add file → Upload files**.
2. Upload the contents of this folder into the repository root, keeping the folder structure. Replace the existing `index.html`, CSS, profile photo, and `CV_J_Kim.pdf`.
3. Commit the uploaded files. Your existing GitHub Pages configuration can continue serving the site.

The repository root must contain `index.html` alongside `css`, `js`, `img`, and `downloads`. No ZIP or build step is required.

## Files

- `index.html`: all site content and links
- `css/style_J_Kim_CV_Page.css`: design, responsive layouts, and print styles
- `js/main.js`: mobile navigation and active section indicator
- `img/Jihwan_Kim_Portrait.jpg`: updated profile photo supplied as IMG_5149.jpg
- `img/favicon.svg`: browser icon
- `CV_J_Kim.pdf`: academic CV, exported from the Word version in `downloads/`
- `downloads/`: consulting PDF and both editable Word CVs

The site uses local assets and system fonts and does not require Bootstrap, a CDN, analytics, or a backend.

## Update content

Edit the text in `index.html`. Replace CV download files at the same paths to update downloads. Update the two Word CVs and regenerate their matching PDF downloads together. Experience dates were confirmed by Jihwan: NPFC consultancy March 2024–March 2026; TUMSAT fellowship September 2023–April 2025; concurrent NPFC fellowship September 2023–February 2024. RFMO LL and ENSO/IOD are internal pilots, started in April and July 2026 respectively.

## Local preview

From the website directory, run `python3 -m http.server 8765`, then open `http://localhost:8765`.
