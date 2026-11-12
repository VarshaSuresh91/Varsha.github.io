# Academic website — Varsha Peringothara Suresh

A responsive, three-page academic portfolio in plain HTML and CSS. No installation, build tools, JavaScript, tracking, or external fonts required.

## Files
- `index.html`: biography, industry experience, fellowship, Scholar profile.
- `research.html`: research foundations, ongoing directions, publication overview, future interests.
- `teaching.html`: philosophy, teaching areas, classroom methods, example activity.
- `assets/style.css`: shared appearance and responsive layouts.
- `.nojekyll`: serve the site as static files on GitHub Pages.

## Preview
Open `index.html` directly in your browser. Alternatively, run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Personalise before publishing
1. Check the displayed full name, biography, fellowship and employment dates.
2. Confirm the HCL employment type before adding Full-time or Part-time. Confirm that “equivalence analysis” accurately describes the method used; if output comparison on test inputs was used, prefer “comparative testing”.
3. Add your email, GitHub and ORCID links in the Connect section of index.html. None are guessed.
4. To offer a CV, put the reviewed PDF at assets/cv.pdf and uncomment the example CV link in index.html.
5. For a portrait, add your own photo to assets and insert an img with meaningful alt text; no stock portrait is used.
6. Add exact publication citations to research.html. The current overview is based on supplied background; no paper titles, author lists or DOIs were invented.
7. On teaching.html, distinguish courses actually taught from interests. Add institution, course code, semester and role from your records.
8. Update the navigation/footer in all three HTML files if changing shared text. Edit colours under :root in assets/style.css.

## Publish on GitHub Pages
1. Create a repository named YOUR_USERNAME.github.io, substituting your actual GitHub username.
2. Upload the CONTENTS of this folder to the repository root, so index.html is at the top level, beside research.html and teaching.html. Do not upload the ZIP as your website.
3. In repository Settings > Pages, select Deploy from a branch, choose main and /(root), then Save.
4. After deployment completes, visit https://YOUR_USERNAME.github.io/.
5. For a project repository, the URL will instead be https://YOUR_USERNAME.github.io/REPOSITORY/. All internal links are relative and support both layouts.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

This is website source for GitHub Pages, not a GitHub profile README. No site has been published and no repository has been modified.

## Accessibility and validation
Semantic page structure, skip navigation, visible keyboard focus, current-page navigation labels, and mobile layouts are included. Core content works without JavaScript. Local HTML references and heading structure were checked programmatically; perform a final desktop/mobile browser review before publishing.
