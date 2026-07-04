# CDR Insights — cdrinsights.com

Static site. Each page is fully self-contained HTML (styles, fonts, logo, favicon inlined).

## Pages
- index.html — Home
- services.html — Services
- about.html — About
- contact.html — Contact
- CNAME — custom domain for GitHub Pages

## Deploy on GitHub Pages
1. Create a repo (e.g. cdrinsights-site), upload all files in this folder to the repo root.
2. Repo Settings → Pages → Source: "Deploy from a branch" → branch: main, folder: / (root).
3. Settings → Pages → Custom domain: cdrinsights.com (the CNAME file is already here).
4. At your domain registrar, point cdrinsights.com:
   - A records → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME record for www → <your-github-username>.github.io
5. Back in Pages settings, enable "Enforce HTTPS" once DNS propagates.
