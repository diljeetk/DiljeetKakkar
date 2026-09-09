# Diljeet Kakkar — Portfolio

Single-file portfolio website (`index.html`). No build step, no dependencies — works on any static host.

## Deploy to GitHub Pages (free, ~5 minutes)

1. **Create a repository** on [github.com](https://github.com/new):
   - For the cleanest URL, name it exactly `YOURUSERNAME.github.io` → site will live at `https://YOURUSERNAME.github.io/`
   - Any other name (e.g. `portfolio`) also works → site lives at `https://YOURUSERNAME.github.io/portfolio/`

2. **Push this folder** (from a terminal, inside the myPortfolio folder):

   ```bash
   git init
   git add index.html .nojekyll README.md
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOURUSERNAME/YOURREPO.git
   git push -u origin main
   ```

3. **Enable Pages**: repo → Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.

4. Wait a minute, then open your URL. Done.

## After deploying (SEO)

Open `index.html`, find the commented lines near the top, uncomment them, and set your live URL:

```html
<link rel="canonical" href="https://YOURUSERNAME.github.io/">
<meta property="og:url" content="https://YOURUSERNAME.github.io/">
```

Commit and push again.

## Boost your online presence

- Add the URL to your LinkedIn profile (Contact info → Website, and as a Featured link)
- Add it to your resume header and email signature
- Optional: buy a custom domain (e.g. diljeetkakkar.dev) and set it in repo → Settings → Pages → Custom domain

## Notes

- `.nojekyll` tells GitHub Pages to serve files as-is (skips Jekyll processing)
- Dark/light mode preference is saved in each visitor's browser
- To update the site, edit `index.html` and push again
