---
api_specs:
- filename: agechecker-net-sessions-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Sessions API
  slug: agechecker-net-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-sessions-api-openapi.yml
- filename: agechecker-net-verification-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Verification API
  slug: agechecker-net-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-verification-api-openapi.yml
- filename: agechecker-net-webhooks-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Webhooks API
  slug: agechecker-net-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information you provide such as your full name, postal address (for billing and/or shipping), e-mail address, and phone number.
  - category: device
    text: Information such as your device identifier, internet protocol (IP) address, browser type, device type, cookies, beacons, pixel tags, mobile ad identifier, and other unique identifiers.
  - category: location
    text: Information that permits us to determine your location, primarily to identify if you are an international user
  - category: demographic
    text: Your date of birth, which we use for age verification purposes.
  - category: identifying
    text: a photograph or scanned image of your government-issued photo ID
  - category: behavioral
    text: Information such as your browsing or search history
  deletion:
    route: email to privacy@agechecker.net
    text: To submit this request, send an email to privacy@agechecker.net
  dpa:
    available: null
    text: We have a data processing agreement in place with our core data partner governing their use of this data.
    url: null
  purposes:
  - purpose: Verification services
    text: securely transmit your personal information to our verification partner to verify your age and identity
  - purpose: Security and fraud prevention
    text: detect, investigate, prevent, or take action regarding possible malicious, deceptive, fraudulent, or illegal activity
  - purpose: Legal obligations
    text: comply with our legal and regulatory obligations
  residency:
  - region: United States
    text: Our Services are operated in the United States.
  retention:
  - period: typically within 30 minutes
    scope: Photo IDs
    text: is deleted from our active systems promptly thereafter (typically within 30 minutes)
  - period: null
    scope: Personal information (name, date of birth, address)
    text: we securely store this information in accordance with our retention policies
  rights:
  - right: Right to know
    text: You have a right to confirm whether we're processing your personal data and to access such personal data, subject to certain exceptions.
  - right: Right to correct
    text: You have a right to request that we correct inaccuracies in your personal information, subject to certain exceptions.
  - right: Right to opt out of profiling
    text: You may have a right to opt out of profiling in furtherance of decisions that produce legal or similarly significant effects.
  role:
    text: we generally act as the Customer's service provider, processor, or similar role
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We will not sell or share User Data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgeChecker.Net
provenance_date: '2026-11-09'
provider_name: AgeChecker.Net
provider_slug: agechecker-net
slug: agechecker-net-privacy-policy
source_date: '2026-11-09'
source_filename: agechecker-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agechecker.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgeChecker.Net\naid: agechecker-net\nurl: https://agechecker.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: processor\n  text: we generally act as the Customer's service provider, processor, or similar role\ndata_categories:\n- category: identifying\n  text: Information you provide such as your full name, postal address (for billing and/or shipping), e-mail address,\n    and phone number.\n- category: device\n  text: Information such as your device identifier, internet protocol (IP) address, browser type, device type, cookies,\n    beacons, pixel tags, mobile ad identifier, and\
  \ other unique identifiers.\n- category: location\n  text: Information that permits us to determine your location, primarily to identify if you are an international\n    user\n- category: demographic\n  text: Your date of birth, which we use for age verification purposes.\n- category: identifying\n  text: a photograph or scanned image of your government-issued photo ID\n- category: behavioral\n  text: Information such as your browsing or search history\npurposes:\n- purpose: Verification services\n  text: securely transmit your personal information to our verification partner to verify your age and identity\n- purpose: Security and fraud prevention\n  text: detect, investigate, prevent, or take action regarding possible malicious, deceptive, fraudulent, or illegal\n    activity\n- purpose: Legal obligations\n  text: comply with our legal and regulatory obligations\nretention:\n- scope: Photo IDs\n  period: typically within 30 minutes\n  text: is deleted from our active systems promptly\
  \ thereafter (typically within 30 minutes)\n- scope: Personal information (name, date of birth, address)\n  period: null\n  text: we securely store this information in accordance with our retention policies\nresidency:\n- region: United States\n  text: Our Services are operated in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We have a data processing agreement in place with our core data partner governing their use of this data.\ndeletion:\n  route: email to privacy@agechecker.net\n  text: To submit this request, send an email to privacy@agechecker.net\nrights:\n- right: Right to know\n  text: You have a right to confirm whether we're processing your personal data and to access such personal data,\n    subject to certain exceptions.\n- right: Right to correct\n  text: You have a right to request that we correct inaccuracies in your personal information, subject to certain\n    exceptions.\n- right: Right to\
  \ opt out of profiling\n  text: You may have a right to opt out of profiling in furtherance of decisions that produce legal or similarly\n    significant effects.\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell or share User Data.\n"
source_yaml_url: https://artifacts.apis.io/agechecker-net/privacy/agechecker-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AgeChecker.Net's own page on 2026-11-09.
synthetic: false
tags:
- Age Verification
- Identity
- Compliance
- Regulatory
- E-Commerce
---
