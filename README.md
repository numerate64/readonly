# Is It Read-Only Friday? (static)


This is a tiny static site that determines whether it's a "read-only Friday" using the visitor's local calendar.

Hosting on GitHub Pages

- Push this repository to GitHub (any branch with the site at the repository root will work).
- In the repository on GitHub, go to Settings → Pages and set the source to the branch you pushed (e.g., `main`) and the root folder `/`.
- After a minute, your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Notes

- I added `styles.css`, `favicon.svg`, and an empty `.nojekyll` to ensure static assets are served.
- If you want automatic deployments or a separate `gh-pages` branch, I can add a GitHub Actions workflow to build and push to `gh-pages`.
