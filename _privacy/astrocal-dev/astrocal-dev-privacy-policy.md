---
api_specs:
- filename: astrocal-dev-activity-api-openapi.yml
  format: yaml
  label: Astrocal Activity API
  slug: astrocal-dev-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-activity-api-openapi.yml
- filename: astrocal-dev-api-keys-api-openapi.yml
  format: yaml
  label: Astrocal API Keys API
  slug: astrocal-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-api-keys-api-openapi.yml
- filename: astrocal-dev-availability-api-openapi.yml
  format: yaml
  label: Astrocal Availability API
  slug: astrocal-dev-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-availability-api-openapi.yml
- filename: astrocal-dev-booking-pages-api-openapi.yml
  format: yaml
  label: Astrocal Booking Pages API
  slug: astrocal-dev-booking-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-booking-pages-api-openapi.yml
- filename: astrocal-dev-bookings-api-openapi.yml
  format: yaml
  label: Astrocal Bookings API
  slug: astrocal-dev-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-bookings-api-openapi.yml
- filename: astrocal-dev-branding-api-openapi.yml
  format: yaml
  label: Astrocal Branding API
  slug: astrocal-dev-branding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-branding-api-openapi.yml
- filename: astrocal-dev-calendars-api-openapi.yml
  format: yaml
  label: Astrocal Calendars API
  slug: astrocal-dev-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-calendars-api-openapi.yml
- filename: astrocal-dev-conferencing-api-openapi.yml
  format: yaml
  label: Astrocal Conferencing API
  slug: astrocal-dev-conferencing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-conferencing-api-openapi.yml
- filename: astrocal-dev-event-type-hosts-api-openapi.yml
  format: yaml
  label: Astrocal Event Type Hosts API
  slug: astrocal-dev-event-type-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-event-type-hosts-api-openapi.yml
- filename: astrocal-dev-event-types-api-openapi.yml
  format: yaml
  label: Astrocal Event Types API
  slug: astrocal-dev-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-event-types-api-openapi.yml
- filename: astrocal-dev-organizations-api-openapi.yml
  format: yaml
  label: Astrocal Organizations API
  slug: astrocal-dev-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-organizations-api-openapi.yml
- filename: astrocal-dev-payments-api-openapi.yml
  format: yaml
  label: Astrocal Payments API
  slug: astrocal-dev-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-payments-api-openapi.yml
- filename: astrocal-dev-stripe-api-openapi.yml
  format: yaml
  label: Astrocal Stripe API
  slug: astrocal-dev-stripe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-stripe-api-openapi.yml
- filename: astrocal-dev-subscription-api-openapi.yml
  format: yaml
  label: Astrocal Subscription API
  slug: astrocal-dev-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-subscription-api-openapi.yml
- filename: astrocal-dev-support-api-openapi.yml
  format: yaml
  label: Astrocal Support API
  slug: astrocal-dev-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-support-api-openapi.yml
- filename: astrocal-dev-team-api-openapi.yml
  format: yaml
  label: Astrocal Team API
  slug: astrocal-dev-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-team-api-openapi.yml
- filename: astrocal-dev-test-data-api-openapi.yml
  format: yaml
  label: Astrocal Test Data API
  slug: astrocal-dev-test-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-test-data-api-openapi.yml
- filename: astrocal-dev-usage-api-openapi.yml
  format: yaml
  label: Astrocal Usage API
  slug: astrocal-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-usage-api-openapi.yml
- filename: astrocal-dev-waitlist-api-openapi.yml
  format: yaml
  label: Astrocal Waitlist API
  slug: astrocal-dev-waitlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-waitlist-api-openapi.yml
- filename: astrocal-dev-webhooks-api-openapi.yml
  format: yaml
  label: Astrocal Webhooks API
  slug: astrocal-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrocal-dev/openapi/astrocal-dev-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your email address, name, and organization name.
  - category: contact
    text: For each booking, we store the attendee's name, email address, meeting time, duration, and any notes provided.
  - category: financial
    text: We store only the Stripe account ID needed to process payments on your behalf via Stripe Connect.
  - category: behavioral
    text: We use PostHog for website analytics, including page views, feature usage, and session recordings.
  - category: device
    text: We log API requests including endpoints accessed, timestamps, response status codes, and rate limit consumption.
  - category: communication
    text: Booking confirmations, cancellations, and service announcements.
  deletion:
    route: Dashboard deletion of individual bookings; account closure; disconnecting calendar
    text: You can delete individual bookings from the dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: 'Service delivery: Processing bookings, syncing calendars, sending notifications, and enforcing rate limits.'
  - purpose: Billing
    text: 'Billing: Processing payments and managing subscriptions via Stripe.'
  - purpose: Support
    text: 'Support: Responding to your questions and troubleshooting issues.'
  - purpose: Product improvement
    text: 'Product improvement: Understanding how the platform is used to improve features and fix bugs (analytics data only, with your consent).'
  - purpose: Product and lifecycle email
    text: 'Product and lifecycle email: Occasional onboarding, activation, and product emails (e.g. a welcome, getting-started tips, or usage notices) sent to your account''s owner.'
  residency:
  - region: United States and European Union
    text: Your data may be processed in the United States and the European Union depending on the infrastructure providers used (Supabase, Vercel).
  retention:
  - period: null
    scope: Account data
    text: 'Account data: Retained while your account is active. Deleted upon account closure.'
  - period: null
    scope: Calendar data and OAuth tokens
    text: When you disconnect a calendar (via the dashboard) or close your account, the associated OAuth tokens and synced calendar data are deleted promptly.
  - period: 90 days
    scope: API logs
    text: 'API logs: Retained for 90 days.'
  - period: null
    scope: Booking data
    text: 'Booking data: Retained according to your organization''s settings.'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate personal data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data.'
  - right: Portability
    text: 'Portability: Request your data in a portable, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to the processing of your personal data.'
  - right: Withdrawal of consent
    text: 'Withdrawal of consent: Withdraw consent for analytics cookies at any time via the cookie banner.'
  role:
    text: Astrocal ("we", "us", "our") is a trading name of Archer Works Ltd (Company No. 17268358)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Astrocal does not sell your personal data. We do not share your data with third parties for their own marketing purposes.
  subprocessors:
    text: 'Supabase: Database hosting and authentication. Resend: Transactional email delivery. Stripe: Payment processing. Google Calendar API: Calendar integration and availability checks. Microsoft Calendar API: Calendar integration and availability checks. PostHog: Website analytics and session recordings (consent-gated). Google Ads: Advertising conversion measurement, including a hashed email address at signup for enhanced conversions (consent-gated). Vercel: Website and dashboard hosting.'
    url: null
  transfers:
  - mechanism: SCC
    text: Where data is transferred outside your region, we rely on standard contractual clauses and provider certifications to ensure adequate data protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Astrocal
