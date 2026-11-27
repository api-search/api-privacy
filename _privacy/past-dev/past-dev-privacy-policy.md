---
api_specs:
- filename: past-dev-audiences-api-openapi.yml
  format: yaml
  label: past-dev Audiences API
  slug: past-dev-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-audiences-api-openapi.yml
- filename: past-dev-debugging-api-openapi.yml
  format: yaml
  label: past-dev Debugging API
  slug: past-dev-debugging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-debugging-api-openapi.yml
- filename: past-dev-identities-api-openapi.yml
  format: yaml
  label: past-dev Identities API
  slug: past-dev-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-identities-api-openapi.yml
- filename: past-dev-ingestion-api-openapi.yml
  format: yaml
  label: past-dev Ingestion API
  slug: past-dev-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-ingestion-api-openapi.yml
- filename: past-dev-management-api-openapi.yml
  format: yaml
  label: past-dev Management API
  slug: past-dev-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-management-api-openapi.yml
- filename: past-dev-recall-api-openapi.yml
  format: yaml
  label: past-dev Recall API
  slug: past-dev-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-recall-api-openapi.yml
- filename: past-dev-webhooks-api-openapi.yml
  format: yaml
  label: past-dev Webhooks API
  slug: past-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/past-dev/openapi/past-dev-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Sign-up and sign-in run on WorkOS, our identity provider, which holds your email address, your name if you give it, and your sign-in method.
  - category: financial
    text: Payments run on Stripe, which holds your card and billing address.
  - category: behavioral
    text: 'PostHog sets analytics cookies and records the pages you view, the calls to action you click (such as Get API key), and the source of your first visit: referrer, campaign parameters, landing page and time.'
  - category: device
    text: The site is hosted by Vercel, which processes request logs including IP addresses to serve and protect it.
  - category: other
    text: The Memory API stores the text, timestamp, label, and project for each data point you send, with the identity, audience and metadata that come with it.
  deletion:
    route: API endpoints or email to support
    text: A data point is deleted by the source id you gave it, through /api/v1/data-points, or with the rest of its ingestion through DELETE /api/v1/ingest/{ingestionId}.
  dpa:
    available: true
    text: Transfers of personal data from the EEA, the United Kingdom and Switzerland rely on the safeguards in our data processing agreement.
    url: https://security.revo.ai
  purposes:
  - purpose: provide the service
    text: We use your account details to provide the service you signed up for, under our contract with you.
  - purpose: product analytics, product email and service logs
    text: 'Product analytics in the console, product email, and the logs that protect the service rest on our legitimate interest: we need them to run and improve the service.'
  - purpose: optional site cookies
    text: Optional cookies on the site rest on your consent where the law requires it.
  residency:
  - region: United States
    text: We are based in the United States, and the service is processed there.
  - region: EU
    text: Events go to PostHog's EU servers.
  retention:
  - period: while the organization exists
    scope: account data and memory
    text: Account data and memory are kept while the organization exists.
  - period: 7 days
    scope: backup and recovery copies
    text: copies kept for backup and recovery expire within 7 days.
  - period: as the pricing page lists for your plan
    scope: API request log
    text: We keep each API call in the request log for as long as the pricing page lists for your plan.
  - period: one year
    scope: consent choice cookie
    text: records your choice in the consent banner for one year.
  rights:
  - right: access, correction, deletion, copy, restriction, objection, withdrawal of consent
    text: Depending on where you live, you can ask to see the personal data we hold about you, to correct or delete it, to receive a copy of it, to restrict or object to how we use it, and to withdraw a consent you gave.
  - right: complaint to data protection authority
    text: If you are in the EEA, the United Kingdom or Switzerland, you can also complain to your data protection authority.
  role:
    text: We are the controller of the data about visitors to this site and about the people who hold an account.
    value: both
  sale_or_sharing:
    stance: conditional
    text: If you are in the United States, you can opt out of what the laws of your state call the sale or sharing of personal information, and of targeted advertising, with either of those controls.
  subprocessors:
    text: The current subprocessor list, the hosting regions, the data processing agreement and our security documents are in our trust center at https://security.revo.ai.
    url: https://security.revo.ai
  transfers:
  - mechanism: other
    text: Transfers of personal data from the EEA, the United Kingdom and Switzerland rely on the safeguards in our data processing agreement.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: past-dev
