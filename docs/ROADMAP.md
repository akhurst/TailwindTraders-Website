# CraftLocal 2026 Roadmap

**Planning Type:** Epic
**Projects:** Seller Onboarding, Payments & Checkout, Search & Discovery
**Last Updated:** 2026-03-09

---

## Backlog

### Tax Calculation & Compliance [MEDIUM]
**Type:** Epic | **Start:** 3/16/2026 12:00:00 AM | **End:** 4/15/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.35% | **Size:** 13 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** api, security

Sales tax calculation and remittance using TaxJar API. Handle multi-jurisdiction nexus determination, marketplace facilitator rules, and tax-exempt categories.

**Sub-items:**
- [ ] Integrate tax calculation API (TaxJar) (Backlog)

### Admin Reporting Dashboard [LOW]
**Type:** Epic | **Start:** 4/1/2026 12:00:00 AM | **End:** 5/1/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.2% | **Size:** 13 | **Teams:** Founders | **Product:** Marketplace | **Tags:** api, ux

Internal admin dashboard for marketplace operators. Revenue reports, transaction logs, seller performance metrics, and dispute resolution queue.

**Sub-items:**
- [ ] Create admin revenue report page (Backlog)

### Seller Analytics Dashboard [MEDIUM]
**Type:** Epic | **Start:** 3/16/2026 12:00:00 AM | **End:** 4/15/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.3% | **Size:** 13 | **Teams:** Founders | **Product:** Seller Tools | **Tags:** performance, ux

Analytics dashboard for sellers showing sales trends, top products, customer demographics, and revenue projections. Interactive charts with date range filtering.

### Refund & Dispute Management [MEDIUM]
**Type:** Epic | **Start:** 4/1/2026 12:00:00 AM | **End:** 5/15/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.25% | **Size:** 13 | **Teams:** AI Agent Beta | **Product:** Marketplace | **Tags:** ux, security

Customer refund workflow and Stripe dispute handling. Support full/partial refunds, return merchandise authorization, and chargeback evidence submission.

## Done

### Seller Registration Flow [URGENT]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 2/15/2026 12:00:00 AM | **Increment:** Alpha | **Confidence:** 1% | **Size:** 13 | **Teams:** AI Agent Beta, Founders | **Product:** Seller Tools | **Tags:** security, ux

Complete seller registration and onboarding wizard. Multi-step form with identity verification, business details, payment setup, and profile creation.

**Sub-items:**
- [x] Seller registration fails with special characters in business name (Done)
- [x] Implement seller identity verification flow (Done)
- [x] Build multi-step seller registration wizard (Done)
- [ ] Seller dashboard session expires without warning (In Progress)
- [x] Build email verification for seller registration (Done)

### Shopping Cart & Checkout Flow [HIGH]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 2/15/2026 12:00:00 AM | **Increment:** Alpha | **Confidence:** 1% | **Size:** 21 | **Teams:** AI Agent Beta | **Product:** Marketplace | **Tags:** marketplace, ux

Full shopping cart with multi-seller support, session persistence, address validation, and multi-step checkout flow.

**Sub-items:**
- [x] Build shopping cart with session persistence (Done)
- [ ] Checkout form doesn't validate ZIP code format (Ready)
- [x] Create multi-step checkout flow with address validation (Done)
- [x] Cart total doesn't update when quantity changes (Done)
- [x] Build order confirmation email templates (Done)

### User Account Management [MEDIUM]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 2/1/2026 12:00:00 AM | **Increment:** Alpha | **Confidence:** 1% | **Size:** 8 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** ux, security

Buyer account management including profile editing, password reset, email verification, saved addresses, and order history. OAuth login with Google and Apple.

**Sub-items:**
- [x] Build password reset flow (Done)

### Artisan Profile Pages [HIGH]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 2/15/2026 12:00:00 AM | **Increment:** Alpha | **Confidence:** 0.9% | **Size:** 13 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** marketplace, ux

Create rich artisan profile pages with portfolio gallery, bio, reviews, location map, and product listings. Each artisan gets a unique shareable URL.

**Sub-items:**
- [ ] Add artisan reviews and ratings system (In Review)
- [x] Create artisan profile page with portfolio gallery (Done)
- [ ] Create seller verification badge system (In Review)

### Full-Text Product Search [HIGH]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 2/15/2026 12:00:00 AM | **Increment:** Alpha | **Confidence:** 0.95% | **Size:** 21 | **Teams:** AI Agent Alpha, AI Agent Beta | **Product:** Marketplace | **Tags:** marketplace, api

Implement Elasticsearch-powered full-text search across all product listings. Support autocomplete, typo tolerance, and synonym matching for artisan goods.

**Sub-items:**
- [ ] Search returns stale results after product update (In Progress)
- [ ] Mobile search results overlap header on small screens (Ready)
- [x] Build search results page with infinite scroll (Done)
- [x] Implement Elasticsearch integration for product catalog (Done)

## In Progress

