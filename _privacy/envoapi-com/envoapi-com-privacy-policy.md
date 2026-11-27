---
api_specs:
- filename: envoapi-com-openapi-generated.yml
  format: yaml
  label: envoapi-com API
  slug: envoapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/envoapi-com/openapi/_ae-authored/envoapi-com-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: name; business email address; business phone number; company name; job title or role; username
  - category: financial
    text: billing name; billing address; tax identification details where required; invoice details; payment method metadata; transaction history
  - category: location
    text: approximate location derived from IP address
  - category: device
    text: IP address; device identifiers; browser type; operating system
  - category: professional
    text: current and past job titles; current and past employers
  - category: communication
    text: message contents; support attachments; call notes; meeting details
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Where required by applicable law or by agreement, our Data Processing Addendum is available at Appendix A of our Terms of Service .
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: create and manage accounts; authenticate users; issue and manage API keys; process API requests
  - purpose: Build and improve Public Professional Data
    text: provide person and company enrichment; normalize public profile URLs; match professionals to companies
  - purpose: Security and abuse prevention
    text: protect accounts and API keys; detect abuse, fraud, and suspicious activity
  - purpose: Marketing communications
    text: send marketing communications where permitted by law
  residency:
  - region: United States
    text: EnvoAPI may process and store Personal Data in countries other than the country where you live, including the United States and other jurisdictions
  retention:
  - period: 30–180 days
    scope: API logs and request metadata
    text: Typically 30–180 days, unless needed longer for security, abuse prevention, debugging, billing, compliance, or legal reasons
  - period: up to seven (7) years
    scope: Billing, tax, and transaction records
    text: As required for tax, accounting, audit, and legal obligations, typically up to seven (7) years
  - period: 7–90 days
    scope: Customer batch files
    text: Typically 7–90 days after processing, unless Customer configures longer retention or support/legal needs require it
  - period: 90 days–2 years
    scope: Security logs
    text: Typically 90 days–2 years, depending on risk, legal needs, and security requirements
  - period: 30–180 days
    scope: Backups
    text: Deleted or overwritten according to backup schedules, typically within 30–180 days, subject to legal holds and technical constraints
  rights:
  - right: access
    text: request access to Personal Data we process about you
  - right: correction
    text: request correction of inaccurate Personal Data
  - right: deletion
    text: request deletion of Personal Data
  - right: opt out of sale, sharing, targeted advertising
    text: opt out of sale, sharing, targeted advertising, or certain profiling
  - right: portability
    text: request a copy or portability of certain Personal Data
  - right: appeal
    text: appeal a denied privacy request where applicable
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Because EnvoAPI provides access to Public Professional Data and Output Data to business Customers for monetary or other valuable consideration, some disclosures of Personal Data through the Services may be considered a “sale” under certain US privacy laws.
  subprocessors:
    text: Our current subprocessor list is available on request at [email protected] .
    url: null
  transfers:
  - mechanism: SCC
    text: We use safeguards such as Standard Contractual Clauses and do not claim Data Privacy Framework participation.
  - mechanism: other
    text: the UK International Data Transfer Addendum, transfer risk assessments, contractual safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: envoapi-com
provenance_date: '2026-11-09'
provider_name: envoapi-com
provider_slug: envoapi-com
slug: envoapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: envoapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://envoapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: envoapi-com\naid: envoapi-com\nurl: https://envoapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name; business email address; business phone number; company name; job title or role; username\n- category: financial\n  text: billing name; billing address; tax identification details where required; invoice details; payment method\n    metadata; transaction history\n- category: location\n  text: approximate location derived from IP address\n- category: device\n  text: IP address; device identifiers; browser type; operating system\n\
  - category: professional\n  text: current and past job titles; current and past employers\n- category: communication\n  text: message contents; support attachments; call notes; meeting details\npurposes:\n- purpose: Provide and operate the Services\n  text: create and manage accounts; authenticate users; issue and manage API keys; process API requests\n- purpose: Build and improve Public Professional Data\n  text: provide person and company enrichment; normalize public profile URLs; match professionals to companies\n- purpose: Security and abuse prevention\n  text: protect accounts and API keys; detect abuse, fraud, and suspicious activity\n- purpose: Marketing communications\n  text: send marketing communications where permitted by law\nretention:\n- scope: API logs and request metadata\n  period: 30–180 days\n  text: Typically 30–180 days, unless needed longer for security, abuse prevention, debugging, billing, compliance,\n    or legal reasons\n- scope: Billing, tax, and transaction\
  \ records\n  period: up to seven (7) years\n  text: As required for tax, accounting, audit, and legal obligations, typically up to seven (7) years\n- scope: Customer batch files\n  period: 7–90 days\n  text: Typically 7–90 days after processing, unless Customer configures longer retention or support/legal needs\n    require it\n- scope: Security logs\n  period: 90 days–2 years\n  text: Typically 90 days–2 years, depending on risk, legal needs, and security requirements\n- scope: Backups\n  period: 30–180 days\n  text: Deleted or overwritten according to backup schedules, typically within 30–180 days, subject to legal holds\n    and technical constraints\nresidency:\n- region: United States\n  text: EnvoAPI may process and store Personal Data in countries other than the country where you live, including\n    the United States and other jurisdictions\ntransfers:\n- mechanism: SCC\n  text: We use safeguards such as Standard Contractual Clauses and do not claim Data Privacy Framework participation.\n\
  - mechanism: other\n  text: the UK International Data Transfer Addendum, transfer risk assessments, contractual safeguards\nsubprocessors:\n  url: null\n  text: Our current subprocessor list is available on request at [email protected] .\ndpa:\n  available: true\n  url: null\n  text: Where required by applicable law or by agreement, our Data Processing Addendum is available at Appendix\n    A of our Terms of Service .\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: request access to Personal Data we process about you\n- right: correction\n  text: request correction of inaccurate Personal Data\n- right: deletion\n  text: request deletion of Personal Data\n- right: opt out of sale, sharing, targeted advertising\n  text: opt out of sale, sharing, targeted advertising, or certain profiling\n- right: portability\n  text: request a copy or portability of certain Personal Data\n- right: appeal\n  text: appeal a denied privacy request where applicable\nsale_or_sharing:\n\
  \  stance: conditional\n  text: Because EnvoAPI provides access to Public Professional Data and Output Data to business Customers for monetary\n    or other valuable consideration, some disclosures of Personal Data through the Services may be considered a\n    “sale” under certain US privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/envoapi-com/privacy/envoapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from envoapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Data Enrichment
- B2B
- LinkedIn
- Email Verification
---
