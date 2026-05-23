# Demo Site Launcher

## Hosting
- Hosted on Netlify: https://demo-site-launcher.netlify.app
- Repo: https://github.com/chrismcconachie/grow-demo-site
- Deploys automatically on push to `main`

## Analytics (GA4)
- Measurement ID: `G-3RMNGZJ98F`
- **Every time a new demo site or client site is added, ensure GA click tracking is wired up for the new card/link.** Custom events to maintain:
  - `nav_click` — anchor nav
  - `more_info_click` — drawer open buttons
  - `view_demo_click` — "View Demo" card links
  - `drawer_view_demo_click` — "View Demo Site" inside drawer
  - `client_site_click` — client site cards (includes vertical)
  - `template_click` — template cards
  - `thumbnail_click` — thumbnail image clicks

## Preferences
- **NEVER commit or push unless the user explicitly says to** — commits cost credits on Netlify, so only commit when directly asked
- Always merge PRs to main when committing to a branch
- Copy should be client-friendly (clients may see this page directly)
