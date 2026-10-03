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
- `CV_J_Kim.pdf`: academic CV, exported from the supplied Word document
- `downloads/`: consulting PDF and both original Word CVs

The site uses local assets and system fonts and does not require Bootstrap, a CDN, analytics, or a backend.

## Update content

Edit the text in `index.html`. Replace CV download files at the same paths to update downloads. The two supplied Word CVs are preserved unchanged; their PDF exports preserve their content. Website experience dates follow the consulting CV where the documents differ, including NPFC advisory work in 2024–2026.

## Local preview

From the website directory, run `python3 -m http.server 8765`, then open `http://localhost:8765`.
