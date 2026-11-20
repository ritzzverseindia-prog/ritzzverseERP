# Ritzzverse India

A responsive creative agency website for Ritzzverse India, built with HTML, CSS, JavaScript and Vite. No database or paid service required.

## Important before launch

**Replace `hello@example.com` in `script.js` with your real, verified business email address.** The enquiry form uses `mailto:` to open a visitor's email application; it does not send or store submissions automatically. For a fully working server-side contact form, integrate a form service or serverless function later.

The site contains example marketing copy and illustrative package descriptions, not claims about real clients, results, or prices. Review and edit the content before publication.

## Run locally

1. Install Node.js 20.19+ or 22.12+.
2. In the project folder run:

```bash
npm install
npm run dev
```

3. Open the local URL shown by Vite (usually http://localhost:5173).

## Deploy with GitHub and Vercel

1. Create a new GitHub repository named `ritzzverse-india`.
2. Upload the contents of this folder to the repository root, including `package.json` and `index.html`.
3. In Vercel, select **Add New > Project**, import the GitHub repository, and deploy.
4. Vercel should detect Vite. If asked: **Build Command:** `npm run build`; **Output Directory:** `dist`.
5. After updating the repository, Vercel will automatically redeploy when Git integration is enabled.

## Customize

- Brand colors: `:root` variables in `styles.css`
- Page copy, services and packages: `index.html`
- Contact form recipient: `businessEmail` in `script.js`
- Browser title and SEO metadata: `<head>` in `index.html`

## Notes

The design uses Google Fonts and otherwise does not depend on external images or assets. It includes mobile navigation, reduced-motion support, and basic metadata.
