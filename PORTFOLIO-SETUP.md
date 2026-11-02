# Sebastian Long — game development portfolio

The active site starts in `src/Portfolio.jsx`, with styles in `src/portfolio.css`. Project descriptions are based on the public repositories. The illustrated panels are concept visuals, not gameplay screenshots. Replace them with your own captures when available. Add an email or LinkedIn only when you are ready to publish those details.

## Preview

Install Node.js 24 and run `npm ci`, then `npm run dev`.
Run `npm run build` to verify the production output.

## GitHub Pages

This checkout is for https://github.com/Seblong2/SebastianLongGameDeveloper.
The Vite base path is already `/SebastianLongGameDeveloper/`.
The existing `.github/workflows/pages.yml` builds and deploys changes pushed to `main`.
In the repository, select **Settings → Pages → Source → GitHub Actions**.
Review and commit the site changes, then push to `main`.
After the Pages deployment succeeds, the expected address is:
https://seblong2.github.io/SebastianLongGameDeveloper/

The site uses section anchors so refreshing or directly linking to a section does not require server routing.
Older template components remain in the checkout but are no longer loaded by the active entry point.

GitHub reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
