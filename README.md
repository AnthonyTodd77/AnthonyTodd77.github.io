# Zhen Tao — Academic Website

Static academic homepage for Zhen Tao, published with GitHub Pages.

## Local preview

Open `index.html` directly, or serve this folder with any static HTTP server.

## Updating the site

The editable source lives in `../zhen-tao-academic-site`. After updating it and starting the local development server on port 3000, run:

```powershell
node scripts/export-github-pages.mjs
```

### Adding a news item

Edit the `news` array in `../zhen-tao-academic-site/app/site-data.ts`. Add the newest item at the top, then run the export command above. Use one of these status labels in the copy: `published`, `accepted`, `pre-accepted`, `scheduled to present`, or `attended`.
