# Women in Law Society — Georgetown

A single-file static website (`index.html`). No build step, no dependencies to install — just HTML/CSS/JS.

## Put it on GitHub Pages (free)

1. Create a new GitHub repo (e.g. `wils-georgetown`), public.
2. Upload `index.html` to the repo root (GitHub web UI: **Add file → Upload files**).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)` → **Save**.
6. Wait ~1 minute, then your site is live at:
   `https://<your-username>.github.io/<repo-name>/`

## Editing content

Everything is in `index.html`:
- Board member names/roles — the `<section id="board">` block.
- Events — the `<section id="events">` block (each `.docket-row`).
- Mission text — the `<section id="about">` block.
- Contact email — the `<footer>` at the bottom.

The join form currently just shows a thank-you message in the browser (no backend). To actually collect submissions, swap the `<form>` action for a free form service like Formspree or Google Forms, or connect it to a Google Sheet.
