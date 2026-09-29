# SADEE SOLUTIONS — Real Store + Admin

Updated GitHub-ready version.

## Included
- Mobile-first SADEE SOLUTIONS storefront
- New uploaded showcase video (old video replaced)
- Product cards with images, prices and details
- WhatsApp BUY NOW to +94 76 847 2404
- Visible ADMIN button linking to `/admin/`
- Mobile navigation menu fixed
- Supabase product loading with local image fallbacks
- Supabase Auth admin login
- Admin email verification against `public.admin_users`
- Add / edit / delete products
- Product image upload to Supabase Storage
- Product availability, featured, price, description and features editing

## Supabase
`config.js` already contains the supplied project URL and publishable key.

Never put a service_role/secret key in browser code.

## Admin
Open:
`/admin/`

Login with the Supabase Authentication user that is also present in `public.admin_users`.
