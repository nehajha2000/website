# nehajha.in

Personal portfolio of Neha Jha: an intro video, an About section, live interactive project demos, case studies and a photo gallery.

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | The homepage (single self-contained page) |
| `projects/` | One interactive case study per project, also used by the "Try it live" demos |
| `img/` | Photos used on the homepage and in the gallery |
| `video/` | Intro video and its cover image |
| `CNAME` | Custom domain for GitHub Pages (`nehajha.in`) |

## Deploying

The site is plain static HTML, so it needs no build step.

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root. The `CNAME` file sets the custom domain.
- **Any static host** (GoDaddy cPanel, Netlify, Vercel): upload or connect the repository root.

Role-specific links quietly reorder the projects: `#product`, `#operations`, `#founders-office`.
