# Shelter Secure website (sheltersecurenow.com) — Website 3

Upload this zip to the existing **sheltersecurenow.com** web app in Hostinger (Deployments → upload zip).
Settings: framework **Vite**, Node **22.x**, defaults. No environment variables needed.

## Pages
- `/` — home page (index.html)
- `/starter-kit.html` — the three free Starter Kit tools
- `/privacy.html` — Privacy Policy
- `/refund.html` — Refund Policy (14-day guarantee)
- Terms of Service link goes to the portal: https://app.sheltersecurenow.com/?terms

## Links (all in index.html, listed at the top of the file)
- Portal sign-in: https://app.sheltersecurenow.com
- Shelter Report System: https://flighttowerbook.mysamcart.com/shelter-secure-shelter-report-system
- Bundle: https://flighttowerbook.mysamcart.com/grid-adjacent-shelter-secure-bundle
- Grid-Adjacent course: https://flighttowerbook.mysamcart.com/grid-adjacent-course
- Instruction manual: https://app.loquy.ai/c/paulburgesshomes-6akeao/shelter-secure-instruction-manual
- Support: support@sheltersecurenow.com

## Still to finish
Nothing outstanding on the public site.

Done: Hostinger Reach forms are live — "SRS Starter Kit" (redirects to /starter-kit.html) and "SRS Coming Next" (tag `continue-protect`). The Reach `embed.js` script loads once at the end of index.html.
Done: Sample reports are live at `/samples/shelter-report-sample-full.pdf` and `/samples/shelter-report-sample-quick-view.pdf` (fictional household Alex & Jordan, in-town renter). The preview card and wording match the report engine: Low / Moderate / High concern across 11 areas.

## Deploying
Hostinger does not pull from GitHub for this site. After changes, download a zip of the repo and upload it in Hostinger: Deployments → Settings and redeploy → Upload new files → Redeploy.

## Editing
`index.html` is generated from `index.template.html` plus the Shelter Scan parts. Small text edits can be made directly in `index.html`.
