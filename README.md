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
1. **Hostinger Reach forms** — paste the Reach snippets where index.html says
   `HOSTINGER REACH FORM` (two places: Starter Kit, and Coming next). Tag Coming-next signups `continue-protect`.
2. **Starter Kit step 2** says "Your kit opens instantly, on this site." Keep only if Reach can redirect to /starter-kit.html after signup.
3. **Sample report** — the button reads "Sample report coming soon" until an approved sample PDF is added (instructions in a comment next to it).

## Editing
`index.html` is generated from `index.template.html` plus the Shelter Scan parts. Small text edits can be made directly in `index.html`.
