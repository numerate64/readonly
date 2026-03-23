# Is It Read-Only Friday? (static)

This is a tiny static site that checks if it's "read-only Friday" based on the visitor's local calendar. The page displays whether it's Friday or not, with appropriate messaging for production deployments.

## What It Does

- **Checks the Day**: Determines if the current day is Friday using JavaScript's `Date.getDay()` method.
- **Displays Status**: Shows "Yep. Hands off prod." if it's Friday, or "Nope. Change away!" if it's not.
- **Shows Local Time**: Displays the current local time and timezone offset for reference.
- **Responsive Design**: Styled with CSS for a clean, card-based layout.

## Hosting on GitHub Pages

- Push this repository to GitHub (any branch with the site at the repository root will work).
- In the repository on GitHub, go to Settings → Pages and set the source to the branch you pushed (e.g., `main`) and the root folder `/`.
- After a minute, your site will be available at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- I added `styles.css`, `favicon.svg`, and an empty `.nojekyll` to ensure static assets are served.
- If you want automatic deployments or a separate `gh-pages` branch, I can add a GitHub Actions workflow to build and push to `gh-pages`.
