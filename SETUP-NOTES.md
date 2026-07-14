# GHL Portfolio — Client-Facing Copy

Copy of the GHL funnel portfolio with personal contact details removed.
Plain HTML — no build step. Works on GitHub Pages or any static host.

The email/phone lines in the "Ready to Automate Your Growth?" section were
removed entirely. To add your own, put this back inside that section in
`index.html` and `portfolio.html` (after the Start a Project button):

```html
<div class="contact-info">
  <a href="mailto:you@example.com">you@example.com</a>
  <a href="tel:+00000000000">+000 0000 0000</a>
</div>
```

## Fill in before sharing (search each file for these placeholders)

Files to edit: `index.html` and `portfolio.html` (same edits in both).

1. `calendly.com/YOUR-CALENDLY-USERNAME/30min` — the "Start a Project" booking
   modal. Replace with your own Calendly link (keep everything after `30min`).
2. `https://YOUR-USERNAME.github.io/Jim/` — the "Advanced Automation" preview
   iframe and its "View Full Site" button. After you deploy the automation
   portfolio copy (the `Jim` repo), put its URL here.

## Deploy on GitHub Pages

1. Create a new repo, upload all files in this folder to the repo root.
2. Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.
3. Live at `https://YOUR-USERNAME.github.io/REPO-NAME/` in a minute or two.
