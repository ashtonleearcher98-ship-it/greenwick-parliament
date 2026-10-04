# Greenwick Parliament Website

A complete static website for the Parliament of the Commonwealth of Greenwick, built from the supplied 4 October 2026 website information archive and image assets.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload **all files and folders in this repository** to the repository root.
3. Ensure the default branch is named `main`.
4. Open **Settings → Pages** and set **Source** to **GitHub Actions**.
5. Push a commit (or run the `Deploy Greenwick Parliament to GitHub Pages` workflow manually).
6. GitHub will provide the public Pages URL after deployment.

## Optional custom domain

Create a file named `CNAME` in the repository root containing only your domain, then point the domain's DNS records to GitHub Pages. Update `robots.txt` and `sitemap.xml` to replace the placeholder GitHub Pages URL.

## Site structure

- 42 source-derived information pages plus a custom 404 page
- Responsive government-style navigation and mobile menu
- Client-side site search (`Ctrl/Cmd + K` also opens search)
- Parliament 360-style interactive image explorer
- GitHub Actions deployment workflow
- No framework, build step, server, API, database, or paid hosting dependency

## Source fidelity note

The supplied archive contains internally inconsistent office-holder and election references on different pages (for example Sean Mannix, Thomas Delvecchio, and Michael Trent appear in different contexts). This repository preserves page-specific archive wording rather than silently rewriting the source. The dedicated Prime Minister page and home page use Sean Mannix because the archive explicitly identifies him as the sixth Prime Minister following Thomas Delvecchio's 2026 resignation.

The original `Prime Ministers` and `Latest` pages contained little or no substantive body text in the capture. Those two pages are reconstructed from other information in the same archive and link back into the site's primary records.

## Assets

All supplied Greenwick images are stored in `assets/img/`.
