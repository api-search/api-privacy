---
api_specs:
- filename: curios-collections-api-openapi.yml
  format: yaml
  label: Curios Collections API
  slug: curios-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-collections-api-openapi.yml
- filename: curios-contracts-api-openapi.yml
  format: yaml
  label: Curios Contracts API
  slug: curios-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-contracts-api-openapi.yml
- filename: curios-customers-api-openapi.yml
  format: yaml
  label: Curios Customers API
  slug: curios-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-customers-api-openapi.yml
- filename: curios-listings-api-openapi.yml
  format: yaml
  label: Curios Listings API
  slug: curios-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-listings-api-openapi.yml
- filename: curios-orders-api-openapi.yml
  format: yaml
  label: Curios Orders API
  slug: curios-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-orders-api-openapi.yml
- filename: curios-projects-api-openapi.yml
  format: yaml
  label: Curios Projects API
  slug: curios-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-projects-api-openapi.yml
- filename: curios-tokens-api-openapi.yml
  format: yaml
  label: Curios Tokens API
  slug: curios-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curios/openapi/curios-tokens-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect personally identifying information such as your name, billing address, shipping address (if relevant), email address, and payment/payment instrument information
  - category: device
    text: We collect device and usage data (IP address, browser type, OS, pages viewed, timestamps, referring URLs, analytics, etc.)
  - category: contact
    text: we share your necessary contact details (e.g. name, email, billing address) with that creator only if you have consented or as required to fulfill the purchase
  - category: communication
    text: If you opt in to text messages, we collect your mobile number and a record of your consent, including when you gave it.
  deletion:
    route: email to DPO or account settings, or https://www.curios.com/delete/
    text: To make such a request, please contact us via the email address below or via your account settings.
  dpa:
    available: true
    text: Each such provider must have a Data Processing Addendum (DPA) with Curios to ensure GDPR-level protections.
    url: null
  purposes:
  - purpose: platform operations and analytics
    text: Platform operations, support, debugging, personalization, analytics, and improvements
  - purpose: process purchases and payments
    text: 'To process your purchases and facilitate payments securely (legal basis: contract).'
  - purpose: marketing communications
    text: 'To send marketing communications, recommendations, newsletters, including communications from creators you''ve opted in for (legal basis: consent).'
  - purpose: fraud prevention
    text: 'To detect and prevent fraud, misuse, and to enforce terms (legal basis: legitimate interest or legal obligation).'
  retention:
  - period: 6–10 years
    scope: accounting and tax records
    text: 'Accounting, payment, and tax data: retained for 6–10 years (or per local jurisdiction).'
  - period: at least the statute of limitation period
    scope: transaction and content delivery logs
    text: 'Transaction and content delivery logs: kept for at least the statute of limitation period (e.g. 3–6 years).'
  - period: 12–24 months
    scope: security logs and fraud prevention
    text: 'Security logs / fraud prevention: retained for up to 12–24 months or as necessary.'
  - period: indefinitely
    scope: marketing opt-out suppression
    text: 'Marketing opt-out suppression: indefinitely, but only the minimal required data (e.g. hashed email).'
  rights:
  - right: access
    text: 'Right to Access: Confirm whether we process your data and receive a copy in machine-readable form.'
  - right: rectification
    text: 'Right to Rectification: Correct or complete your data.'
  - right: erasure
    text: 'Right to Erasure / Deletion: Request deletion, subject to legal/contractual exceptions'
  - right: portability
    text: 'Right to Data Portability: Receive a structured export of your personal data'
  - right: withdraw consent
    text: 'Right to Withdraw Consent: Where we rely on consent for processing, you may withdraw at any time (e.g. marketing).'
  - right: lodge a complaint
    text: 'Right to Lodge a Complaint: With your local supervisory authority.'
  role:
    text: Curios acts as a data controller for your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your SMS opt-in data or personal information with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards such as standard contractual clauses (SCCs), binding corporate rules, or other approved transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Curios
provenance_date: '2026-11-09'
provider_name: Curios
provider_slug: curios
slug: curios-privacy-policy
source_date: '2026-11-09'
source_filename: curios-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.curios.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Curios\naid: curios\nurl: https://www.curios.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Curios acts as a data controller for your personal data.\ndata_categories:\n- category: identifying\n  text: we collect personally identifying information such as your name, billing address, shipping address (if relevant),\n    email address, and payment/payment instrument information\n- category: device\n  text: We collect device and usage data (IP address, browser type, OS, pages viewed, timestamps, referring URLs,\n    analytics, etc.)\n- category: contact\n  text: we share your\
  \ necessary contact details (e.g. name, email, billing address) with that creator only if you\n    have consented or as required to fulfill the purchase\n- category: communication\n  text: If you opt in to text messages, we collect your mobile number and a record of your consent, including when\n    you gave it.\npurposes:\n- purpose: platform operations and analytics\n  text: Platform operations, support, debugging, personalization, analytics, and improvements\n- purpose: process purchases and payments\n  text: 'To process your purchases and facilitate payments securely (legal basis: contract).'\n- purpose: marketing communications\n  text: 'To send marketing communications, recommendations, newsletters, including communications from creators\n    you''ve opted in for (legal basis: consent).'\n- purpose: fraud prevention\n  text: 'To detect and prevent fraud, misuse, and to enforce terms (legal basis: legitimate interest or legal obligation).'\nretention:\n- scope: accounting and tax\
  \ records\n  period: 6–10 years\n  text: 'Accounting, payment, and tax data: retained for 6–10 years (or per local jurisdiction).'\n- scope: transaction and content delivery logs\n  period: at least the statute of limitation period\n  text: 'Transaction and content delivery logs: kept for at least the statute of limitation period (e.g. 3–6 years).'\n- scope: security logs and fraud prevention\n  period: 12–24 months\n  text: 'Security logs / fraud prevention: retained for up to 12–24 months or as necessary.'\n- scope: marketing opt-out suppression\n  period: indefinitely\n  text: 'Marketing opt-out suppression: indefinitely, but only the minimal required data (e.g. hashed email).'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards such as standard contractual clauses (SCCs), binding corporate rules, or other\n    approved transfer mechanisms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Each such provider must\
  \ have a Data Processing Addendum (DPA) with Curios to ensure GDPR-level protections.\ndeletion:\n  route: email to DPO or account settings, or https://www.curios.com/delete/\n  text: To make such a request, please contact us via the email address below or via your account settings.\nrights:\n- right: access\n  text: 'Right to Access: Confirm whether we process your data and receive a copy in machine-readable form.'\n- right: rectification\n  text: 'Right to Rectification: Correct or complete your data.'\n- right: erasure\n  text: 'Right to Erasure / Deletion: Request deletion, subject to legal/contractual exceptions'\n- right: portability\n  text: 'Right to Data Portability: Receive a structured export of your personal data'\n- right: withdraw consent\n  text: 'Right to Withdraw Consent: Where we rely on consent for processing, you may withdraw at any time (e.g.\n    marketing).'\n- right: lodge a complaint\n  text: 'Right to Lodge a Complaint: With your local supervisory authority.'\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your SMS opt-in data or personal information with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/curios/privacy/curios-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Curios's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Web3
- Creators
---
