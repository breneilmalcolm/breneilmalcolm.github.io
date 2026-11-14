# Breneil Malcolm, PhD — Version 3 (final proof)

This is a **publication proof**, not yet a live deployment. Open `index.html` in a browser, or use a local static file server (`python -m http.server 8000`) from this folder. The six pages link to one another. Photographs are stored in `assets/` and the two uploaded PDF documents in `documents/`.

## Pages
- `index.html` — Home
- `research.html` — Research
- `scholarship.html` — Scholarship
- `professional-praxis.html` — Professional Praxis
- `leadership-service.html` — Leadership & Service
- `health-fitness-wellness.html` — Health, Fitness & Wellness

## GitHub Pages and custom domain (after approval)
1. Upload the **contents** of this folder to the root of the `breneilmalcolm.github.io` repository.
2. GitHub repository **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`.
3. In **Settings → Pages → Custom domain**, enter the exact domain you own. GitHub Pages can create the `CNAME` file automatically, or add one at the repository root containing just the domain.
4. At your domain registrar, configure DNS according to GitHub's current Pages guidance, choosing apex `@` A/AAAA records or a `www` CNAME as appropriate. Verify the domain in GitHub and enable **Enforce HTTPS** when available.
5. Wait for DNS propagation and verify both your GitHub Pages address and custom domain.

**The domain has not been set yet** because its exact spelling and preferred canonical host (`www` or apex) have not been confirmed. Do not add speculative DNS values.

## Pre-publication review
- Review the accuracy and current status of each listed credential and research item; CV and résumé supplied on Nov 14, 2026.
- Confirm permissions to publish group and client photographs, including visible photographer watermarks.
- Check links, mobile layouts, PDF downloads and contact details before going live.
- Some original pages include Google Fonts and may require an internet connection for the exact typography.


## Version 3 live-preview refinements (November 14, 2026)
- Homepage portrait displays in full using `object-fit: contain` (no body cropping).
- Academic CV and fitness résumé PDF links open in new tabs (browser PDF display depends on visitor settings).
- Removed outdated prototype and document-coming-soon text.
- Added a consistent Get in Touch footer to all six pages. The button opens the visitor's default email application, addressed to bxm5750@psu.edu.
- The contact email can be changed later to a domain-based email address.
- Do not add a CNAME or change DNS until final domain cutover.