provenance_date: '2026-11-10'
provider_name: past-dev
provider_slug: past-dev
slug: past-dev-privacy-policy
source_date: '2026-11-10'
source_filename: past-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://past.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: past-dev\naid: past-dev\nurl: https://past.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of the data about visitors to this site and about the people who hold an account.\ndata_categories:\n- category: contact\n  text: Sign-up and sign-in run on WorkOS, our identity provider, which holds your email address, your name if you\n    give it, and your sign-in method.\n- category: financial\n  text: Payments run on Stripe, which holds your card and billing address.\n- category: behavioral\n  text: 'PostHog sets analytics cookies and records the pages you view, the calls\
  \ to action you click (such as Get\n    API key), and the source of your first visit: referrer, campaign parameters, landing page and time.'\n- category: device\n  text: The site is hosted by Vercel, which processes request logs including IP addresses to serve and protect it.\n- category: other\n  text: The Memory API stores the text, timestamp, label, and project for each data point you send, with the identity,\n    audience and metadata that come with it.\npurposes:\n- purpose: provide the service\n  text: We use your account details to provide the service you signed up for, under our contract with you.\n- purpose: product analytics, product email and service logs\n  text: 'Product analytics in the console, product email, and the logs that protect the service rest on our legitimate\n    interest: we need them to run and improve the service.'\n- purpose: optional site cookies\n  text: Optional cookies on the site rest on your consent where the law requires it.\nretention:\n- scope: account\
  \ data and memory\n  period: while the organization exists\n  text: Account data and memory are kept while the organization exists.\n- scope: backup and recovery copies\n  period: 7 days\n  text: copies kept for backup and recovery expire within 7 days.\n- scope: API request log\n  period: as the pricing page lists for your plan\n  text: We keep each API call in the request log for as long as the pricing page lists for your plan.\n- scope: consent choice cookie\n  period: one year\n  text: records your choice in the consent banner for one year.\nresidency:\n- region: United States\n  text: We are based in the United States, and the service is processed there.\n- region: EU\n  text: Events go to PostHog's EU servers.\ntransfers:\n- mechanism: other\n  text: Transfers of personal data from the EEA, the United Kingdom and Switzerland rely on the safeguards in our\n    data processing agreement.\nsubprocessors:\n  url: https://security.revo.ai\n  text: The current subprocessor list, the hosting\
  \ regions, the data processing agreement and our security documents\n    are in our trust center at https://security.revo.ai.\ndpa:\n  available: true\n  url: https://security.revo.ai\n  text: Transfers of personal data from the EEA, the United Kingdom and Switzerland rely on the safeguards in our\n    data processing agreement.\ndeletion:\n  route: API endpoints or email to support\n  text: A data point is deleted by the source id you gave it, through /api/v1/data-points, or with the rest of its\n    ingestion through DELETE /api/v1/ingest/{ingestionId}.\nrights:\n- right: access, correction, deletion, copy, restriction, objection, withdrawal of consent\n  text: Depending on where you live, you can ask to see the personal data we hold about you, to correct or delete\n    it, to receive a copy of it, to restrict or object to how we use it, and to withdraw a consent you gave.\n- right: complaint to data protection authority\n  text: If you are in the EEA, the United Kingdom or Switzerland,\
  \ you can also complain to your data protection\n    authority.\nsale_or_sharing:\n  stance: conditional\n  text: If you are in the United States, you can opt out of what the laws of your state call the sale or sharing\n    of personal information, and of targeted advertising, with either of those controls.\n"
source_yaml_url: https://artifacts.apis.io/past-dev/privacy/past-dev-privacy-policy.yml
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
summary_line: 22 quoted statements, read from past-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Platform
- Developers
---
