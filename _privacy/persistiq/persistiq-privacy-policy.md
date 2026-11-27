---
api_specs:
- filename: persistiq-campaigns-api-openapi.yml
  format: yaml
  label: PersistIQ Campaigns API
  slug: persistiq-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-campaigns-api-openapi.yml
- filename: persistiq-do-not-contact-domains-api-openapi.yml
  format: yaml
  label: PersistIQ Do Not Contact Domains API
  slug: persistiq-do-not-contact-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-do-not-contact-domains-api-openapi.yml
- filename: persistiq-events-api-openapi.yml
  format: yaml
  label: PersistIQ Events API
  slug: persistiq-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-events-api-openapi.yml
- filename: persistiq-lead-fields-api-openapi.yml
  format: yaml
  label: PersistIQ Lead Fields API
  slug: persistiq-lead-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-lead-fields-api-openapi.yml
- filename: persistiq-lead-statuses-api-openapi.yml
  format: yaml
  label: PersistIQ Lead Statuses API
  slug: persistiq-lead-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-lead-statuses-api-openapi.yml
- filename: persistiq-leads-api-openapi.yml
  format: yaml
  label: PersistIQ Leads API
  slug: persistiq-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-leads-api-openapi.yml
- filename: persistiq-users-api-openapi.yml
  format: yaml
  label: PersistIQ Users API
  slug: persistiq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-users-api-openapi.yml
- filename: persistiq-campaign-leads-api-openapi.yml
  format: yaml
  label: PersistIQ Campaign Leads API
  slug: persistiq-campaign-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-campaign-leads-api-openapi.yml
- filename: persistiq-dnc-domains-api-openapi.yml
  format: yaml
  label: PersistIQ DNC Domains API
  slug: persistiq-dnc-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-dnc-domains-api-openapi.yml
- filename: persistiq-replies-api-openapi.yml
  format: yaml
  label: PersistIQ Replies API
  slug: persistiq-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-replies-api-openapi.yml
- filename: persistiq-tags-api-openapi.yml
  format: yaml
  label: PersistIQ Tags API
  slug: persistiq-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-tags-api-openapi.yml
- filename: persistiq-webhook-plugin-api-openapi.yml
  format: yaml
  label: PersistIQ Webhook Plugin API
  slug: persistiq-webhook-plugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-webhook-plugin-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information typically includes your name, email address, and telephone numbers (landline and mobile), company name, and work email address.
  - category: financial
    text: Billing Information is collected and processed by our third-party payment processor “Stripe.”
  - category: device
    text: This information includes the device from which you access the Service, your IP addresses, browser type and language, referring and exit pages and URLs, date and time, amount of time spent on particular pages
  - category: behavioral
    text: what sections of the Website you visit, and similar information concerning your use of the Service.
  deletion:
    route: email to privacy contact
    text: You have the right to access, correct, amend or delete your personal data where it is inaccurate or has been processed in violation of this Privacy Policy.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service and customer support
    text: We use the contact information to provide you with the Service, participation in brief, voluntary surveys, customer support
  - purpose: direct marketing
    text: to contact customers and visitors for the purpose of direct marketing of our current and future services.
  - purpose: improve the Website
    text: In an ongoing effort to improve the Website, we automatically collect certain information regarding the activity of visitors to our Website
  - purpose: remarketing and advertising
    text: This information is used to display targeted ads on or through our Website or on other websites or apps, including on Facebook.
  residency:
  - region: United States
    text: Our servers are located in the U.S..
  retention:
  - period: null
    scope: personal information
    text: We will retain your personal information in a form that identifies you only for as long as it serves the purpose(s) for which it was initially collected as stated in this Privacy Policy, or subsequently authorized.
  rights:
  - right: access
    text: Upon request to [email protected] we will provide you with confirmation as to whether we are processing your personal data, and have the data communicated to you within a reasonable time.
  - right: correct, amend or delete
    text: You have the right to access, correct, amend or delete your personal data where it is inaccurate or has been processed in violation of this Privacy Policy.
  - right: opt out of direct marketing
    text: You may opt out at any time from the use of your personal information for direct marketing purposes
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: PersistIQ complies with the EU-US Privacy Shield Framework and the Swiss-US Privacy Shield Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PersistIQ
provenance_date: '2026-11-10'
provider_name: PersistIQ
provider_slug: persistiq
slug: persistiq-privacy-policy
source_date: '2026-11-10'
source_filename: persistiq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.persistiq.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PersistIQ\naid: persistiq\nurl: https://www.persistiq.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information typically includes your name, email address, and telephone numbers (landline and mobile),\n    company name, and work email address.\n- category: financial\n  text: Billing Information is collected and processed by our third-party payment processor “Stripe.”\n- category: device\n  text: This information includes the device from which you access the Service, your IP addresses, browser type\n    and language,\
  \ referring and exit pages and URLs, date and time, amount of time spent on particular pages\n- category: behavioral\n  text: what sections of the Website you visit, and similar information concerning your use of the Service.\npurposes:\n- purpose: provide the Service and customer support\n  text: We use the contact information to provide you with the Service, participation in brief, voluntary surveys,\n    customer support\n- purpose: direct marketing\n  text: to contact customers and visitors for the purpose of direct marketing of our current and future services.\n- purpose: improve the Website\n  text: In an ongoing effort to improve the Website, we automatically collect certain information regarding the\n    activity of visitors to our Website\n- purpose: remarketing and advertising\n  text: This information is used to display targeted ads on or through our Website or on other websites or apps,\n    including on Facebook.\nretention:\n- scope: personal information\n  period: null\n\
  \  text: We will retain your personal information in a form that identifies you only for as long as it serves the\n    purpose(s) for which it was initially collected as stated in this Privacy Policy, or subsequently authorized.\nresidency:\n- region: United States\n  text: Our servers are located in the U.S..\ntransfers:\n- mechanism: DPF\n  text: PersistIQ complies with the EU-US Privacy Shield Framework and the Swiss-US Privacy Shield Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to privacy contact\n  text: You have the right to access, correct, amend or delete your personal data where it is inaccurate or has\n    been processed in violation of this Privacy Policy.\nrights:\n- right: access\n  text: Upon request to [email protected] we will provide you with confirmation as to whether we are processing\n    your personal data, and have the data communicated to you within a reasonable time.\n- right:\
  \ correct, amend or delete\n  text: You have the right to access, correct, amend or delete your personal data where it is inaccurate or has\n    been processed in violation of this Privacy Policy.\n- right: opt out of direct marketing\n  text: You may opt out at any time from the use of your personal information for direct marketing purposes\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/persistiq/privacy/persistiq-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 15 quoted statements, read from PersistIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Engagement
- Sales
- Outbound
- Email Outreach
- CRM
- Lead Management
- Marketing
- Webhook
- SEP
---
