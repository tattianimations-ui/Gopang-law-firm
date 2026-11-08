# Gopang Law Firm website
A static, self-contained site. No build step.

- `index.html` is the whole site (pages switch with `#` links, English/Urdu with RTL). Images are embedded in the file.
- `assets/` holds the original portrait and court photos. `content/` holds the copy as JSON for reference.
- To edit text, open `index.html` and search for the sentence, in both the `en` and `ur` blocks.

## Publish
- **Vercel:** import this repo, framework preset "Other", deploy. Then add `www.gopanglaw.com` under Domains.
- **GitHub Pages:** Settings, Pages, deploy from branch `main`, folder `/ (root)`.

## Notes
- The enquiry form is a placeholder and does not send email yet. Phone, WhatsApp and email links work.
- Pages use `#` links. For stronger search ranking, move to separate URLs (for example a Next.js version).
- The biography is a placeholder.