### Email Notification System [MEDIUM]
**Type:** Epic | **Start:** 2/16/2026 12:00:00 AM | **End:** 3/15/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.6% | **Size:** 8 | **Teams:** AI Agent Alpha | **Product:** Seller Tools | **Tags:** api

Transactional email system for seller onboarding milestones, order notifications, and marketing digests. Template-based with SendGrid integration and unsubscribe management.

**Sub-items:**
- [ ] Implement order status email notifications (In Progress)

### Category & Filter System [HIGH]
**Type:** Epic | **Start:** 2/2/2026 12:00:00 AM | **End:** 3/15/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.7% | **Size:** 21 | **Teams:** AI Agent Beta | **Product:** Marketplace | **Tags:** ux, marketplace

Build a hierarchical category taxonomy with faceted filtering. Enable buyers to narrow results by category, price range, material, location, and seller rating.

**Sub-items:**
- [x] Create category taxonomy and seed data (Done)
- [ ] Create wishlist feature (Backlog)
- [ ] Build faceted filter sidebar component (In Progress)
- [ ] Category filter count mismatch on mobile viewport (Ready)

### Order Fulfillment Workflow [HIGH]
**Type:** Epic | **Start:** 2/16/2026 12:00:00 AM | **End:** 4/1/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.6% | **Size:** 21 | **Teams:** AI Agent Beta | **Product:** Seller Tools | **Tags:** marketplace, api

End-to-end order fulfillment pipeline for sellers. Order acceptance, packing, shipping label generation, tracking updates, and delivery confirmation.

**Sub-items:**
- [ ] Build order notification and fulfillment queue (In Progress)
- [ ] Create shipping label generation integration (Backlog)

### Product Listing Management [HIGH]
**Type:** Epic | **Start:** 2/2/2026 12:00:00 AM | **End:** 3/15/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.7% | **Size:** 21 | **Teams:** AI Agent Alpha | **Product:** Seller Tools | **Tags:** ux, api

Full product listing CRUD with image upload, variant management (size, color, material), pricing, and inventory fields. Rich text descriptions with markdown support.

**Sub-items:**
- [ ] Build product variant management (size, color, material) (Ready)
- [ ] Create product listing form with image upload (In Progress)
- [ ] Product image upload timeout on files > 5MB (In Progress)

### Stripe Payment Integration [URGENT]
**Type:** Epic | **Start:** 1/19/2026 12:00:00 AM | **End:** 3/1/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.75% | **Size:** 21 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** security, api

Integrate Stripe for card payments, marketplace fee splitting, and webhook event processing. PCI-DSS compliant with tokenized card data.

**Sub-items:**
- [ ] Implement Stripe Connect for marketplace split payments (In Progress)
- [x] Integrate Stripe Elements for card payments (Done)
- [ ] Payment webhook retry creates duplicate orders (In Progress)
- [ ] Cryptocurrency payment support (Cancelled)
- [ ] Stripe webhook signature verification fails in staging (In Review)

### Geolocation & Local Discovery [HIGH]
**Type:** Epic | **Start:** 2/16/2026 12:00:00 AM | **End:** 4/1/2026 12:00:00 AM | **Increment:** Beta | **Confidence:** 0.6% | **Size:** 21 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** marketplace, mobile

Enable location-based discovery so buyers can find artisans and products near them. Geocode seller addresses and support radius-based search with map view.

**Sub-items:**
- [ ] Build Near Me radius search with map view (Ready)
- [ ] Geocode seller addresses using Google Maps API (In Progress)

## Ready

### Artisan Payout System [HIGH]
**Type:** Epic | **Start:** 3/2/2026 12:00:00 AM | **End:** 4/1/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.5% | **Size:** 13 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** security, api

Automated payout system for artisans via Stripe Connect. Weekly batch processing, payout reports, and ACH direct deposit to seller bank accounts.

**Sub-items:**
- [ ] Build Stripe Connect Express onboarding for sellers (Ready)
- [ ] Implement weekly automated payout batch processing (Backlog)

### Inventory & Stock Tracking [MEDIUM]
**Type:** Epic | **Start:** 3/2/2026 12:00:00 AM | **End:** 4/1/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.5% | **Size:** 13 | **Teams:** AI Agent Alpha | **Product:** Seller Tools | **Tags:** performance, api

Real-time inventory management for artisan sellers. Track stock levels per variant, set low-stock alerts, and auto-pause listings when out of stock.

**Sub-items:**
- [ ] Implement real-time stock level tracking (Ready)

### Search Ranking & Relevance [MEDIUM]
**Type:** Epic | **Start:** 3/16/2026 12:00:00 AM | **End:** 4/15/2026 12:00:00 AM | **Increment:** Launch | **Confidence:** 0.4% | **Size:** 13 | **Teams:** AI Agent Alpha | **Product:** Marketplace | **Tags:** performance, api

Implement search ranking algorithm with configurable boost factors. Consider relevance, seller rating, product freshness, and geographic proximity.

**Sub-items:**
- [ ] Implement search ranking algorithm with boost factors (Backlog)
- [ ] Implement voice search for product discovery (Cancelled)

