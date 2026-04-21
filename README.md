# BigCommerce (bigcommerce)
BigCommerce is a leading e-commerce platform providing APIs for building and managing online stores, products, catalogs, orders, customers, checkouts, payments, and shipping. BigCommerce powers tens of thousands of online stores with its open SaaS architecture.

**URL:** [https://developer.bigcommerce.com/](https://developer.bigcommerce.com/)

## Tags:

 - E-Commerce, Retail, Catalog, Orders, Checkout, Payments, SaaS

## Timestamps

- **Created:** 2023-11-21
- **Modified:** 2026-04-19

## APIs

BigCommerce exposes 65+ REST API domains. Key API groups include:

- **Catalog** — Products, variants, categories, brands, modifiers
- **Orders** — Order management, fulfillment, shipments
- **Customers** — Customer accounts, groups, address books
- **Carts & Checkout** — Shopping carts, checkout sessions
- **Payments** — Accepted methods, payment processing
- **Channels** — Multi-storefront, marketplace channel management
- **Content** — Pages, blogs, redirects
- **Shipping** — Zones, methods, carrier connections
- **Webhooks** — Real-time event subscriptions

## Common Properties

- [Portal](https://developer.bigcommerce.com/)
- [Documentation](https://developer.bigcommerce.com/docs/api)
- [GettingStarted](https://developer.bigcommerce.com/docs/start)
- [Authentication](https://developer.bigcommerce.com/docs/start/authentication/api-accounts)
- [Webhooks](https://developer.bigcommerce.com/docs/integrations/webhooks)
- [GitHubOrganization](https://github.com/bigcommerce)

## Features

| Name | Description |
|------|-------------|
| Multi-Storefront | Manage multiple storefronts from a single BigCommerce account. |
| Catalog Management | Full CRUD API for products, variants, categories, and brands. |
| Order Management | Create, update, and fulfill orders with the Order Management API. |
| Checkout API | Build custom checkout experiences with the Checkout API. |
| Payment Processing | Accept payments via 65+ payment gateway integrations. |
| Webhooks | Receive real-time event notifications for store activity. |
| Customer Management | Manage customer accounts, groups, and address books via API. |
| Shipping Management | Configure shipping zones, methods, and carrier integrations. |
| Channel Manager | Sell across channels including storefronts, marketplaces, and social. |
| GraphQL Storefront API | Query storefront data via GraphQL for headless commerce builds. |

## Use Cases

| Name | Description |
|------|-------------|
| Headless Commerce | Build custom storefronts powered by BigCommerce APIs and GraphQL. |
| ERP Integration | Sync orders, inventory, and customers with ERP systems via API. |
| Marketplace Selling | List products and sync inventory across Amazon, eBay, and other marketplaces. |
| Custom Checkout | Replace the standard checkout with a branded custom checkout experience. |
| Wholesale Portals | Build B2B wholesale portals with customer group pricing and quote workflows. |
| Order Fulfillment Automation | Automate order fulfillment with warehouse management and 3PL systems. |

## Integrations

| Name | Description |
|------|-------------|
| Stripe | Accept card payments via Stripe payment gateway integration. |
| PayPal | Accept PayPal and Venmo payments on BigCommerce storefronts. |
| ShipStation | Sync orders and manage fulfillment with ShipStation. |
| Salesforce | Sync customer and order data with Salesforce CRM. |
| NetSuite | Integrate BigCommerce with NetSuite ERP for unified commerce. |
| Klaviyo | Sync customer and order data to Klaviyo for email marketing automation. |
| Google Shopping | Sync product catalog to Google Shopping for paid and organic visibility. |

## Capabilities

### Shared Per-API Definitions

- [BigCommerce APIs](capabilities/shared/bigcommerce.yaml) — 11 operations for catalog, orders, and customers

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Catalog Management](capabilities/catalog-management.yaml) | BigCommerce | 11 | Store Developer, Merchant |

## Vocabulary

- [BigCommerce Vocabulary](vocabulary/bigcommerce-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 1 workflow, and 2 personas

## Rules

- [BigCommerce Spectral Rules](rules/bigcommerce-spectral-rules.yml) — 24 rules across 9 categories enforcing BigCommerce API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
