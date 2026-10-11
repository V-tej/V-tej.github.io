# Portfolio

Static personal portfolio site — plain HTML/CSS/JS, no build step.

## Deploy on GitHub Pages

1. Create a new GitHub repo. For a site at `v-tej.github.io` (your root domain), name the repo
   exactly `V-tej.github.io`. For a project page instead (e.g. `v-tej.github.io/portfolio`), any
   repo name works.
2. Push this folder's contents to that repo:
   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/V-tej/<repo-name>.git
   git push -u origin main
   ```
3. In the repo on GitHub: **Settings → Pages → Source → Deploy from branch → main → / (root)**.
4. Your site goes live at `https://v-tej.github.io/` (or `/<repo-name>/` for a project page) within
   a minute or two.

## Before pushing

- Add your resume PDF to this folder (e.g. `resume.pdf`) and link it from the "View Projects" /
  hero section if you want a direct download button.
- Double-check the live project links still work (Render free-tier services can spin down when
  idle and take ~30s to wake on first click — normal, not a bug).
