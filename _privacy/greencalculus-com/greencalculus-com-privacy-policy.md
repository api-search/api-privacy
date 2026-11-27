---
api_specs:
- filename: greencalculus-com-account-api-openapi.yml
  format: yaml
  label: greencalculus-com Account API
  slug: greencalculus-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-account-api-openapi.yml
- filename: greencalculus-com-bulk-api-openapi.yml
  format: yaml
  label: greencalculus-com Bulk API
  slug: greencalculus-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-bulk-api-openapi.yml
- filename: greencalculus-com-calculate-api-openapi.yml
  format: yaml
  label: greencalculus-com Calculate API
  slug: greencalculus-com-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-calculate-api-openapi.yml
- filename: greencalculus-com-discovery-api-openapi.yml
  format: yaml
  label: greencalculus-com Discovery API
  slug: greencalculus-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-discovery-api-openapi.yml
- filename: greencalculus-com-factors-api-openapi.yml
  format: yaml
  label: greencalculus-com Factors API
  slug: greencalculus-com-factors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-factors-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and professional title — to personalise your account experience.
  - category: contact
    text: Business email address — for account creation, authentication, newsletter delivery, and support communications.
  - category: device
    text: 'User-agent string: Browser and operating system information, used solely for rendering compatibility decisions.'
  - category: location
    text: Google uses it to derive an approximate location and does not log or store it.
  deletion:
    route: Contact dpo@greencalculus.com
    text: You may request earlier deletion of any personal data we hold at any time — see Section 7 for your rights and the contact details to use.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account personalisation
    text: to personalise your account experience
  - purpose: security and performance
    text: Legitimate interests — maintaining the security and performance of the platform.
  - purpose: aggregate analytics
    text: 'Umami: legitimate interests (Art. 6(1)(f)) in improving the product through aggregate usage insight.'
  residency:
  - region: EU-West
    text: EU/UK user data does not leave EU-West data centres under normal operating conditions.
  - region: Singapore
    text: Asia-Pacific user data is processed in Singapore-region data centres.
  retention:
  - period: Duration of active account + 2 years after closure
    scope: Account identity data
    text: Duration of active account + 2 years after closure
  - period: Not retained
    scope: Calculator input data
    text: Not retained — processed in memory and discarded immediately
  - period: approximately 30 days when last measured
    scope: Technical log data
    text: The window depends on traffic volume rather than a fixed period; it was approximately 30 days when last measured.
  - period: 3 months
    scope: API usage records
    text: 3 months, set and applied by Cloudflare Analytics Engine
  - period: 14 months
    scope: Google Analytics data
    text: Data is kept for 14 months, the shortest standard setting that covers year-on-year comparison.
  rights:
  - right: Access
    text: You may obtain a copy of all personal data we hold about you
  - right: Erasure
    text: You may request deletion of your personal data where it is no longer necessary for the purpose for which it was collected
  - right: Portability
    text: You may receive your personal data in a structured, commonly used, machine-readable format (JSON or CSV) for transfer to another data controller.
  - right: Objection
    text: You may object to processing based on legitimate interests.
  role:
    text: is the controller of the personal data described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will never sell, rent, or monetise your personal data.
  subprocessors:
    text: We will notify account holders of any material changes to our sub-processor list at least 30 days in advance.
    url: null
  transfers:
  - mechanism: SCC
    text: Safeguarded by Cloudflare’s Data Processing Addendum and Standard Contractual Clauses.
  - mechanism: DPF
    text: Resend’s EU-U.S. Data Privacy Framework certification.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: greencalculus-com
provenance_date: '2026-11-09'
provider_name: greencalculus-com
provider_slug: greencalculus-com
slug: greencalculus-com-privacy-policy
source_date: '2026-11-09'
source_filename: greencalculus-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://greencalculus.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: greencalculus-com\naid: greencalculus-com\nurl: https://greencalculus.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: is the controller of the personal data described here\ndata_categories:\n- category: identifying\n  text: Name and professional title — to personalise your account experience.\n- category: contact\n  text: Business email address — for account creation, authentication, newsletter delivery, and support communications.\n- category: device\n  text: 'User-agent string: Browser and operating system information, used solely for rendering compatibility decisions.'\n- category:\
  \ location\n  text: Google uses it to derive an approximate location and does not log or store it.\npurposes:\n- purpose: account personalisation\n  text: to personalise your account experience\n- purpose: security and performance\n  text: Legitimate interests — maintaining the security and performance of the platform.\n- purpose: aggregate analytics\n  text: 'Umami: legitimate interests (Art. 6(1)(f)) in improving the product through aggregate usage insight.'\nretention:\n- scope: Account identity data\n  period: Duration of active account + 2 years after closure\n  text: Duration of active account + 2 years after closure\n- scope: Calculator input data\n  period: Not retained\n  text: Not retained — processed in memory and discarded immediately\n- scope: Technical log data\n  period: approximately 30 days when last measured\n  text: The window depends on traffic volume rather than a fixed period; it was approximately 30 days when last\n    measured.\n- scope: API usage records\n  period:\
  \ 3 months\n  text: 3 months, set and applied by Cloudflare Analytics Engine\n- scope: Google Analytics data\n  period: 14 months\n  text: Data is kept for 14 months, the shortest standard setting that covers year-on-year comparison.\nresidency:\n- region: EU-West\n  text: EU/UK user data does not leave EU-West data centres under normal operating conditions.\n- region: Singapore\n  text: Asia-Pacific user data is processed in Singapore-region data centres.\ntransfers:\n- mechanism: SCC\n  text: Safeguarded by Cloudflare’s Data Processing Addendum and Standard Contractual Clauses.\n- mechanism: DPF\n  text: Resend’s EU-U.S. Data Privacy Framework certification.\nsubprocessors:\n  url: null\n  text: We will notify account holders of any material changes to our sub-processor list at least 30 days in advance.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact dpo@greencalculus.com\n  text: You may request earlier deletion of any personal data we hold at any time\
  \ — see Section 7 for your rights\n    and the contact details to use.\nrights:\n- right: Access\n  text: You may obtain a copy of all personal data we hold about you\n- right: Erasure\n  text: You may request deletion of your personal data where it is no longer necessary for the purpose for which\n    it was collected\n- right: Portability\n  text: You may receive your personal data in a structured, commonly used, machine-readable format (JSON or CSV)\n    for transfer to another data controller.\n- right: Objection\n  text: You may object to processing based on legitimate interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell, rent, or monetise your personal data.\n"
source_yaml_url: https://artifacts.apis.io/greencalculus-com/privacy/greencalculus-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from greencalculus-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emissions
- Data
- Sustainability
---
