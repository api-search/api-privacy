---
api_specs:
- filename: cherishedbook-com-auth-api-openapi.yml
  format: yaml
  label: Cherished Book Auth API
  slug: cherishedbook-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-auth-api-openapi.yml
- filename: cherishedbook-com-contributions-api-openapi.yml
  format: yaml
  label: Cherished Book Contributions API
  slug: cherishedbook-com-contributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-contributions-api-openapi.yml
- filename: cherishedbook-com-me-api-openapi.yml
  format: yaml
  label: Cherished Book Me API
  slug: cherishedbook-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-me-api-openapi.yml
- filename: cherishedbook-com-memorials-api-openapi.yml
  format: yaml
  label: Cherished Book Memorials API
  slug: cherishedbook-com-memorials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-memorials-api-openapi.yml
- filename: cherishedbook-com-organization-api-openapi.yml
  format: yaml
  label: Cherished Book Organization API
  slug: cherishedbook-com-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-organization-api-openapi.yml
- filename: cherishedbook-com-owners-api-openapi.yml
  format: yaml
  label: Cherished Book Owners API
  slug: cherishedbook-com-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-owners-api-openapi.yml
- filename: cherishedbook-com-ping-api-openapi.yml
  format: yaml
  label: Cherished Book Ping API
  slug: cherishedbook-com-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherishedbook-com/openapi/cherishedbook-com-ping-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'We collect information you provide directly: name, email address, the memorial content you create, and any messages you submit.'
  - category: device
    text: We also collect minimal technical data (IP address, browser type) for security and service reliability.
  - category: location
    text: an approximate location (city and country) derived from that IP using ipinfo.io
  deletion:
    route: delete account from profile settings
    text: You can delete your account at any time from your profile settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the platform
    text: Your data is used to operate the platform, deliver memorial pages to those you authorise, and communicate with you about the service.
  - purpose: abuse prevention for IP addresses
    text: to help memorial owners spot and stop abuse, including spam, impersonation, harassment, or coordinated misuse of public memorials
  residency:
  - region: UK
    text: Hosting infrastructure is GDPR-compliant and UK-based.
  retention:
  - period: as long as the contribution exists
    scope: IP address on a contribution
    text: It is stored against the contribution for as long as the contribution exists; if the contribution is deleted, the IP is deleted with it.
  - period: as long as your account is active
    scope: memorial content
    text: Memorial content is kept for as long as your account is active.
  - period: 28-day cooling-off period
    scope: account deletion
    text: Deletion runs after a 28-day cooling-off period, which you can cancel from the emails we send.
  - period: null
    scope: contact enquiries
    text: We keep your message and our reply only as long as we need to deal with your enquiry and any follow-up, then we remove it.
  rights:
  - right: access, correct, export, delete
    text: You have the right to access, correct, export, and delete your personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data and we do not share it with advertisers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cherished Book
provenance_date: '2026-11-09'
provider_name: Cherished Book
provider_slug: cherishedbook-com
slug: cherishedbook-com-privacy-policy
source_date: '2026-11-09'
source_filename: cherishedbook-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cherishedbook.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cherished Book\naid: cherishedbook-com\nurl: https://www.cherishedbook.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'We collect information you provide directly: name, email address, the memorial content you create, and\n    any messages you submit.'\n- category: device\n  text: We also collect minimal technical data (IP address, browser type) for security and service reliability.\n- category: location\n  text: an approximate location (city and country) derived from that IP using ipinfo.io\npurposes:\n- purpose: operate the\
  \ platform\n  text: Your data is used to operate the platform, deliver memorial pages to those you authorise, and communicate\n    with you about the service.\n- purpose: abuse prevention for IP addresses\n  text: to help memorial owners spot and stop abuse, including spam, impersonation, harassment, or coordinated misuse\n    of public memorials\nretention:\n- scope: IP address on a contribution\n  period: as long as the contribution exists\n  text: It is stored against the contribution for as long as the contribution exists; if the contribution is deleted,\n    the IP is deleted with it.\n- scope: memorial content\n  period: as long as your account is active\n  text: Memorial content is kept for as long as your account is active.\n- scope: account deletion\n  period: 28-day cooling-off period\n  text: Deletion runs after a 28-day cooling-off period, which you can cancel from the emails we send.\n- scope: contact enquiries\n  period: null\n  text: We keep your message and our reply only\
  \ as long as we need to deal with your enquiry and any follow-up,\n    then we remove it.\nresidency:\n- region: UK\n  text: Hosting infrastructure is GDPR-compliant and UK-based.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account from profile settings\n  text: You can delete your account at any time from your profile settings.\nrights:\n- right: access, correct, export, delete\n  text: You have the right to access, correct, export, and delete your personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/cherishedbook-com/privacy/cherishedbook-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Cherished Book's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Memorials
- Online Memorials
- Funeral Services
- Grief Support
- Consumer
- MCP
- AI Agents
---
