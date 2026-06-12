# Cody Stoerck Portfolio Website

This repository contains the static GitHub Pages portfolio website for Cody Stoerck.

## Updated UX Iteration

This version incorporates recruiter-focused UX recommendations:

- Simplified navigation.
- Stronger hero positioning for analytics engineering and data pipeline roles.
- Recruiter summary strip near the top of the homepage.
- Clearer CTA hierarchy.
- Featured Onyx Auto proof strip.
- Case study at-a-glance panel.
- Earlier dashboard/business output placement.
- Reduced screenshot density through expandable evidence galleries.
- Why-this-matters callouts after major technical sections.
- Recruiter takeaway section mapping the project to target roles.

## Website Structure

```text
.
├── index.html              # Portfolio homepage
├── onyx-auto.html          # Featured Onyx Auto case study page
├── styles.css              # Site-wide styling
├── 404.html                # Basic GitHub Pages 404 page
├── .nojekyll               # Prevents GitHub Pages from processing with Jekyll
└── assets/                 # Screenshots, resume PDF, and certification files
```

## Deployment Instructions

1. Upload all files and folders from this package to the root of `CStoerck.github.io`.
2. In GitHub, go to **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and **Folder** to `/ root`.
5. Save and wait for the Pages deployment to complete.

## Pre-Publish Checks

- Confirm all links work.
- Confirm the resume PDF is the intended public version.
- Review Teams alert screenshots for any private details.
- Test the site on desktop and mobile.
