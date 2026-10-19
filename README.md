# Caprino — Fresh Goat Milk Storefront Starter

A responsive, image-rich ecommerce **prototype** for the proposed Caprino fresh goat milk business in Mumbai.

## Preview
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Internet access is required for remote product imagery and Google Fonts. All primary layout/code files are included locally.

## Included in this package
- Responsive storefront, brand story, delivery information, FAQs and footer
- Product listing, search, size filters and sorting
- Demo product details and interactive shopping bag
- Sample checkout date/time selection (does not submit or store an order)
- Keyboard escape behavior, basic labels and responsive mobile navigation
- `supabase/schema.sql`: initial database design with row-level security policies

## Important: not production-ready
The storefront is a prototype and is not connected to any live database, real stock, customer accounts, order processing, delivery capacity, email/SMS or payment provider. Do not accept customer orders or payments through it. The photos, product sizes and prices are illustrative; replace them with verified product images and accurate commercial details.

## Production checklist
- Confirm supplier, cold-chain process, packaging, shelf-life/storage labels and applicable FSSAI/licensing/consumer requirements.
- Confirm delivery pin codes, actual delivery capacity, dates/slots, cut-off times and fees.
- Configure Supabase in the account dashboard, review the schema and run it only after understanding it. Keep service-role secrets server-side; never put them in browser code.
- Implement a server-side order function that validates price, stock, service area and slot capacity; protect admin access with authentication and authorization.
- Add a payment provider using its official server-side integration and verify payment webhooks before marking an order paid.
- Add privacy, refund/cancellation and contact policies; perform security, accessibility and end-to-end testing.
- Publish only after testing. A free hosting tier does not mean payment processing, domain names or all future usage are free.

## Fonts and images
The stylesheet imports Google Fonts and the page uses Unsplash image URLs. If you want to avoid external font requests, remove the Google Fonts `<link>` from `index.html`; system fallbacks are configured. Replace illustrative photos before commercial launch.
