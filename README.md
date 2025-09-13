Sea Cross Capital — Static Site Template
How to use:
1) Create a GitHub account if you don’t have one.
2) Create a repository named seacrosscapital.github.io (exactly this) OR create any repo and enable GitHub Pages later.
3) Upload these files to the repo root (index.html, about.html, strategy.html, contact.html, styles.css, /assets).
4) In GitHub → Settings → Pages: set Source to deploy from the main branch (/root). If you want a custom domain (seacrosscapital.com), enter it and GitHub will create a CNAME file automatically.
5) Go to GoDaddy DNS for seacrosscapital.com and set:
   A @ 185.199.108.153
   A @ 185.199.109.153
   A @ 185.199.110.153
   A @ 185.199.111.153
   CNAME www seacrosscapital.github.io
6) Wait a few minutes for DNS to propagate. Visit https://seacrosscapital.com and https://www.seacrosscapital.com
7) Edit text inside the HTML files as needed. Change email in contact.html. Replace assets as desired.
Notes:
- This is a static site (no backend). For forms, use a service like Formspree or Netlify Forms.
- For analytics, add your Google Analytics tag to each HTML <head> section.
- For SEO, update meta descriptions/titles per page.
