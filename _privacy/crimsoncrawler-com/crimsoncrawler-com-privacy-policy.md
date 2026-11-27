---
api_specs:
- filename: crimsoncrawler-com-openapi-generated.yml
  format: yaml
  label: crimsoncrawler-com API
  slug: crimsoncrawler-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimsoncrawler-com/openapi/_ae-authored/crimsoncrawler-com-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, a hashed password, and your active sessions.
  - category: device
    text: the browser you used (its self-reported identification string)
  - category: location
    text: Sign-in and sign-out events also record the originating IP address.
  - category: behavioral
    text: which endpoints you called, per-key request counts, and a short buffer of your most recent calls
  - category: communication
    text: Send transactional email about your account and your automations.
  - category: other
    text: enrichment inputs, saved enrichment reports, asset inventories, generated reports, and the ratings you leave on enrichments
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide and operate the service, and keep your saved work available to you.
  - purpose: Security and abuse prevention
    text: Prevent abuse and investigate security incidents.
  - purpose: Analytics and product improvement
    text: Analyze usage patterns and service performance to enhance features and develop new services.
  - purpose: Legal compliance
    text: Comply with legal obligations and respond to lawful requests from authorities.
  residency:
  - region: United States
    text: We operate from the United States.
  retention:
  - period: null
    scope: Recent-request buffers and usage counts
    text: Recent-request buffers and metered usage counts are kept as a limited rolling window and are continuously overwritten as new activity arrives.
  - period: about 30 minutes
    scope: Enricher submitted content
    text: Content you submit to the Enricher is held briefly (about 30 minutes) while the enrichment runs and while you decide whether to save it.
  - period: typically within 90 days
    scope: Off-site backups
    text: Copies may remain in our off-site backups until those backups age out on their normal rotation (typically within 90 days), after which they are deleted.
  rights:
  - right: Access
    text: Right to Know / Access You may request confirmation of whether we process your personal information and access specific pieces of personal information we have collected about you.
  - right: Correction
    text: Right to Correction You may request that we correct inaccurate personal information we maintain about you
  - right: Deletion
    text: Right to Deletion You may request that we delete personal information we have collected from you
  - right: Portability
    text: Right to Data Portability Where applicable and technically feasible, you may request a copy of your personal information in a portable and readily usable format
  - right: Opt out of sale, targeted advertising, profiling
    text: Right to Opt Out of Certain Processing Depending on your state of residence, you may have the right to opt out of
  - right: Appeal
    text: If we deny your request, in whole or in part, you may have the right to appeal that decision.
  role:
    text: It is operated by Def-Logix, Inc., a Texas Corporation, based in San Antonio, Texas, United States.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties for their own marketing purposes.
  subprocessors:
    text: We rely on a few outside services to run the hosted platform. Each handles only the data it needs for its job.
    url: null
  transfers:
  - mechanism: other
    text: Where such transfers are subject to law that requires a safeguard, we rely on an appropriate transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crimsoncrawler-com
provenance_date: '2026-11-09'
provider_name: crimsoncrawler-com
provider_slug: crimsoncrawler-com
slug: crimsoncrawler-com-privacy-policy
source_date: '2026-11-09'
source_filename: crimsoncrawler-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crimsoncrawler.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crimsoncrawler-com\naid: crimsoncrawler-com\nurl: https://crimsoncrawler.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: It is operated by Def-Logix, Inc., a Texas Corporation, based in San Antonio, Texas, United States.\ndata_categories:\n- category: identifying\n  text: Your name, email address, a hashed password, and your active sessions.\n- category: device\n  text: the browser you used (its self-reported identification string)\n- category: location\n  text: Sign-in and sign-out events also record the originating IP address.\n- category: behavioral\n  text: which endpoints you\
  \ called, per-key request counts, and a short buffer of your most recent calls\n- category: communication\n  text: Send transactional email about your account and your automations.\n- category: other\n  text: enrichment inputs, saved enrichment reports, asset inventories, generated reports, and the ratings you leave\n    on enrichments\npurposes:\n- purpose: Provide and operate the service\n  text: Provide and operate the service, and keep your saved work available to you.\n- purpose: Security and abuse prevention\n  text: Prevent abuse and investigate security incidents.\n- purpose: Analytics and product improvement\n  text: Analyze usage patterns and service performance to enhance features and develop new services.\n- purpose: Legal compliance\n  text: Comply with legal obligations and respond to lawful requests from authorities.\nretention:\n- scope: Recent-request buffers and usage counts\n  period: null\n  text: Recent-request buffers and metered usage counts are kept as a limited\
  \ rolling window and are continuously\n    overwritten as new activity arrives.\n- scope: Enricher submitted content\n  period: about 30 minutes\n  text: Content you submit to the Enricher is held briefly (about 30 minutes) while the enrichment runs and while\n    you decide whether to save it.\n- scope: Off-site backups\n  period: typically within 90 days\n  text: Copies may remain in our off-site backups until those backups age out on their normal rotation (typically\n    within 90 days), after which they are deleted.\nresidency:\n- region: United States\n  text: We operate from the United States.\ntransfers:\n- mechanism: other\n  text: Where such transfers are subject to law that requires a safeguard, we rely on an appropriate transfer mechanism.\nsubprocessors:\n  url: null\n  text: We rely on a few outside services to run the hosted platform. Each handles only the data it needs for its\n    job.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text:\
  \ null\nrights:\n- right: Access\n  text: Right to Know / Access You may request confirmation of whether we process your personal information and\n    access specific pieces of personal information we have collected about you.\n- right: Correction\n  text: Right to Correction You may request that we correct inaccurate personal information we maintain about you\n- right: Deletion\n  text: Right to Deletion You may request that we delete personal information we have collected from you\n- right: Portability\n  text: Right to Data Portability Where applicable and technically feasible, you may request a copy of your personal\n    information in a portable and readily usable format\n- right: Opt out of sale, targeted advertising, profiling\n  text: Right to Opt Out of Certain Processing Depending on your state of residence, you may have the right to opt\n    out of\n- right: Appeal\n  text: If we deny your request, in whole or in part, you may have the right to appeal that decision.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell your personal data to third parties for their own marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/crimsoncrawler-com/privacy/crimsoncrawler-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from crimsoncrawler-com's own page on 2026-11-09.
synthetic: false
tags:
- CVE
- Threat Intelligence
- Security
- Data API
---
