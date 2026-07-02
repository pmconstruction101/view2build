# View2Build — deploy on GitHub Pages (free)

1. Create a free account at github.com.
2. New repository → name it (e.g. view2build-site) → Public → Create.
3. "Add file → Upload files" → drag EVERYTHING inside this folder
   (index.html, all the .html files, the css / images / fonts folders,
   favicon.svg, robots.txt, sitemap.xml and the CNAME file) → Commit.
4. Settings → Pages → Source: "Deploy from a branch" → Branch: main → /(root) → Save.
   Your custom domain (view2build.co.uk) is pre-set by the CNAME file.
5. Tick "Enforce HTTPS" once it becomes available (a few minutes).
6. At GoDaddy → Domains → view2build.co.uk → DNS, point the site at GitHub
   (leave every MX record untouched so email keeps working):
     A   @   185.199.108.153
     A   @   185.199.109.153
     A   @   185.199.110.153
     A   @   185.199.111.153
     CNAME  www   <your-github-username>.github.io
   (Use the exact IPs GitHub shows in Settings → Pages if they differ.)
7. Contact form: the first time the form is submitted, FormSubmit emails
   paul@view2build.co.uk a one-time "Activate" link — click it once and the
   form is live forever after.
