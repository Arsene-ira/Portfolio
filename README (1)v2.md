# Iradukunda Arsene — Portfolio

Single-file, dependency-free portfolio. Warm brown-beige palette, dark mode, mobile-responsive.

## Files (keep both together, same folder)
- `index.html` — the site
- `Iradukunda-Arsene-CV.pdf` — the CV. The Download CV buttons link to this by relative path, so it just works.

## Deploy

**GitHub Pages**
1. Create a repo, upload both files to the root.
2. Settings → Pages → Source: "Deploy from a branch" → main / (root) → Save.
3. Live at `https://<username>.github.io/<repo>/` in a minute or two.

**Vercel**
1. Import the repo (or drag the folder into vercel.com/new).
2. Framework preset: "Other". No build command, output directory = root. Deploy.

Both work with zero config — it's plain static HTML.

## The two working buttons
- **Download CV** (hero + nav) → opens/downloads the PDF. Works out of the box.
- **Nav links** (About, Education, Skills, Projects, Experience, Contact) → smooth-scroll to each section on the page.

## Contact form
Posts to FormSubmit. On the first real submission, FormSubmit emails Arsene a one-time
activation link — click it once and the form works forever. No account, no key.
(The email and phone links work immediately regardless.)

## To swap in a different CV
Replace `Iradukunda-Arsene-CV.pdf` with a new file of the exact same name. No code changes needed.

## Customize colors
All colors are CSS variables in the `:root` block at the top of `index.html`
(`--clay`, `--coffee`, `--gold`, `--paper`). Dark mode auto-detects system preference
and remembers the toggle.
