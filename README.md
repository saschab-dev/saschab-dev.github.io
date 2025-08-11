# Sascha B – Portfolio (Starter Pack)

This is a minimal, clean portfolio starter ready for **GitHub Pages** with a custom domain.

## Quick Start (GitHub Pages)
1. Create a public repo named: `<your-username>.github.io`
2. Add these files to the repo (or upload the ZIP’s contents).
3. Commit and push.
4. In **Settings → Pages**, set the source to `main` (if needed).
5. (Custom domain) In **Settings → Pages → Custom domain**, enter your domain (e.g., `saschab.dev`). This creates/uses a `CNAME` file automatically.

## DNS Setup (Custom Domain)
- Create a **CNAME** record at your domain registrar:
  - **Name/Host:** `www`
  - **Value:** `<your-username>.github.io`
- (Optional root domain) Create **ALIAS/ANAME** (or A) records for `@` to GitHub Pages:
  - A Records to: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- Enable **Enforce HTTPS** in GitHub Pages settings once the certificate is issued.

> Tip: If you prefer a single page at the root (no `www`), you can set up redirects at your registrar or use Cloudflare to handle root → `www` redirection cleanly.

## Customize
- Edit text in `index.html` (About, Projects, Contact)
- Update the “Live Demo” and “GitHub” links per project
- Edit colors and spacing in `styles.css`
- Replace email/links in the Contact section

## Next Steps
- Add project screenshots to the `assets/` folder and reference them in `index.html`
- As you finish Django/LLM projects, add them to the **Featured Projects** grid
- Later, migrate to a Django app on Render/Heroku and keep this static site as your landing page

## License
MIT – do whatever you want, just keep the copyright notice.

