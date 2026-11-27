---
api_specs:
- filename: revenuebase-account-api-openapi.yml
  format: yaml
  label: RevenueBase Account API
  slug: revenuebase-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-account-api-openapi.yml
- filename: revenuebase-email-api-openapi.yml
  format: yaml
  label: RevenueBase Email API
  slug: revenuebase-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-email-api-openapi.yml
- filename: revenuebase-jobs-api-openapi.yml
  format: yaml
  label: RevenueBase Jobs API
  slug: revenuebase-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-jobs-api-openapi.yml
- filename: revenuebase-organization-api-openapi.yml
  format: yaml
  label: RevenueBase Organization API
  slug: revenuebase-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-organization-api-openapi.yml
- filename: revenuebase-health-api-openapi.yml
  format: yaml
  label: RevenueBase Health API
  slug: revenuebase-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-health-api-openapi.yml
- filename: revenuebase-contact-api-openapi.yml
  format: yaml
  label: RevenueBase Contact API
  slug: revenuebase-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-contact-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Your name, business email address, company name, job title, and account credentials, provided when you register or contact us.
  - category: professional
    text: First and last name Job title, department, and seniority level Work email address and email verification status
  - category: financial
    text: Your billing address and payment method details, processed by our payment processor.
  - category: behavioral
    text: Traffic data including pages visited, session duration, approximate location (country/region), device and browser type, and referral source
  - category: communication
    text: Records of emails, support requests, or other messages you send to us.
  deletion:
    route: Email privacy@revenuebase.ai with subject line "Opt-Out Request"
    text: Send an email to privacy@revenuebase.ai with the subject line "Opt-Out Request."
  dpa:
    available: true
    text: Business customers in the EEA or UK who require SCCs or a Data Processing Addendum may request them at privacy@revenuebase.ai.
    url: null
  purposes:
  - purpose: Provide, operate, secure, and improve services
    text: Provide, operate, secure, and improve our Services;
  - purpose: Licensing database to B2B customers
    text: License it to business customers for B2B sales, marketing, recruiting, and related professional activities under our Terms of Service;
  - purpose: Training machine-learning models
    text: Develop and improve our Services, including training and improving our matching, verification, and machine-learning models using aggregated and pseudonymized data;
  residency:
  - region: United States
    text: RevenueBase is based in the United States.
  retention:
  - period: up to three (3) years following account closure
    scope: Account and usage data
    text: We retain account and usage data for as long as your account is active and for up to three (3) years following account closure
  - period: 12 consecutive months
    scope: Database records
    text: Records that cannot be verified after 12 consecutive months are removed from our active database.
  rights:
  - right: Access
    text: Right of access. Request a copy of the personal data we hold about you, including information about the categories of sources it came from.
  - right: Erasure
    text: Right to erasure. Request that we delete your personal data.
  - right: Rectification
    text: Right to rectification. Request that we correct inaccurate or incomplete data.
  - right: Object
    text: Right to object. Object to processing based on our legitimate interests.
  - right: Portability
    text: Right to data portability. Request a machine-readable copy of your personal data.
  - right: Opt out of sale or sharing (California)
    text: Right to opt out of sale or sharing. Request that we stop selling or sharing your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your account or usage information to third parties, and we do not use it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When we transfer personal data from the EEA or UK to the United States, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission (Decision 2021/914)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RevenueBase
provenance_date: '2026-11-10'
provider_name: RevenueBase
provider_slug: revenuebase
slug: revenuebase-privacy-policy
source_date: '2026-11-10'
source_filename: revenuebase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://revenuebase.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RevenueBase\naid: revenuebase\nurl: https://revenuebase.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your name, business email address, company name, job title, and account credentials, provided when you register\n    or contact us.\n- category: professional\n  text: First and last name Job title, department, and seniority level Work email address and email verification\n    status\n- category: financial\n  text: Your billing address and payment method details, processed by our payment processor.\n- category: behavioral\n\
  \  text: Traffic data including pages visited, session duration, approximate location (country/region), device and\n    browser type, and referral source\n- category: communication\n  text: Records of emails, support requests, or other messages you send to us.\npurposes:\n- purpose: Provide, operate, secure, and improve services\n  text: Provide, operate, secure, and improve our Services;\n- purpose: Licensing database to B2B customers\n  text: License it to business customers for B2B sales, marketing, recruiting, and related professional activities\n    under our Terms of Service;\n- purpose: Training machine-learning models\n  text: Develop and improve our Services, including training and improving our matching, verification, and machine-learning\n    models using aggregated and pseudonymized data;\nretention:\n- scope: Account and usage data\n  period: up to three (3) years following account closure\n  text: We retain account and usage data for as long as your account is active and\
  \ for up to three (3) years following\n    account closure\n- scope: Database records\n  period: 12 consecutive months\n  text: Records that cannot be verified after 12 consecutive months are removed from our active database.\nresidency:\n- region: United States\n  text: RevenueBase is based in the United States.\ntransfers:\n- mechanism: SCC\n  text: When we transfer personal data from the EEA or UK to the United States, we rely on Standard Contractual\n    Clauses (SCCs) approved by the European Commission (Decision 2021/914)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Business customers in the EEA or UK who require SCCs or a Data Processing Addendum may request them at privacy@revenuebase.ai.\ndeletion:\n  route: Email privacy@revenuebase.ai with subject line \"Opt-Out Request\"\n  text: Send an email to privacy@revenuebase.ai with the subject line \"Opt-Out Request.\"\nrights:\n- right: Access\n  text: Right of access. Request a copy of\
  \ the personal data we hold about you, including information about the\n    categories of sources it came from.\n- right: Erasure\n  text: Right to erasure. Request that we delete your personal data.\n- right: Rectification\n  text: Right to rectification. Request that we correct inaccurate or incomplete data.\n- right: Object\n  text: Right to object. Object to processing based on our legitimate interests.\n- right: Portability\n  text: Right to data portability. Request a machine-readable copy of your personal data.\n- right: Opt out of sale or sharing (California)\n  text: Right to opt out of sale or sharing. Request that we stop selling or sharing your personal information.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your account or usage information to third parties, and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/revenuebase/privacy/revenuebase-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from RevenueBase's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B Data
- Data Enrichment
- Email Verification
- Contact Data
- Company Data
- Lead Intelligence
- Sales Intelligence
- A2A
---
