# Hayden Nghiem — Engineering Portfolio Website

A complete static, GitHub Pages-ready engineering portfolio built with HTML, CSS and JavaScript. **No build step, backend, framework, API key or npm install required.**

## Contents
- `index.html` — responsive homepage, navigation, all sections and dialog shell
- `style.css` — responsive layouts, accessible contrast, animations and automatic light/dark styling
- `script.js` — project case studies, category filters, theme preference and mobile navigation
- `assets/` — original project figures extracted from the supplied engineering portfolio PDF and provided headshot
- `The_Minh_Nghiem_CV.pdf` — latest uploaded two-page CV, downloadable from the site
- `engineering-portfolio.pdf` — original seven-page visual engineering portfolio
- `favicon.svg` — website icon
- `.nojekyll` — prevents unnecessary Jekyll processing

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or from the extracted folder run `python -m http.server 8000`.
3. If using the server, visit `http://localhost:8000`.

## Publish to GitHub Pages (separate from the private robotics repository)
1. In GitHub, create a **new public repository** such as `engineering-portfolio` or `ntm08.github.io`.
2. Upload **the contents of this extracted folder** to the repository root, preserving the `assets/` directory.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch** and select `main` and `/ (root)`.
4. GitHub Pages will display the publication address when deployed (commonly `https://ntm08.github.io/engineering-portfolio/`, depending on repository name).
5. Check links, images, theme toggle and the downloadable CV in the live version.

The site uses relative file paths, so it works at project-repository subpaths. **This package does not edit, link to, or publish the private `autonomous-robot-following-docking` repository.** The optional GitHub profile link is public and points only to your profile.

## Colour themes
The CSS follows the visitor's operating-system colour preference by default. The moon/sun toggle overrides the theme, storing the choice under `hayden-theme` in browser local storage. It also works without storage permission (selection lasts for the current page view).

## Edit later
- Site copy and contact links: `index.html`.
- Project case studies and galleries: `script.js`, in the `projects` array.
- Project images: `assets/*.webp`.
- New CV: replace `The_Minh_Nghiem_CV.pdf` with a file of that exact name, or update the download links.

## Evidence and attribution notes
- The five academic project case studies and flagship performance numbers are based on the supplied visual engineering portfolio; industry PCB scope and experience are from the uploaded CV.
- The sixth PCB project has no supplied photographs. Its abstract **illustrative** circuit motif is clearly labelled, not passed off as a real PCB diagram.
- The uploaded ball-and-beam source image is an electronics diagram rather than a clear physical apparatus photo; the site labels it accordingly.
- Team projects avoid claiming sole ownership of integration and results.
- Before making the site public, confirm you have permission to publish any images belonging to teammates, students or institutions, and check that all CV contact details are suitable for public indexing.
- No contact form or analytics are included; email uses the visitor's mail client.

## Browser test checklist
- [ ] Desktop/tablet/mobile navigation works.
- [ ] Project filters show the intended cards.
- [ ] All six case-study dialogs open, scroll and close using button, Esc or backdrop.
- [ ] Light and dark themes follow OS preferences and a chosen override persists after refresh.
- [ ] All original project pictures and the headshot load.
- [ ] CV and portfolio PDF links work.
- [ ] LinkedIn, GitHub and mailto links work.
- [ ] Keyboard focus and reduced-motion preference remain usable.

## Updated elevator PCB case study
Four supplied original photographs and PCB images replace the illustrative circuit graphic. No unverified performance claims have been added.
