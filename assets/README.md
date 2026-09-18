# Browns Business Group Website

A mobile-first, bilingual (English/Spanish), multi-page static website built for Netlify.

## Included pages

English:
- Home
- Services
- Real Estate
- Business Growth
- About
- Contact
- Thank-you page

Spanish versions are under `/es/`.

## Brand colors used

- Deep green: `#041817`
- Forest green: `#10322E`
- Brand gold: `#AD802D`
- Accent gold: `#C49637`
- Warm cream: `#F7F4EC`

The included logo was optimized to WebP for faster loading while the original PNG is preserved in `/assets/logo-original.png`.

## Deploying to Netlify

1. Upload this entire folder to a Netlify site (or deploy the ZIP containing the folder contents).
2. Netlify will detect the form named `contact` because both contact pages use `data-netlify="true"`.
3. In the Netlify site's form notification settings, add an **email notification for the `contact` form** and set the recipient to:

   `markgainesville@gmail.com`

4. Submit one test inquiry after deployment and confirm the notification arrives.

### Important note about Netlify email delivery

A static Netlify form cannot hard-code the notification recipient email address in the HTML. The form is fully wired for Netlify Forms, but the recipient must be configured once in the Netlify site dashboard. All English and Spanish inquiries use the same `contact` form name so they can feed the same notification workflow.

## Editing

Shared styles: `/assets/styles.css`

Shared JavaScript: `/assets/site.js`

English pages: project root

Spanish pages: `/es/`

## Production checklist

- Connect the final custom domain.
- Add the Netlify email notification described above.
- If a phone number, office address, social profiles, or business hours become available, add them to the Contact page and structured data.
- Confirm that any services requiring professional licensing are offered only as legally permitted or through appropriately licensed professionals.
