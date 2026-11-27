---
api_specs:
- filename: africacompliancedata-com-countries-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Countries API
  slug: africacompliancedata-com-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-countries-api-openapi.yml
- filename: africacompliancedata-com-holidays-and-business-days-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Holidays and business days API
  slug: africacompliancedata-com-holidays-and-business-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-holidays-and-business-days-api-openapi.yml
- filename: africacompliancedata-com-private-mode-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Private mode API
  slug: africacompliancedata-com-private-mode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-private-mode-api-openapi.yml
- filename: africacompliancedata-com-public-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Public API
  slug: africacompliancedata-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-public-api-openapi.yml
- filename: africacompliancedata-com-tax-data-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Tax data API
  slug: africacompliancedata-com-tax-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-tax-data-api-openapi.yml
- filename: africacompliancedata-com-webhooks-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Webhooks API
  slug: africacompliancedata-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-webhooks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: business contact details (name, job title, organisation, work email address)
  - category: device
    text: IP address, requested URL (including query parameters), time, user agent (browser or client name), referrer, and the country of the connection.
  - category: behavioral
    text: we count, per key hash, which countries the key read each day (and tax data over 7 days)
  - category: financial
    text: your payment details and the tax form needed to pay commissions
  deletion:
    route: Email support or use the API endpoint for webhooks
    text: delete them with DELETE /v1/webhooks/{id} or ask support.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service and check API keys
    text: 'Basis: contract (to give you access) and legitimate interest (to keep the Service available and stop floods of made-up keys).'
  - purpose: Protect the dataset from bulk copying
    text: To protect the dataset from bulk copying, we count, per key hash, which countries the key read each day
  - purpose: Security and running the Service
    text: 'Basis: legitimate interest (security and running the Service).'
  - purpose: Website statistics
    text: Cloudflare Web Analytics counts page views without cookies, without building a profile, and without tracking you across sites.
  - purpose: Change alerts
    text: When the data changes, we fetch the email addresses of active Compliance subscribers from Polar at sending time and send the alert through Resend.
  - purpose: Marketing outreach
    text: We sometimes contact organisations that may need the Service.
  residency:
  - region: United States
    text: We are based in the United States, and our providers process data in the United States and, for Cloudflare, in data centres worldwide.
  retention:
  - period: 8 days after the key's last use
    scope: Daily usage counts
    text: These records are deleted automatically 8 days after the key's last use.
  - period: 3 years after the last message
    scope: Support emails
    text: keep them for 3 years after the last message, or longer if needed for a legal claim or obligation
  - period: null
    scope: Outreach contact details
    text: Other outreach details are deleted 24 months after our last contact if no business relationship follows.
  - period: 90 days after the key's last use
    scope: Pro country pack
    text: Deleted automatically 90 days after the key's last use, or as soon as a key that Polar reports revoked or expired is next used.
  - period: 12 months after the trial's last activity
    scope: Trial key hashes
    text: They are deleted automatically 12 months after the trial's last activity
  rights:
  - right: Access
    text: 'Access: get a copy of the personal data we hold about you.'
  - right: Erasure
    text: 'Erasure: have your data deleted when there is no good reason to keep it.'
  - right: Objection
    text: 'Objection: object to uses based on legitimate interest, and always to direct marketing.'
  - right: Portability
    text: 'Portability: receive data you gave us in a common machine-readable format.'
  - right: Rectification
    text: 'Rectification: have wrong or incomplete data corrected.'
  - right: Restriction
    text: 'Restriction: ask us to limit how we use your data while a question is settled.'
  - right: Human review
    text: 'Human review: ask a person to review an automatic key pause (section 3).'
  role:
    text: We decide why and how the personal data described here is used, so we are its controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it for advertising.
  subprocessors:
    text: Cloudflare Hosting (Workers), storage (KV, Durable Objects), cache, CDN, security, rate limits, request logs, Web Analytics Processor Global network; company in the USA
    url: null
  transfers:
  - mechanism: DPF
    text: the EU-US Data Privacy Framework (and its UK and Swiss extensions) for providers certified under it
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (with the UK addendum) in our providers' data processing terms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: africacompliancedata-com
provenance_date: '2026-11-09'
provider_name: africacompliancedata-com
provider_slug: africacompliancedata-com
slug: africacompliancedata-com-privacy-policy
source_date: '2026-11-09'
source_filename: africacompliancedata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://africacompliancedata.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: africacompliancedata-com\naid: africacompliancedata-com\nurl: https://africacompliancedata.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We decide why and how the personal data described here is used, so we are its controller.\ndata_categories:\n- category: contact\n  text: business contact details (name, job title, organisation, work email address)\n- category: device\n  text: IP address, requested URL (including query parameters), time, user agent (browser or client name), referrer,\n    and the country of the connection.\n- category: behavioral\n  text: we count, per key hash,\
  \ which countries the key read each day (and tax data over 7 days)\n- category: financial\n  text: your payment details and the tax form needed to pay commissions\npurposes:\n- purpose: Provide the Service and check API keys\n  text: 'Basis: contract (to give you access) and legitimate interest (to keep the Service available and stop floods\n    of made-up keys).'\n- purpose: Protect the dataset from bulk copying\n  text: To protect the dataset from bulk copying, we count, per key hash, which countries the key read each day\n- purpose: Security and running the Service\n  text: 'Basis: legitimate interest (security and running the Service).'\n- purpose: Website statistics\n  text: Cloudflare Web Analytics counts page views without cookies, without building a profile, and without tracking\n    you across sites.\n- purpose: Change alerts\n  text: When the data changes, we fetch the email addresses of active Compliance subscribers from Polar at sending\n    time and send the alert through\
  \ Resend.\n- purpose: Marketing outreach\n  text: We sometimes contact organisations that may need the Service.\nretention:\n- scope: Daily usage counts\n  period: 8 days after the key's last use\n  text: These records are deleted automatically 8 days after the key's last use.\n- scope: Support emails\n  period: 3 years after the last message\n  text: keep them for 3 years after the last message, or longer if needed for a legal claim or obligation\n- scope: Outreach contact details\n  period: null\n  text: Other outreach details are deleted 24 months after our last contact if no business relationship follows.\n- scope: Pro country pack\n  period: 90 days after the key's last use\n  text: Deleted automatically 90 days after the key's last use, or as soon as a key that Polar reports revoked or\n    expired is next used.\n- scope: Trial key hashes\n  period: 12 months after the trial's last activity\n  text: They are deleted automatically 12 months after the trial's last activity\nresidency:\n\
  - region: United States\n  text: We are based in the United States, and our providers process data in the United States and, for Cloudflare,\n    in data centres worldwide.\ntransfers:\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework (and its UK and Swiss extensions) for providers certified under it\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses (with the UK addendum) in our providers' data processing\n    terms\nsubprocessors:\n  url: null\n  text: Cloudflare Hosting (Workers), storage (KV, Durable Objects), cache, CDN, security, rate limits, request\n    logs, Web Analytics Processor Global network; company in the USA\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support or use the API endpoint for webhooks\n  text: delete them with DELETE /v1/webhooks/{id} or ask support.\nrights:\n- right: Access\n  text: 'Access: get a copy of the personal data we hold about you.'\n- right: Erasure\n  text: 'Erasure: have\
  \ your data deleted when there is no good reason to keep it.'\n- right: Objection\n  text: 'Objection: object to uses based on legitimate interest, and always to direct marketing.'\n- right: Portability\n  text: 'Portability: receive data you gave us in a common machine-readable format.'\n- right: Rectification\n  text: 'Rectification: have wrong or incomplete data corrected.'\n- right: Restriction\n  text: 'Restriction: ask us to limit how we use your data while a question is settled.'\n- right: Human review\n  text: 'Human review: ask a person to review an automatic key pause (section 3).'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/africacompliancedata-com/privacy/africacompliancedata-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from africacompliancedata-com's own page on 2026-11-09.
synthetic: false
tags:
- Africa
- Compliance
- Tax
- Holidays
- Data
---
