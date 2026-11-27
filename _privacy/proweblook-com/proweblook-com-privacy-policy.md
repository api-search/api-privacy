---
api_specs:
- filename: proweblook-com-account-api-openapi.yml
  format: yaml
  label: proweblook-com Account API
  slug: proweblook-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-account-api-openapi.yml
- filename: proweblook-com-ai-audit-api-openapi.yml
  format: yaml
  label: proweblook-com AI Audit API
  slug: proweblook-com-ai-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-ai-audit-api-openapi.yml
- filename: proweblook-com-email-api-openapi.yml
  format: yaml
  label: proweblook-com Email API
  slug: proweblook-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-email-api-openapi.yml
- filename: proweblook-com-ip-api-openapi.yml
  format: yaml
  label: proweblook-com IP API
  slug: proweblook-com-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-ip-api-openapi.yml
- filename: proweblook-com-phone-api-openapi.yml
  format: yaml
  label: proweblook-com Phone API
  slug: proweblook-com-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-phone-api-openapi.yml
- filename: proweblook-com-scraping-api-openapi.yml
  format: yaml
  label: proweblook-com Scraping API
  slug: proweblook-com-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-scraping-api-openapi.yml
- filename: proweblook-com-security-api-openapi.yml
  format: yaml
  label: proweblook-com Security API
  slug: proweblook-com-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-security-api-openapi.yml
- filename: proweblook-com-system-api-openapi.yml
  format: yaml
  label: proweblook-com System API
  slug: proweblook-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-system-api-openapi.yml
- filename: proweblook-com-whats-app-api-openapi.yml
  format: yaml
  label: proweblook-com Whats App API
  slug: proweblook-com-whats-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proweblook-com/openapi/proweblook-com-whats-app-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact details: name, email address, telephone number, job title, employer, and location.'
  - category: contact
    text: 'Business contacts: customer lists including names, email addresses, telephone numbers, job titles, employers, and locations.'
  - category: device
    text: 'Other information: website visitor IP addresses, payment data, and additional details for account management.'
  deletion:
    route: Contact support or privacy team; secure deletion or anonymization on valid request
    text: 'Data Deletion: When data is no longer required or upon receiving a valid deletion request, we securely delete or anonymize the data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fulfil requests and provide services
    text: we process the service inputs and files you explicitly provide, selected contact or network values, verification results, account connection records and job progress to fulfill your requests.
  - purpose: Legal compliance and protection
    text: We may disclose data to comply with legal obligations, enforce our agreements, or protect the rights, property, or safety of Proweblook, our customers, or others.
  retention:
  - period: 90 days
    scope: API service logs, AI audit history, closed account records and billing records
    text: API service logs, AI audit history, records of closed accounts and billing records are retained for 90 days.
  - period: seven days
    scope: Plugin uploads, extracted inputs and job results (ChatGPT)
    text: Plugin uploads, extracted inputs and job results expire seven days after the job is created.
  - period: seven days
    scope: Claude verification job inputs, selected files and results
    text: Claude verification job inputs, selected files and results expire after seven days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: proweblook-com
provenance_date: '2026-11-10'
provider_name: proweblook-com
provider_slug: proweblook-com
slug: proweblook-com-privacy-policy
source_date: '2026-11-10'
source_filename: proweblook-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://proweblook.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: proweblook-com\naid: proweblook-com\nurl: https://proweblook.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Contact details: name, email address, telephone number, job title, employer, and location.'\n- category: contact\n  text: 'Business contacts: customer lists including names, email addresses, telephone numbers, job titles, employers,\n    and locations.'\n- category: device\n  text: 'Other information: website visitor IP addresses, payment data, and additional details for account management.'\npurposes:\n- purpose:\
  \ Fulfil requests and provide services\n  text: we process the service inputs and files you explicitly provide, selected contact or network values, verification\n    results, account connection records and job progress to fulfill your requests.\n- purpose: Legal compliance and protection\n  text: We may disclose data to comply with legal obligations, enforce our agreements, or protect the rights, property,\n    or safety of Proweblook, our customers, or others.\nretention:\n- scope: API service logs, AI audit history, closed account records and billing records\n  period: 90 days\n  text: API service logs, AI audit history, records of closed accounts and billing records are retained for 90 days.\n- scope: Plugin uploads, extracted inputs and job results (ChatGPT)\n  period: seven days\n  text: Plugin uploads, extracted inputs and job results expire seven days after the job is created.\n- scope: Claude verification job inputs, selected files and results\n  period: seven days\n  text: Claude\
  \ verification job inputs, selected files and results expire after seven days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support or privacy team; secure deletion or anonymization on valid request\n  text: 'Data Deletion: When data is no longer required or upon receiving a valid deletion request, we securely\n    delete or anonymize the data.'\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/proweblook-com/privacy/proweblook-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from proweblook-com's own page on 2026-11-10.
synthetic: false
tags:
- Verification
- Communications
- Security
- Data
---
