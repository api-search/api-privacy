---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: contact
    text: Account info (email, company, VAT)
  - category: identifying
    text: One-way hash of the IP address, browser and date
  - category: location
    text: we derive an approximate location (country, region and city) from their IP address
  - category: behavioral
    text: In-app usage events (steps completed, e.g. product created, datasheet uploaded — account and company IDs only, no document content)
  - category: financial
    text: Payment data
  - category: device
    text: IP address, browser type, pages visited via standard web server logs.
  - category: communication
    text: we collect their email address, company name (optional), selected guide category, and language preference
  deletion:
    route: Email info@tracepass.eu with your request
    text: Email info@tracepass.eu with your request. We will verify your identity and respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision and DPP generation
    text: Service provision Contract (Art. 6(1)(b))
  - purpose: Improving onboarding and the product
    text: Improving onboarding and the product Legitimate interest (Art. 6(1)(f))
  - purpose: Learning which channels and content bring sign-ups
    text: Learning which channels and content bring sign-ups
  - purpose: Billing
    text: Payment data Billing Contract (Art. 6(1)(b))
  - purpose: Giving manufacturers aggregate scan statistics
    text: Legitimate interest (Art. 6(1)(f)) in giving manufacturers aggregate scan statistics.
  residency:
  - region: EU
    text: The application and its database are hosted in the EU (Hetzner, Germany), and the website's server functions run in Frankfurt (Vercel).
  - region: Not restricted to EU
    text: Uploaded files and database backups are stored with Cloudflare R2, whose storage location is not restricted to the EU.
  retention:
  - period: 30 days
    scope: Account info
    text: Until you leave; then retrievable for at least 30 days
  - period: 90 days
    scope: Server logs
    text: 'Retention: 90 days.'
  - period: 180 days
    scope: In-app usage events
    text: 180 days
  - period: typically 10 years
    scope: Payment data
    text: Per tax law (typically 10 years)
  rights:
  - right: Access
    text: Access (Art. 15) — request a copy of your data
  - right: Rectification
    text: Rectification (Art. 16) — correct inaccurate data
  - right: Erasure
    text: Erasure (Art. 17) — request deletion of your data
  - right: Restriction
    text: Restriction (Art. 18) — restrict processing of your data
  - right: Portability
    text: Portability (Art. 20) — receive your data in machine-readable format
  - right: Objection
    text: Objection (Art. 21) — object to processing based on legitimate interest
  - right: Withdraw consent
    text: Withdraw consent (Art. 7(3)) — at any time, without affecting prior processing
  role:
    text: TracePass is the data controller for website visitors, account registration and administration data, and billing data. For the product and passport content you publish through the platform (technical specifications, supplier information, supporting documents, etc.), you are the data controller and TracePass acts as a data processor on your behalf
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell, rent, or share your personal data with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Each transfer relies on the EU-US Data Privacy Framework where the recipient is certified under it
  - mechanism: SCC
    text: otherwise on the EU Standard Contractual Clauses in the recipient's data processing agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tracepass-eu
provenance_date: '2026-11-10'
provider_name: tracepass-eu
provider_slug: tracepass-eu
slug: tracepass-eu-privacy-policy
source_date: '2026-11-10'
source_filename: tracepass-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tracepass.eu/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tracepass-eu\naid: tracepass-eu\nurl: https://www.tracepass.eu/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TracePass is the data controller for website visitors, account registration and administration data, and\n    billing data. For the product and passport content you publish through the platform (technical specifications,\n    supplier information, supporting documents, etc.), you are the data controller and TracePass acts as a data\n    processor on your behalf\ndata_categories:\n- category: contact\n  text: Account info (email, company, VAT)\n- category: identifying\n  text: One-way\
  \ hash of the IP address, browser and date\n- category: location\n  text: we derive an approximate location (country, region and city) from their IP address\n- category: behavioral\n  text: In-app usage events (steps completed, e.g. product created, datasheet uploaded — account and company IDs\n    only, no document content)\n- category: financial\n  text: Payment data\n- category: device\n  text: IP address, browser type, pages visited via standard web server logs.\n- category: communication\n  text: we collect their email address, company name (optional), selected guide category, and language preference\npurposes:\n- purpose: Service provision and DPP generation\n  text: Service provision Contract (Art. 6(1)(b))\n- purpose: Improving onboarding and the product\n  text: Improving onboarding and the product Legitimate interest (Art. 6(1)(f))\n- purpose: Learning which channels and content bring sign-ups\n  text: Learning which channels and content bring sign-ups\n- purpose: Billing\n \
  \ text: Payment data Billing Contract (Art. 6(1)(b))\n- purpose: Giving manufacturers aggregate scan statistics\n  text: Legitimate interest (Art. 6(1)(f)) in giving manufacturers aggregate scan statistics.\nretention:\n- scope: Account info\n  period: 30 days\n  text: Until you leave; then retrievable for at least 30 days\n- scope: Server logs\n  period: 90 days\n  text: 'Retention: 90 days.'\n- scope: In-app usage events\n  period: 180 days\n  text: 180 days\n- scope: Payment data\n  period: typically 10 years\n  text: Per tax law (typically 10 years)\nresidency:\n- region: EU\n  text: The application and its database are hosted in the EU (Hetzner, Germany), and the website's server functions\n    run in Frankfurt (Vercel).\n- region: Not restricted to EU\n  text: Uploaded files and database backups are stored with Cloudflare R2, whose storage location is not restricted\n    to the EU.\ntransfers:\n- mechanism: DPF\n  text: Each transfer relies on the EU-US Data Privacy Framework where\
  \ the recipient is certified under it\n- mechanism: SCC\n  text: otherwise on the EU Standard Contractual Clauses in the recipient's data processing agreement\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email info@tracepass.eu with your request\n  text: Email info@tracepass.eu with your request. We will verify your identity and respond within 30 days.\nrights:\n- right: Access\n  text: Access (Art. 15) — request a copy of your data\n- right: Rectification\n  text: Rectification (Art. 16) — correct inaccurate data\n- right: Erasure\n  text: Erasure (Art. 17) — request deletion of your data\n- right: Restriction\n  text: Restriction (Art. 18) — restrict processing of your data\n- right: Portability\n  text: Portability (Art. 20) — receive your data in machine-readable format\n- right: Objection\n  text: Objection (Art. 21) — object to processing based on legitimate interest\n- right: Withdraw consent\n  text: Withdraw\
  \ consent (Art. 7(3)) — at any time, without affecting prior processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell, rent, or share your personal data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/tracepass-eu/privacy/tracepass-eu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from tracepass-eu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Digital Product Passport
- EU-Regulation
- Sustainability
---
