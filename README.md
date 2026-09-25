# Pratistha Bairwa — Portfolio

Static website. No build step, no dependencies.

## Files
- index.html — homepage
- jira-plugin.html — Jira Plugin case study
- arenahub.html — ArenaHub case study
- designer-friend.html — Designer Friend case study
- support.js — page runtime (required by every page)
- image-slot.js — image component (required by every page)
- Pratistha_Bairwa_Resume.pdf — resume shown by the Resume button

All images are embedded inside the HTML files. Keep every file in the same top-level folder; the pages link to each other with relative paths (./arenahub.html etc.).

## Publish with GitHub Pages
1. Create a new public repository on GitHub (e.g. `portfolio`).
2. Upload every file in this folder to the root of the repository (Add file → Upload files → drag them all in → Commit).
3. Go to Settings → Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main`, folder `/ (root)`. Save.
5. After 1–2 minutes the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Custom domain (optional)
1. In Settings → Pages → Custom domain, enter your domain (e.g. `pratisthabairwa.com`) and save. GitHub adds a CNAME file to the repo.
2. At your domain registrar, add DNS records:
   - Apex domain (pratisthabairwa.com): four A records pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - www subdomain: a CNAME record pointing to `<your-username>.github.io`
3. Wait for DNS to propagate (minutes to a few hours), then tick "Enforce HTTPS" in Settings → Pages.

## Editing later
Edit the HTML file, commit the change on GitHub, and the site updates automatically within a minute or two.
