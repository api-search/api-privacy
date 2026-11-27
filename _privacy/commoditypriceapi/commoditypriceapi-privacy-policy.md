---
api_specs:
- filename: commoditypriceapi-commoditypriceapi-api-api-openapi.yml
  format: yaml
  label: CommodityPriceAPI CommodityPriceAPI API
  slug: commoditypriceapi-commoditypriceapi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commoditypriceapi/openapi/commoditypriceapi-commoditypriceapi-api-api-openapi.yml
- filename: commoditypriceapi-rates-api-openapi.yml
  format: yaml
  label: CommodityPriceAPI Rates API
  slug: commoditypriceapi-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commoditypriceapi/openapi/commoditypriceapi-rates-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and password — required to create an account.
  - category: contact
    text: we receive your name, email address, the content of your message and any attachments
  - category: financial
    text: Card details are entered on Stripe-hosted checkout pages and are never transmitted to or stored on our servers.
  - category: location
    text: the originating IP address
  - category: behavioral
    text: Microsoft Clarity records page interactions such as clicks, scrolls and mouse movement
  - category: device
    text: IP address, browser type and version, operating system, internet service provider
  deletion:
    route: Dashboard deletion with 5-digit email confirmation code; account data retained 90 days then permanently deleted
    text: Your account data is retained for 90 days from the deletion request.
  dpa:
    available: null
    text: Any additional data processing terms for an Enterprise engagement, including a data processing agreement where required, are agreed in writing alongside this policy.
    url: null
  purposes:
  - purpose: Run account and API
    text: to run your account and the API, to bill you, to prevent abuse, to support you
  - purpose: Consent-based measurement and advertising
    text: only with your consent — to measure and advertise our service
  - purpose: Security and abuse prevention
    text: to detect abuse such as key sharing or scraping
  residency:
  - region: United States
    text: Your data is therefore processed in the United States and accessed from Pakistan by the people who operate the service
  retention:
  - period: 90 days
    scope: Account data
    text: Account data (email, name, timezone, password hash) While your account is open, then 90 days after deletion (see section 9)
  - period: 6–10 years
    scope: Invoices, payments, refunds and tax records (held by Stripe)
    text: Kept by Stripe for the period required by applicable accounting and tax law, typically 6–10 years
  - period: Up to 12 months
    scope: Server and security logs
    text: Short retention, typically up to 12 months
  - period: Up to 14 months
    scope: Analytics data
    text: Per the provider retention settings, up to 14 months
  rights:
  - right: Access
    text: Access — get a copy of the personal data we hold about you.
  - right: Rectification
    text: Rectification — have inaccurate data corrected or incomplete data completed.
  - right: Erasure
    text: Erasure — have your data deleted where we no longer have a lawful reason to keep it.
  - right: Restriction
    text: Restriction — have processing paused while a dispute about accuracy or lawfulness is resolved.
  - right: Objection
    text: Objection — object to processing based on our legitimate interests, and to direct marketing at any time.
  - right: Portability
    text: Portability — receive the data you gave us in a structured, machine-readable format
  - right: Withdraw consent
    text: Withdraw consent — withdraw analytics, advertising or marketing consent at any time
  - right: Complain
    text: Complain — lodge a complaint with your local data protection supervisory authority.
  - right: Deletion (CCPA)
    text: request deletion of your personal information
  - right: Correction (CCPA)
    text: request correction of inaccurate personal information
  role:
    text: The data controller for the personal data described here is JFreaks Software Solutions LLC, the legal entity behind APIFreaks.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: transfers rely on the European Commission and UK adequacy decisions where they apply
  - mechanism: SCC
    text: or on Standard Contractual Clauses with additional safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CommodityPriceAPI
provenance_date: '2026-11-09'
provider_name: CommodityPriceAPI
provider_slug: commoditypriceapi
slug: commoditypriceapi-privacy-policy
source_date: '2026-11-09'
source_filename: commoditypriceapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://commoditypriceapi.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CommodityPriceAPI\naid: commoditypriceapi\nurl: https://commoditypriceapi.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for the personal data described here is JFreaks Software Solutions LLC, the legal entity\n    behind APIFreaks.\ndata_categories:\n- category: identifying\n  text: Email address and password — required to create an account.\n- category: contact\n  text: we receive your name, email address, the content of your message and any attachments\n- category: financial\n  text: Card details are entered on Stripe-hosted checkout pages and are\
  \ never transmitted to or stored on our servers.\n- category: location\n  text: the originating IP address\n- category: behavioral\n  text: Microsoft Clarity records page interactions such as clicks, scrolls and mouse movement\n- category: device\n  text: IP address, browser type and version, operating system, internet service provider\npurposes:\n- purpose: Run account and API\n  text: to run your account and the API, to bill you, to prevent abuse, to support you\n- purpose: Consent-based measurement and advertising\n  text: only with your consent — to measure and advertise our service\n- purpose: Security and abuse prevention\n  text: to detect abuse such as key sharing or scraping\nretention:\n- scope: Account data\n  period: 90 days\n  text: Account data (email, name, timezone, password hash) While your account is open, then 90 days after deletion\n    (see section 9)\n- scope: Invoices, payments, refunds and tax records (held by Stripe)\n  period: 6–10 years\n  text: Kept by Stripe\
  \ for the period required by applicable accounting and tax law, typically 6–10 years\n- scope: Server and security logs\n  period: Up to 12 months\n  text: Short retention, typically up to 12 months\n- scope: Analytics data\n  period: Up to 14 months\n  text: Per the provider retention settings, up to 14 months\nresidency:\n- region: United States\n  text: Your data is therefore processed in the United States and accessed from Pakistan by the people who operate\n    the service\ntransfers:\n- mechanism: adequacy\n  text: transfers rely on the European Commission and UK adequacy decisions where they apply\n- mechanism: SCC\n  text: or on Standard Contractual Clauses with additional safeguards\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Any additional data processing terms for an Enterprise engagement, including a data processing agreement\n    where required, are agreed in writing alongside this policy.\ndeletion:\n  route: Dashboard deletion\
  \ with 5-digit email confirmation code; account data retained 90 days then permanently\n    deleted\n  text: Your account data is retained for 90 days from the deletion request.\nrights:\n- right: Access\n  text: Access — get a copy of the personal data we hold about you.\n- right: Rectification\n  text: Rectification — have inaccurate data corrected or incomplete data completed.\n- right: Erasure\n  text: Erasure — have your data deleted where we no longer have a lawful reason to keep it.\n- right: Restriction\n  text: Restriction — have processing paused while a dispute about accuracy or lawfulness is resolved.\n- right: Objection\n  text: Objection — object to processing based on our legitimate interests, and to direct marketing at any time.\n- right: Portability\n  text: Portability — receive the data you gave us in a structured, machine-readable format\n- right: Withdraw consent\n  text: Withdraw consent — withdraw analytics, advertising or marketing consent at any time\n- right:\
  \ Complain\n  text: Complain — lodge a complaint with your local data protection supervisory authority.\n- right: Deletion (CCPA)\n  text: request deletion of your personal information\n- right: Correction (CCPA)\n  text: request correction of inaccurate personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/commoditypriceapi/privacy/commoditypriceapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from CommodityPriceAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commodities
- Finance
- Real-Time
---
