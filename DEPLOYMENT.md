# Deployment

## Current live site

- **URL:** https://renewal-desk-showcase.vercel.app/
- **Hosting project:** `renewal-desk-showcase`
- **Source repository:** `Ajazz-git/renewal-desk-showcase`
- **Published branch snapshot:** `main`
- **Mode:** Static file deployment

The current production site was published directly from the public repository files. The private Renewal Desk application repository was not connected or deployed.

## Automatic deployments

Git-based automatic deployments are not connected yet. Vercel reported that a GitHub Login Connection must be added to the Vercel account before the repository can be linked.

To enable automatic updates:

1. In Vercel, add or authorize the GitHub Login Connection for the account.
2. Connect `Ajazz-git/renewal-desk-showcase` to the existing `renewal-desk-showcase` Vercel project.
3. Set `main` as the production branch and confirm the root directory is the repository root.
4. Push a small reviewed change and verify that Vercel creates a production deployment.

Until then, changes pushed to GitHub will not automatically update the live site. Redeploy the static files manually after reviewing changes.
