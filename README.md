# Ayushi Shiv — Portfolio Site

Single self-contained `index.html` (all CSS/JS inline, no build step, no dependencies). Same deployment model as the reference site you shared.

## Deploy to GitHub Pages (root domain)

1. Create a new GitHub repo named exactly `<your-username>.github.io` (e.g. `ayushi-shiv.github.io`). This naming convention makes it your root portfolio URL automatically.
2. Add `index.html` (and `resume.pdf` if you have one to link) to the repo root, then commit and push to `main`.
3. Go to the repo's **Settings → Pages** and confirm the source is set to deploy from the `main` branch, root folder. (For a repo named `<username>.github.io`, GitHub usually enables this automatically.)
4. Wait 1–2 minutes — your site goes live at `https://<username>.github.io`.

## Before you publish

- [ ] Double-check every metric against your latest resume
- [ ] Replace the `resume.pdf` link in the Hero and Contact sections with a real file, or point it at your LinkedIn instead
- [ ] Consider whether you want a headshot — the design works without one, but I can add a slot if you want it
- [ ] Add the live link to your LinkedIn "Featured"/"Contact info" section and your resume header

## Editing later

Everything is in one file (`index.html`) — search for the section you want to change (`id="work"`, `id="experience"`, etc.) and edit the HTML directly. No build tools required.