provenance_date: '2026-11-09'
provider_name: Astrocal
provider_slug: astrocal-dev
slug: astrocal-dev-privacy-policy
source_date: '2026-11-09'
source_filename: astrocal-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.astrocal.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Astrocal\naid: astrocal-dev\nurl: https://www.astrocal.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Astrocal (\"we\", \"us\", \"our\") is a trading name of Archer Works Ltd (Company No. 17268358)\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your email address, name, and organization name.\n- category: contact\n  text: For each booking, we store the attendee's name, email address, meeting time, duration, and any notes provided.\n- category: financial\n  text: We store only the Stripe account ID needed to process payments on your behalf\
  \ via Stripe Connect.\n- category: behavioral\n  text: We use PostHog for website analytics, including page views, feature usage, and session recordings.\n- category: device\n  text: We log API requests including endpoints accessed, timestamps, response status codes, and rate limit consumption.\n- category: communication\n  text: Booking confirmations, cancellations, and service announcements.\npurposes:\n- purpose: Service delivery\n  text: 'Service delivery: Processing bookings, syncing calendars, sending notifications, and enforcing rate limits.'\n- purpose: Billing\n  text: 'Billing: Processing payments and managing subscriptions via Stripe.'\n- purpose: Support\n  text: 'Support: Responding to your questions and troubleshooting issues.'\n- purpose: Product improvement\n  text: 'Product improvement: Understanding how the platform is used to improve features and fix bugs (analytics\n    data only, with your consent).'\n- purpose: Product and lifecycle email\n  text: 'Product and lifecycle\
  \ email: Occasional onboarding, activation, and product emails (e.g. a welcome, getting-started\n    tips, or usage notices) sent to your account''s owner.'\nretention:\n- scope: Account data\n  period: null\n  text: 'Account data: Retained while your account is active. Deleted upon account closure.'\n- scope: Calendar data and OAuth tokens\n  period: null\n  text: When you disconnect a calendar (via the dashboard) or close your account, the associated OAuth tokens and\n    synced calendar data are deleted promptly.\n- scope: API logs\n  period: 90 days\n  text: 'API logs: Retained for 90 days.'\n- scope: Booking data\n  period: null\n  text: 'Booking data: Retained according to your organization''s settings.'\nresidency:\n- region: United States and European Union\n  text: Your data may be processed in the United States and the European Union depending on the infrastructure providers\n    used (Supabase, Vercel).\ntransfers:\n- mechanism: SCC\n  text: Where data is transferred outside\
  \ your region, we rely on standard contractual clauses and provider certifications\n    to ensure adequate data protection.\nsubprocessors:\n  url: null\n  text: 'Supabase: Database hosting and authentication. Resend: Transactional email delivery. Stripe: Payment processing.\n    Google Calendar API: Calendar integration and availability checks. Microsoft Calendar API: Calendar integration\n    and availability checks. PostHog: Website analytics and session recordings (consent-gated). Google Ads: Advertising\n    conversion measurement, including a hashed email address at signup for enhanced conversions (consent-gated).\n    Vercel: Website and dashboard hosting.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard deletion of individual bookings; account closure; disconnecting calendar\n  text: You can delete individual bookings from the dashboard.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right:\
  \ Correction\n  text: 'Correction: Request correction of inaccurate personal data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data.'\n- right: Portability\n  text: 'Portability: Request your data in a portable, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to the processing of your personal data.'\n- right: Withdrawal of consent\n  text: 'Withdrawal of consent: Withdraw consent for analytics cookies at any time via the cookie banner.'\nsale_or_sharing:\n  stance: prohibited\n  text: Astrocal does not sell your personal data. We do not share your data with third parties for their own marketing\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/astrocal-dev/privacy/astrocal-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Astrocal's own page on 2026-11-09.
synthetic: false
tags:
- Scheduling
- Booking
- Small Business
- Payments
---
