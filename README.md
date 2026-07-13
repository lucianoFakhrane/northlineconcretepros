# Northline Concrete Pros

Local SEO website for a free service that helps Quad Cities homeowners connect with available local concrete professionals.

## Stack

- Astro static site
- Cloudflare hosting and DNS
- Formspree form processing

## Local development

Requires Node.js 22.12 or newer.

```sh
npm install
npm run dev
```

The production domain is `https://northlineconcretepros.com/`.

## Validation

```sh
npm run check
npm run build
```

The build output is written to `dist/`. Every production change should keep canonical URLs, sitemap URLs and structured data on the apex (non-`www`) hostname.

## Contact form

The estimate request form is processed by Formspree. It includes required consent and an anti-spam honeypot. Test submissions must be clearly identified as tests and verified in the receiving mailbox.

## Deployment

Changes pushed to `main` are deployed through the connected Cloudflare project. After deployment, verify the canonical tag, sitemap, robots file, structured data and hostname redirects on the public site.
