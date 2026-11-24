# MGS Garden & Landscape × Montalban Gardening Supplies

Deployable static website for Cloudflare Pages, GitHub Pages, or any static web host.

## Deploy to Cloudflare Pages
1. Extract this ZIP.
2. In Cloudflare dashboard, open **Workers & Pages → Create → Pages → Upload assets**.
3. Upload the **contents** of `mgs-gardening-website` (or upload the folder, depending on the interface).
4. Publish. No build command, framework, server, PHP, or database required.

For Git-based Cloudflare Pages deployments: Framework preset **None**, build command **blank**, output directory **/** (repository root).

## Pages
- `/` Home
- `/about/` About Us
- `/products/` Products with category filtering
- `/services/` Services
- `/projects/` Portfolio
- `/contact/` Contact and email inquiry

## Editing content
- `assets/app.js`: productData, serviceData, projectData and copy.
- `assets/style.css`: shared site theme and responsive styles.
- `assets/*.webp`: visual assets.
- `assets/content.json`: matching reference dataset for future CMS integration; current static site reads its inlined copy in app.js for reliable file-hosted deployment.

## Important before public launch
- The company logos were provided as images, and some website photography is cropped from AI-generated mockups. Replace these with high-resolution official assets and actual project photographs.
- Product categories, services, mission/vision, projects, and clients are illustrative pending company approval. Do not treat sample project cards as completed work.
- Confirm product availability and actual best sellers before making such claims.
- Phone and email came from the supplied MGS company graphic. Confirm accuracy.
- Contact form opens the visitor's email client using mailto; it does not send server-side and requires the visitor to send the email.
- Google Fonts require network access; fallback fonts are included.
- Do not upload private customer data into the static site.
