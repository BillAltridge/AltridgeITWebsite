# Altridge IT Static Website

This is a static HTML/CSS/JavaScript website ready for Cloudflare Pages, GitHub Pages, Azure Static Web Apps, or Netlify.

## Files

- `index.html` - main site page
- `styles.css` - responsive styling
- `script.js` - mobile navigation and footer year
- `README.md` - setup notes

## Cloudflare Pages deployment

1. Create a GitHub repository named `altridge-it-site`.
2. Upload these files to the repository.
3. In Cloudflare, go to Workers & Pages > Pages > Create project.
4. Connect your GitHub account.
5. Select the repository.
6. Framework preset: None.
7. Build command: leave blank.
8. Build output directory: `/`
9. Deploy.

## Custom domain

After deployment:

1. In Cloudflare Pages, open the project.
2. Go to Custom domains.
3. Add `altridgeit.com`.
4. Add `www.altridgeit.com`.
5. Set `www` to redirect to the root domain or keep both active.

## Contact form note

The included contact form uses `mailto:contact@altridgeit.com`, which opens the visitor's email app.

For a better production form, use one of these:

- Formspree
- Basin
- Cloudflare Workers
- Microsoft Forms
- HubSpot form embed
