# SmartTrust Realty

A responsive React + TypeScript + Vite real estate concept website.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

## Publish with Vercel

1. Push the project folder to a GitHub repository (do not include `node_modules`).
2. In Vercel, select **Add New > Project**, import the GitHub repository, and deploy.
3. Vercel detects Vite. Build command: `npm run build`; output directory: `dist`.
4. Test the published site, then add a custom domain and verify it in Google Search Console.

## IMPORTANT: Demo limitations

- All properties, prices, photos and locations are **fictional examples**; the images are illustrative Unsplash photos.
- Search, property filters, property detail modals and favourites work in the browser. Favourites reset when the page reloads.
- The enquiry form is **demo-only** and intentionally does not send or save any personal data.
- No real authentication, database, property management, document storage, payments or bookings are implemented.
- Before a real business launch: add verified listings and licensed photography, configure a secure backend (such as Supabase with Row Level Security), connect enquiry submissions, publish accurate business details, privacy and terms pages, and test security and accessibility.
- No Supabase keys are needed for this demonstration; do not add secret service-role keys to Vite environment variables.
