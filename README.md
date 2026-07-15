# Waad's Digital Card

A single-file, no-build website. Everything (HTML, CSS, JS) lives in `index.html`.

## How to put this on GitHub Pages (free hosting)

1. Go to [github.com](https://github.com) and create a **new repository** (e.g. `digital-card`). Keep it **public**.
2. Upload `index.html` to the repo — the filename `index.html` matters, GitHub Pages looks for it by default.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site will be live at:
   `https://YOUR-USERNAME.github.io/digital-card/`
6. Share that link by email instead of attaching the file — it'll always be up to date with whatever you add through Edit Mode... with one caveat below.

## Important: how "Edit Mode" data works

This page saves anything you add (About text, projects, experience) in **your browser's local storage** — not on GitHub, not on a server. That means:

- Edits you make on your laptop stay on your laptop's browser.
- If you open the GitHub Pages link on your phone, you won't see those edits there — you'd need to re-add them on that device too.
- Recruiters visiting your link will always see the page in its default/last-published state from *their* browser, never your edits (each visitor has their own separate local storage).

**Best workflow:** finish adding all your real content locally (open the file, unlock edit mode with the password, add everything), then when you're happy with it, tell me and I'll bake those entries into the file itself as the new defaults — so everyone who visits sees them, not just you.

## Notifications

Wrong password attempts, edit-mode unlocks, and content changes trigger an email to you via EmailJS. The "Email Us" tab lets visitors message you directly the same way.

## Password

Edit mode is protected by a password set in the code. It is **not real security** — anyone who views the page source can find it — but it stops casual clicks.
