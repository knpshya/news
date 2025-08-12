# Cloudflare Pages Starter

This is a ready-to-deploy static starter that works out of the box on Cloudflare Pages.

## Quick start

### Option A: Direct upload
1. Download the ZIP from your assistant.
2. In Cloudflare Dashboard go to **Pages** → **Create a project** → **Direct Upload**.
3. Drag and drop the ZIP. Done.

### Option B: Git integration
1. Create a new GitHub repo and push these files.
2. In Cloudflare Dashboard go to **Pages** → **Create a project** → **Connect to Git**.
3. Select the repo and branch. No build command is required.
4. Deploy. Your site will be available at `https://<project>.pages.dev`.

## Customization
- Edit `index.html`, `about.html`, and `styles.css`.
- Update `robots.txt`, `sitemap.xml`, and meta tags for your real domain.
- Add more pages in the project root.
- If you add a build step later, set build command and output directory in Pages settings.
