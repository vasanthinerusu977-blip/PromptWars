# 🧭 Launchpad: Find your route

A student career-planning website that runs entirely in the browser. No backend, no sign-up, no build step.

**Live demo:** https://fastidious-griffin-fdad38.netlify.app

## What it does

1. **Roadmaps:** 113 career roadmaps. Pick a destination and see what to learn, in order, through five waypoints from Basecamp to Summit.
2. **Prep Guide:** 8 guides on what hackathons and case competitions expect and how to prepare.
3. **My Opportunities:** paste in a hackathon, internship or scholarship and get matched prep guidance. Entries are saved in your browser.

> Data is a starting point, not gospel. Always cross-check deadlines on the official source.

## Project structure

```
launchpad/
├── index.html      # the whole site (HTML, CSS and JS)
├── netlify.toml    # Netlify deploy settings
├── .gitignore
└── README.md
```

## Run locally

No install needed. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

**Netlify:** connect this GitHub repo in Netlify. No build command is needed and the publish directory is the repo root (already set in `netlify.toml`).

**GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.

## Roadmap ideas

- Save and share a roadmap as a link
- Deadline reminders for saved opportunities
- Add more prep guides and roadmaps

## License

MIT (add a `LICENSE` file if you want it public).
