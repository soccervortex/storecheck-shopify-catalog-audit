# StoreCheck — Shopify product catalog audit

[StoreCheck](https://getstorecheck.eu) is a review-first product catalog auditor for Shopify merchants. It helps merchants find catalog-quality issues before cleanup work turns into risky bulk editing.

**Live product:** https://getstorecheck.eu  
**Interactive demo:** https://getstorecheck.eu/demo  
**Product audit guide:** https://getstorecheck.eu/shopify-product-audit  
**Free audit checklist:** https://getstorecheck.eu/shopify-product-audit-checklist

![StoreCheck catalog health overview](assets/catalog-health-overview.png)

## What StoreCheck checks

StoreCheck groups explainable findings across seven areas:

- product structure, handles, SKUs, and variants
- titles and product descriptions
- product images and alt text
- pricing and compare-at pricing
- inventory data and configuration
- product SEO titles and meta descriptions
- vendors, product types, and tags

Merchants can connect an owned Shopify store for a live **read-only** catalog scan or upload a Shopify product CSV. Findings include severity, affected products, evidence, and Shopify-specific fix guidance.

## Review-first by design

StoreCheck is intentionally conservative about automation. A connected-store audit does not write product changes through the Shopify Admin API. Ambiguous pricing, inventory, classification, and content decisions remain merchant review items.

The deterministic safe CSV cleanup path is deliberately narrow: it only handles proven duplicate/empty tag hygiene cases, verifies the exact source CSV by SHA-256 fingerprint, and reparses/rescans the candidate output before download.

## Screenshots

### Category scores

![StoreCheck category score view](assets/category-scores.png)

### Action guidance

![StoreCheck issue action guidance](assets/action-guidance.png)

## Useful Shopify catalog resources

- [Shopify product audit](https://getstorecheck.eu/shopify-product-audit)
- [Shopify product audit checklist](https://getstorecheck.eu/shopify-product-audit-checklist)
- [Shopify product SEO audit](https://getstorecheck.eu/shopify-seo-audit)
- [Shopify catalog cleanup](https://getstorecheck.eu/shopify-catalog-cleanup)
- [Privacy](https://getstorecheck.eu/privacy)
- [Contact / support](https://getstorecheck.eu/contact)

## Repository scope

This is the public StoreCheck product showcase. The application source code, production configuration, credentials, and private operational material are intentionally not published here.

Shopify is a trademark of Shopify Inc. StoreCheck is an independent product and is not endorsed by Shopify Inc.
