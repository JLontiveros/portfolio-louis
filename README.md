# Jann Louis Ontiveros — Portfolio

Single-page portfolio site positioning Jann Louis as a VA specializing in
GoHighLevel, CRM automation, and lead generation for service businesses.

Plain HTML/CSS/JS — no build step, no dependencies.

## Files

- `index.html` — page structure and copy
- `styles.css` — design system (colors, type, layout, animation)
- `script.js` — scroll-reveal polish

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy to GitHub + Vercel

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then in Vercel: **New Project → Import** the GitHub repo. No framework
preset needed — select **Other** and leave build/output settings blank.
Vercel will serve `index.html` as a static site automatically.

## Customize

- Update the email/phone in the `#contact` section and the hero CTA links.
- Swap the stats in `.hero-stats` as your track record grows.
- Add real project links/screenshots to the `#projects` cards when ready.
