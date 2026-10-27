# ruckusapp.ai

Static website for the Ruckus iOS app, hosted on GitHub Pages with the custom domain in `CNAME`.

- `/` home page
- `/support/` contact form (Formspree form `mvkkadnr`, delivered to the Ruckus inbox) and FAQ
- `/privacy/` Privacy Policy and `/terms/` Terms of Service, generated with Termly

## Updating the policies

Paste Termly's exported HTML between the `PRIVACY POLICY` / `TERMS OF SERVICE` markers. Termly leaves
blanks for a street address, email and mailing address; remove the address entirely and point contact
lines to https://ruckusapp.ai/support instead. Repeat this after every Termly re-export.

The app links to `/privacy/`, `/terms/` and `/support/`, so keep those paths stable.
