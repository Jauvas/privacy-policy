# PlanFlow Privacy Policy Website

`index.html` is a self-contained, responsive version of
`docs/PRIVACY_POLICY_DRAFT.md`. It uses semantic HTML, embedded CSS, and the
bundled `planflow-icon.png` app icon: no JavaScript, external fonts, analytics,
cookies, or third-party runtime network requests.

## Before publishing

1. Confirm that `JayOabs, Uganda` is the correct legal publisher/controller.
2. Confirm that `aurexlabs1@gmail.com` is monitored for privacy requests.
3. Re-run the HTML anchor/no-tracker check documented in `docs/TESTING.md`.
4. Deploy this directory's contents at the root of a public HTTPS static site.
5. Update `src/constants/privacy.ts` and the Google Play/App Store Connect
   privacy-policy fields with the final URL.

The page intentionally has no build step. GitHub Pages can serve `index.html`
directly from a publishing branch or from a repository dedicated to the policy.
