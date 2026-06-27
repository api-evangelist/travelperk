# TravelPerk (travelperk)

TravelPerk is a business-travel management platform that lets companies book and manage flights, hotels, trains, and cars in one place. Its Open API gives partners and customers programmatic access to bookings and trips, invoices and expenses, travelers and members, cost centers, scheduled reports, and webhooks for real-time travel and finance data exchange with HR systems, ERPs, and expense tools.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/travelperk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/travelperk/refs/heads/main/apis.yml)

## Tags

- Business Travel
- Travel Management
- Expenses
- Invoices
- Bookings

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### TravelPerk Bookings & Trips API

Retrieve trips and their bookings - confirmed or canceled flights, hotels, trains, and cars - along with traveler detail and trip custom fields, for syncing travel itineraries into downstream systems.

- **Human URL:** [https://developers.travelperk.com/reference/introduction-3](https://developers.travelperk.com/reference/introduction-3)
- **Base URL:** `https://api.travelperk.com`

#### Tags

- Bookings
- Trips
- Travel

#### Properties

- [Documentation](https://developers.travelperk.com/reference/introduction-3)
- [API Reference](https://developers.travelperk.com/reference/list-all-trips)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TravelPerk Invoices API

List and retrieve invoices, invoice lines, invoice profiles, and invoice PDFs for accounting, reconciliation, and finance reporting.

- **Human URL:** [https://developers.travelperk.com/reference/list-invoice](https://developers.travelperk.com/reference/list-invoice)
- **Base URL:** `https://api.travelperk.com`

#### Tags

- Invoices
- Billing
- Finance

#### Properties

- [Documentation](https://developers.travelperk.com/reference/the-invoice-object)
- [API Reference](https://developers.travelperk.com/reference/list-invoice)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TravelPerk Expenses API

Access invoice and invoice-line data for expense reporting and accounting, mapping travel spend to cost centers and downstream expense tools.

- **Human URL:** [https://support.travelperk.com/hc/en-us/articles/360046079392-Getting-the-Expenses-API](https://support.travelperk.com/hc/en-us/articles/360046079392-Getting-the-Expenses-API)
- **Base URL:** `https://api.travelperk.com`

#### Tags

- Expenses
- Reporting
- Finance

#### Properties

- [Documentation](https://support.travelperk.com/hc/en-us/articles/360046079392-Getting-the-Expenses-API)
- [API Reference](https://developers.travelperk.com/reference/list-invoice-lines-1)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TravelPerk Travelers & Members API

Manage travelers and members via a SCIM 2.0 user provisioning interface - create, read, update, and replace users and read user schemas for IdP-driven sync from HR and identity systems.

- **Human URL:** [https://developers.travelperk.com/reference/using-the-scim-api-1](https://developers.travelperk.com/reference/using-the-scim-api-1)
- **Base URL:** `https://api.travelperk.com/scim`

#### Tags

- Members
- Travelers
- SCIM

#### Properties

- [Documentation](https://developers.travelperk.com/docs/introduction-1)
- [API Reference](https://developers.travelperk.com/reference/create-a-new-user)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TravelPerk Cost Centers API

Automatically create, list, retrieve, update, bulk-update, and archive cost centers and assign users to them for allocating travel spend across teams and projects.

- **Human URL:** [https://developers.travelperk.com/reference/cost-centers](https://developers.travelperk.com/reference/cost-centers)
- **Base URL:** `https://api.travelperk.com`

#### Tags

- Cost Centers
- Allocation
- Finance

#### Properties

- [Documentation](https://developers.travelperk.com/reference/cost-centers)
- [API Reference](https://developers.travelperk.com/reference/list-cost-centers)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TravelPerk Webhooks API

Subscribe to platform events - such as a new invoice or trip change - by creating and updating webhook endpoints that push real-time notifications to your application.

- **Human URL:** [https://developers.travelperk.com/docs/subscribing-to-webhooks](https://developers.travelperk.com/docs/subscribing-to-webhooks)
- **Base URL:** `https://api.travelperk.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.travelperk.com/docs/subscribing-to-webhooks)
- [API Reference](https://developers.travelperk.com/reference/subscribe-to-event)
- [OpenAPI](openapi/travelperk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/travelperk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/travelperk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/travelperk)
- [LinkedIn](https://www.linkedin.com/company/travelperk)
- [Website](https://www.travelperk.com)
- [Documentation](https://developers.travelperk.com/docs)
- [Plans](plans/travelperk-plans-pricing.yml)
- [Rate Limits](rate-limits/travelperk-rate-limits.yml)
- [Fin Ops](finops/travelperk-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
