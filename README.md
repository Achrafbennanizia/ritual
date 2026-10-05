# Ritual Edit

Editorial beauty discovery + affiliate commerce.

## Business model

Ritual Edit is an affiliate storefront. Unless a merchant integration explicitly authorizes direct sales, the site does not collect payment, shipping or billing details. Product CTAs route visitors through `/out/[offerId]` to an approved retailer destination.

## Development

```bash
npm install
npm run dev
```

Before launch:

```bash
npm run typecheck
npm run test
npm run build
```

The current content intentionally uses demo affiliate offers and approved=false placeholder imagery. Replace them only with assets and destinations that the relevant brand/network has authorized.

## First commercial integrations

1. Awin
2. Stylevana
3. Shopify Collabs / direct Beauty of Joseon creator relationship
4. Direct brand programs such as Paula's Choice where approved

Do not publish commission rates, prices, stock or image assets unless verified and authorized.
# ritual
