---
api_specs:
- filename: curated-for-you-companies-api-openapi.yml
  format: yaml
  label: Curated for You Companies API
  slug: curated-for-you-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-companies-api-openapi.yml
- filename: curated-for-you-curations-api-openapi.yml
  format: yaml
  label: Curated for You Curations API
  slug: curated-for-you-curations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-curations-api-openapi.yml
- filename: curated-for-you-users-api-openapi.yml
  format: yaml
  label: Curated for You Users API
  slug: curated-for-you-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curated-for-you/openapi/curated-for-you-users-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact details, such as your name, email address, postal address and telephone number
  - category: financial
    text: Payment information, such as a credit or debit card number
  - category: identifying
    text: Usernames and passwords
  - category: demographic
    text: Demographic and background information
  - category: communication
    text: Communication preferences
  - category: device
    text: IP addresses
  deletion:
    route: Uninstall triggers app/uninstalled webhook, then shop/redact webhook deletion
    text: All store data is fully deleted within 30 days of the shop/redact webhook.
  dpa:
    available: false
    text: a separate data processing agreement under GDPR Article 28 is not required
    url: null
  purposes:
  - purpose: Respond to requests and inquiries
    text: To respond to your requests, inquiries, comments or concerns
  - purpose: Internal operations and analysis
    text: To administer our services and for internal operations, including troubleshooting, data analysis, testing, statistical and survey purposes
  - purpose: App core functionality (app merchant data)
    text: 'We use the data described above solely to provide the App''s core functionality: syncing AI-curated product collections from Curated For You into your Shopify store''s collections.'
  residency:
  - region: United States (us-central1, Iowa)
    text: All data is stored and processed on Google Cloud Platform (GCP) infrastructure in the us-central1 (Iowa, United States) region.
  retention:
  - period: no more than 24 months after resolution
    scope: Support communications
    text: Support communications are retained for no more than 24 months after resolution.
  - period: within 30 days of the shop/redact webhook
    scope: Store data (app)
    text: All store data is fully deleted within 30 days of the shop/redact webhook.
  - period: one year
    scope: Comment cookies
    text: These cookies will last for one year.
  - period: two days
    scope: Login cookies
    text: Login cookies last for two days, and screen options cookies last for a year.
  rights:
  - right: Access
    text: Access — request a copy of the data we hold about your store
  - right: Correction
    text: Correction — request correction of inaccurate data
  - right: Deletion
    text: Deletion — request deletion of your store's data at any time (uninstalling the App also initiates deletion per Section 8)
  - right: Portability
    text: Portability — request your data in a structured, machine-readable format
  - right: Opt out of marketing
    text: You have the right to ask us not to process your personal data for marketing purposes.
  role:
    text: Curated For You, Inc. acts as an independent data controller for the merchant business data described in this policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioral advertising as defined under the California Consumer Privacy Act (CCPA/CPRA).
  subprocessors:
    text: Google Cloud Platform — compute, storage, and secret management (us-central1 region)
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are protected by Standard Contractual Clauses (SCCs) approved by the European Commission
  - mechanism: DPF
    text: Google LLC holds EU-US Data Privacy Framework certification, which provides an additional transfer mechanism for EEA-to-US transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Curated for You
provenance_date: '2026-11-09'
provider_name: Curated for You
provider_slug: curated-for-you
slug: curated-for-you-privacy-policy
source_date: '2026-11-09'
source_filename: curated-for-you-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.curatedforyou.io/privacy-policy-1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Curated for You\naid: curated-for-you\nurl: https://www.curatedforyou.io/privacy-policy-1\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Curated For You, Inc. acts as an independent data controller for the merchant business data described in\n    this policy\ndata_categories:\n- category: contact\n  text: Contact details, such as your name, email address, postal address and telephone number\n- category: financial\n  text: Payment information, such as a credit or debit card number\n- category: identifying\n  text: Usernames and passwords\n- category: demographic\n  text: Demographic and background\
  \ information\n- category: communication\n  text: Communication preferences\n- category: device\n  text: IP addresses\npurposes:\n- purpose: Respond to requests and inquiries\n  text: To respond to your requests, inquiries, comments or concerns\n- purpose: Internal operations and analysis\n  text: To administer our services and for internal operations, including troubleshooting, data analysis, testing,\n    statistical and survey purposes\n- purpose: App core functionality (app merchant data)\n  text: 'We use the data described above solely to provide the App''s core functionality: syncing AI-curated product\n    collections from Curated For You into your Shopify store''s collections.'\nretention:\n- scope: Support communications\n  period: no more than 24 months after resolution\n  text: Support communications are retained for no more than 24 months after resolution.\n- scope: Store data (app)\n  period: within 30 days of the shop/redact webhook\n  text: All store data is fully deleted\
  \ within 30 days of the shop/redact webhook.\n- scope: Comment cookies\n  period: one year\n  text: These cookies will last for one year.\n- scope: Login cookies\n  period: two days\n  text: Login cookies last for two days, and screen options cookies last for a year.\nresidency:\n- region: United States (us-central1, Iowa)\n  text: All data is stored and processed on Google Cloud Platform (GCP) infrastructure in the us-central1 (Iowa,\n    United States) region.\ntransfers:\n- mechanism: SCC\n  text: These transfers are protected by Standard Contractual Clauses (SCCs) approved by the European Commission\n- mechanism: DPF\n  text: Google LLC holds EU-US Data Privacy Framework certification, which provides an additional transfer mechanism\n    for EEA-to-US transfers.\nsubprocessors:\n  url: null\n  text: Google Cloud Platform — compute, storage, and secret management (us-central1 region)\ndpa:\n  available: false\n  url: null\n  text: a separate data processing agreement under GDPR Article\
  \ 28 is not required\ndeletion:\n  route: Uninstall triggers app/uninstalled webhook, then shop/redact webhook deletion\n  text: All store data is fully deleted within 30 days of the shop/redact webhook.\nrights:\n- right: Access\n  text: Access — request a copy of the data we hold about your store\n- right: Correction\n  text: Correction — request correction of inaccurate data\n- right: Deletion\n  text: Deletion — request deletion of your store's data at any time (uninstalling the App also initiates deletion\n    per Section 8)\n- right: Portability\n  text: Portability — request your data in a structured, machine-readable format\n- right: Opt out of marketing\n  text: You have the right to ask us not to process your personal data for marketing purposes.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioral advertising as defined under\n    the California Consumer Privacy Act (CCPA/CPRA).\n"
source_yaml_url: https://artifacts.apis.io/curated-for-you/privacy/curated-for-you-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Curated for You's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Product Discovery
- Personalization
- Artificial Intelligence
- Curation
- Shopify
- Lifestyle Commerce
---
