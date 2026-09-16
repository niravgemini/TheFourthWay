# Fourthway Labs website redesign

Prepared 16 September 2026 for Nirav Bhatia. Static HTML, CSS, and JavaScript; no package installation, framework, or build step is needed.

## Pages
- `index.html`: redesigned company homepage, header navigation, services, Ads Agent feature section, approach, founder, and contact.
- `ads-agent.html`: simple product page, illustrative review screen, four-step interactive explanation, data use, and FAQs.
- `privacy.html`: privacy/data-use draft describing the supplied static website and current local, privately operated Ads Agent.
- `assets/`: shared styling, navigation/workflow script, and SVG favicon. Fonts use system families; no external assets are loaded.

## Preview locally
From this folder run `python -m http.server 8878 --bind 127.0.0.1` and open `http://127.0.0.1:8878/`.
The static pages can also be opened directly. Browsers use a mail application for email links and a calling application for phone links.

## Update the existing Vercel project
1. Extract this ZIP.
2. Keep a copy of your existing repository before replacing its files.
3. Put the CONTENTS of this folder at the root of the existing TheFourthWay repository. `index.html` and `vercel.json` should be at the root, with `assets` beside them.
4. Review the diff and create a preview deployment using a branch. With a connected Git repository, Vercel normally deploys branch pushes automatically. The site is static: Framework Preset Other, no build command, and the repository root as the output location if prompted.
5. Check the preview on desktop and phone. Merge to the configured production branch only when you are ready to publish.

Vercel documentation: https://vercel.com/docs/deployments

## Before publication / Google submission
- The live website has NOT been changed by preparing this package.
- Read and confirm `privacy.html` against your real hosting settings, record handling, client agreements, and any AI services you actually connect. It is a draft for owner review, not a legal-compliance certification.
- No analytics, advertising pixels, external fonts, signup backend, Google OAuth login, or AI calls are implemented in these pages. The old pretend newsletter success form has been replaced by email / WhatsApp / telephone links.
- The Ads Agent is described as privately operated by Nirav, in development, with production API access pending. Update that statement only after the status changes.
- The sample review screen and workflow explanation are illustrative; buttons in the explanation do not operate Google Ads.
- Company URL: https://www.fourthwaylabs.com/
- Suggested OAuth app homepage after deployment: https://www.fourthwaylabs.com/ads-agent.html
- Suggested privacy URL after owner review and deployment: https://www.fourthwaylabs.com/privacy.html
- These links describe the intended deployment locations; the new pages are not live merely because the ZIP exists. The owner must verify the domain and complete Google's access/branding process separately.

Google references:
https://support.google.com/cloud/answer/13807376
https://developers.google.com/terms/api-services-user-data-policy
https://developers.google.com/google-ads/api/docs/api-policy/brand-verification

## Operator contact update
The Ads Agent page identifies Nirav Bhatia as developer and operator, with nirav.gemini@gmail.com as its direct contact email. All pages include a floating WhatsApp link to +91 87349 42696. LinkedIn links use https://www.linkedin.com/in/niravbegins/.
