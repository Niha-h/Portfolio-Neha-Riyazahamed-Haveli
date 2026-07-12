# Portfolio — Neha Riyazahamed Haveli

A single-page portfolio site featuring three projects:

1. **AI History Timeline** — live demo at [ai-timeline-haveli-neha.netlify.app](https://ai-timeline-haveli-neha.netlify.app/)
2. **AI Lab** — prompt-engineering practice, a Design Thinking exercise, and the "Social Spark" chatbot build
3. **Personal Assessment — Leading Change** — a graduate reflection on AI/ML leadership and change-management self-assessments

It's a single static file (`index.html`, CSS and fonts included, no build step) so it works as-is on GitHub Pages.

## Put it on GitHub

If you don't have a repo yet:

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Turn on GitHub Pages

1. On GitHub, open the repo → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
4. GitHub gives you a live URL within a minute or two, usually:
   `https://<your-username>.github.io/<repo-name>/`

If you want it at the root of your GitHub Pages (`https://<your-username>.github.io/`), name the repo exactly `<your-username>.github.io` instead.

## Customizing

Everything lives in `index.html` — no separate CSS/JS files or dependencies to manage:

- **Header links** near the top of the page (`.header-links`) point to the live demo and the two on-page sections. Add more (LinkedIn, email, resume PDF) the same way.
- Each project is a `.record` block. Copy one to add a fourth project.
- The color tokens are set as CSS variables at the top of the `<style>` block (`--paper`, `--ink`, `--teal`, `--amber`) if you want to adjust the palette.
