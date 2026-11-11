# Personal research website — GitHub Pages starter

A responsive research portfolio and technical writing site, built with plain HTML, CSS, and JavaScript. No build step, no paid hosting required.

## Publish to GitHub Pages

1. Create a public GitHub repository named `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your actual GitHub username).
2. Upload the **contents** of this folder to the repository root (not the containing folder).
3. Commit the files to the `main` branch.
4. Open repository **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. After deployment, visit `https://YOUR_USERNAME.github.io/`. It can take a few minutes to become available.

For a different repository name, the site may be served under `/repository-name/`; relative links should work.

## Personalize before launch

- Replace the placeholder email `YOUR_EMAIL@example.com` and GitHub username in `index.html`.
- Check the biographical text and change anything you don't want public.
- The articles are **examples/drafts**; don't represent them as published original writing.
- Change the site title, colors, and section copy as desired.
- Replace the placeholder planned-topic pages with original articles.
- For a custom domain, configure it under GitHub Pages settings and add the DNS records required by GitHub.

## Add an article

1. Copy `posts/calibration.html` to `posts/my-article.html`.
2. Update title, metadata, headings, and article body. MathJax supports `\\(...\\)` and `\\[...\\]`.
3. Add an entry in the `articles` array near the top of `assets/app.js`, with title, tag, desc, symbol, url, and status.
4. Commit and push. The homepage list, search, and filters update automatically.

## Included features

- Responsive homepage and article pages
- Dark/light mode (saved in browser)
- Animated canvas visualization
- Interactive softmax temperature experiment
- Blog search and category filters
- MathJax support for equations
- GitHub Pages compatible static hosting

## Technical notes

- Fonts are fetched from Google Fonts and MathJax from jsDelivr, so they require internet access.
- The animated calibration curve is **illustrative**, not empirical data. Replace it with real measurements before making scientific claims.
- No analytics, cookies, contact form backend, CMS, or search engine indexing setup is included.
- For dozens of articles, consider migrating to Quarto or Astro with Markdown-based content collections; this starter prioritizes zero-build simplicity.
