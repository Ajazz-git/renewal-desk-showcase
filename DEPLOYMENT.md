# Deployment

## Preferred hosting: GitHub Pages

This repository is a static HTML site, so GitHub Pages is the simplest fit. No framework build step or external deployment platform is needed.

One-time repository setting (requires repository admin/maintainer access):

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Save.

GitHub Pages will serve the `index.html` and assets from the repository root and publish future pushes from that source.

**Expected site URL:** https://ajazz-git.github.io/renewal-desk-showcase/

The repository is public, which is eligible for GitHub Pages on GitHub Free. GitHub's documentation recommends branch publishing when no custom build process is needed.

## Vercel fallback deployment

A one-time static Vercel deployment was created during setup troubleshooting. It is not the preferred/canonical hosting target and is not connected to the private Renewal Desk application repository.

- Vercel project: `renewal-desk-showcase`
- Vercel URL: https://renewal-desk-showcase.vercel.app/
- GitHub automatic deployment: not connected.

Once GitHub Pages is confirmed live, the Vercel fallback can be removed to avoid maintaining two hosting locations.
