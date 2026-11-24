# Deployment

## Hosting: GitHub Pages

Renewal Desk Showcase is a static HTML, CSS and JavaScript website. GitHub Pages is the primary host; a separate application server or framework build step is not required.

**Live URL:** https://ajazz-git.github.io/renewal-desk-showcase/

The GitHub Pages deployment completed successfully for the repository's `main` branch on **24 November 2026**. The successful run was GitHub's `pages build and deployment` workflow, and its deployment log reported the live URL above.

### Publishing source

The repository is published from the `main` branch at the repository root. GitHub Pages builds and deploys that content when the selected branch source is updated.

To review the setting, open [Repository Pages settings](https://github.com/Ajazz-git/renewal-desk-showcase/settings/pages). The publishing source should be **Deploy from a branch**, with branch `main` and folder `/(root)`.

### Workflow cleanup

The temporary custom Actions workflow was removed because GitHub Pages' branch-based publishing already handles deployment. This avoids running a second, unnecessary deployment workflow.

## Temporary Vercel fallback

A one-time static deployment was created during troubleshooting at https://renewal-desk-showcase.vercel.app/. It is not the primary site and is not connected to the private Renewal Desk application repository.

GitHub Pages is the canonical showcase URL. The Vercel fallback can be retired separately after confirming the Pages site is accessible.
