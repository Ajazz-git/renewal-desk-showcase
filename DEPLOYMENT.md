# Deployment

## Hosting choice: GitHub Pages

GitHub Pages is the preferred host for this project. The showcase is a static HTML/CSS/JavaScript site with image assets. It does not need a server runtime or a framework build step.

**Expected URL:** https://ajazz-git.github.io/renewal-desk-showcase/

### One-time repository setting

A repository administrator needs to enable the Pages publishing source:

1. Open [Repository Pages settings](https://github.com/Ajazz-git/renewal-desk-showcase/settings/pages).
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Save if prompted.

The workflow at `.github/workflows/pages.yml` will then publish the site and deploy future pushes to `main` automatically. No custom token or secret is required for the normal deployment workflow.

### Why the first attempt failed

The first workflow run tried to create the GitHub Pages site automatically by setting `enablement: true` on `actions/configure-pages`. That option requires a token with repository administration and Pages permissions. The standard Actions `GITHUB_TOKEN` does not have the administration permission needed to create the Pages site, so GitHub returned **Resource not accessible by integration**.

The workflow now uses the normal GitHub Pages setup and does not try to enable the site through the workflow token. The repository's Pages source must be selected once in Settings by an administrator.

## Temporary Vercel fallback

A one-time static deployment was created while troubleshooting, at https://renewal-desk-showcase.vercel.app/. It is not the preferred hosting target, is not linked to the private application repository, and is not required for the GitHub Pages setup.

Once GitHub Pages is confirmed live, the Vercel fallback can be removed to avoid duplicate hosting.
