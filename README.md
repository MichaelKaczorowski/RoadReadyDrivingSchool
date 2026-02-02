# Road Ready Driving School (Static)

This folder is ready to upload to **GitHub** and host with **GitHub Pages**.

## What was changed from the original backup
- Converted Server-Side Includes (SSI like `<!--#include ...-->`) into plain HTML so it works on static hosting.
- Replaced the old server-side `test/test.pl` "Sample Test" links with `driving_test.html`.
- Replaced the old server-side scheduling/test embed (`<!--#exec cgi=...-->`) with a static message and contact email.
- Removed absolute links to `roadreadydrivingschool.com` where possible so the site works from GitHub Pages.
- Extracted the shared CSS into `styles.css`.
- Added `.nojekyll` to avoid GitHub Pages/Jekyll special handling.

## How to publish
1. Create a GitHub repository (public is easiest for Pages).
2. Upload **all files in this folder** to the repo root.
3. In GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** (or `master`) / Folder: **/(root)**
4. Your site will be published at a `github.io` URL.

## Notes
This is a static site. Any original server-side Perl/CGI functionality is not included.
