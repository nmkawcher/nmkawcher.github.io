# NM Kawcher · Portfolio

Static site: `index.html`, `photo.jpg`, `NM-Kawcher-CV.pdf`, `og-image.png`, `robots.txt`, `sitemap.xml`. No build step.

## Preview locally
Double-click `index.html`.

## Publish free on GitHub Pages (nmkawcher.github.io)
1. Create a public repo on GitHub named exactly `nmkawcher.github.io`.
2. Upload all files in this folder (except README.md, optional) to the repo root.
3. Repo → Settings → Pages → Source: "Deploy from a branch", Branch: `main` / root → Save.
4. After about a minute the site is live at https://nmkawcher.github.io

Alternative: drag this folder onto https://app.netlify.com/drop.

## Updating content
- Projects: search for `<article class="proj"` in index.html. Copy a block to add an app.
- Experience: each `<li class="log-item">` is one role.
- New CV: replace `NM-Kawcher-CV.pdf` (keep the same filename).
- New photo: replace `photo.jpg` (portrait, about 465×520 px or larger).

## Get found on Google and AI search (do once, after the site is live)
1. **Google Search Console** (search.google.com/search-console): add `https://nmkawcher.github.io/`, verify, then submit `sitemap.xml`.
2. **Bing Webmaster Tools** (bing.com/webmasters): import from Google Search Console in one click and submit the sitemap. ChatGPT search relies on Bing's index, so this step matters for AI answers.
3. Put the site link everywhere: LinkedIn (Contact info + Featured), GitHub profile "Website" field and README, Medium bio, YouTube "About", Udemy instructor bio. These links tell Google and AI tools the site is the real you.
4. Use the same name and title everywhere: "NM Kawcher · Senior Mobile Engineer".
5. Check the social preview at https://www.opengraph.xyz after deploy.

**Using a custom domain later?** Replace `https://nmkawcher.github.io/` in index.html (canonical, og:url, og:image, JSON-LD), robots.txt and sitemap.xml.
