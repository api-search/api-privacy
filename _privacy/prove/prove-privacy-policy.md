---
api_specs:
- filename: prove-auth-api-openapi.yml
  format: yaml
  label: Prove Auth API
  slug: prove-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-auth-api-openapi.yml
- filename: prove-authentication-api-openapi.yml
  format: yaml
  label: Prove Authentication API
  slug: prove-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-authentication-api-openapi.yml
- filename: prove-domain-api-openapi.yml
  format: yaml
  label: Prove Domain API
  slug: prove-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-domain-api-openapi.yml
- filename: prove-identity-api-openapi.yml
  format: yaml
  label: Prove Identity API
  slug: prove-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-identity-api-openapi.yml
- filename: prove-identity-verification-api-openapi.yml
  format: yaml
  label: Prove Identity Verification API
  slug: prove-identity-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-identity-verification-api-openapi.yml
- filename: prove-pre-fill-api-openapi.yml
  format: yaml
  label: Prove Pre-Fill API
  slug: prove-pre-fill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-pre-fill-api-openapi.yml
- filename: prove-trust-score-api-openapi.yml
  format: yaml
  label: Prove Trust Score API
  slug: prove-trust-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-trust-score-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal and/or business contact information
  - category: contact
    text: A name, address, telephone number, email address, and IP address.
  - category: behavioral
    text: Browsing history, search history, information on a consumer's interaction with a website, application, or advertisement.
  - category: location
    text: Physical location or movements not legally qualified as precise geolocation.
  - category: behavioral
    text: Inferences drawn from other Personal Information
  deletion:
    route: online portal request
    text: To exercise your rights as they relate to Prove’s processing of your personal information, please submit a request through our online portal .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and provide Sites features
    text: Operate, maintain, improve, and provide the features and functionality of our Sites.
  - purpose: Personalized advertising and marketing
    text: Send you personalized and interest-based advertising and marketing
  - purpose: Security and fraud
    text: Detect fraud and abuse
  residency:
  - region: United States
    text: your information may be stored and processed outside of the country or region where it was originally collected including in the United States.
  retention:
  - period: null
    scope: personal information generally
    text: Prove will retain your personal information only for as long as reasonably necessary to fulfill the purposes for which the personal information was collected
  rights:
  - right: access, correction, or update
    text: The right to access, correct, or update your personal information.
  - right: deletion
    text: The right to request deletion of your personal information.
  - right: objection or restriction
    text: The right to object to or restrict the processing of your personal information.
  - right: portability
    text: The right to portability to move, copy, or transfer your personal information easily from one entity to another.
  - right: withdraw consent
    text: The right to withdraw your consent to processing at any time.
  - right: opt-out of selling or sharing
    text: The right to opt-out of the selling or sharing of your personal information.
  role:
    text: Prove is the Controller of the personal information that we collect and process in relation to your use of our Sites.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: To opt out of this activity, you can change your cookie settings by clicking on the Cookie Icon located in the bottom right corner of our website.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Prove complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)
  - mechanism: SCC
    text: The recipient may have signed a contract based on “model contractual clauses” approved by the European Commission, obliging them to protect your personal information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Prove
provenance_date: '2026-11-10'
provider_name: Prove
provider_slug: prove
slug: prove-privacy-policy
source_date: '2026-11-10'
source_filename: prove-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.prove.com/legal/overview
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Prove\naid: prove\nurl: https://www.prove.com/legal/overview\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Prove is the Controller of the personal information that we collect and process in relation to your use\n    of our Sites.\ndata_categories:\n- category: identifying\n  text: Personal and/or business contact information\n- category: contact\n  text: A name, address, telephone number, email address, and IP address.\n- category: behavioral\n  text: Browsing history, search history, information on a consumer's interaction with a website, application, or\n    advertisement.\n\
  - category: location\n  text: Physical location or movements not legally qualified as precise geolocation.\n- category: behavioral\n  text: Inferences drawn from other Personal Information\npurposes:\n- purpose: Operate and provide Sites features\n  text: Operate, maintain, improve, and provide the features and functionality of our Sites.\n- purpose: Personalized advertising and marketing\n  text: Send you personalized and interest-based advertising and marketing\n- purpose: Security and fraud\n  text: Detect fraud and abuse\nretention:\n- scope: personal information generally\n  period: null\n  text: Prove will retain your personal information only for as long as reasonably necessary to fulfill the purposes\n    for which the personal information was collected\nresidency:\n- region: United States\n  text: your information may be stored and processed outside of the country or region where it was originally collected\n    including in the United States.\ntransfers:\n- mechanism: DPF\n \
  \ text: Prove complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)\n- mechanism: SCC\n  text: The recipient may have signed a contract based on “model contractual clauses” approved by the European Commission,\n    obliging them to protect your personal information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: online portal request\n  text: To exercise your rights as they relate to Prove’s processing of your personal information, please submit\n    a request through our online portal .\nrights:\n- right: access, correction, or update\n  text: The right to access, correct, or update your personal information.\n- right: deletion\n  text: The right to request deletion of your personal information.\n- right: objection or restriction\n  text: The right to object to or restrict the processing of your personal information.\n- right: portability\n  text: The right to portability to move, copy, or transfer your personal\
  \ information easily from one entity to\n    another.\n- right: withdraw consent\n  text: The right to withdraw your consent to processing at any time.\n- right: opt-out of selling or sharing\n  text: The right to opt-out of the selling or sharing of your personal information.\nsale_or_sharing:\n  stance: conditional\n  text: To opt out of this activity, you can change your cookie settings by clicking on the Cookie Icon located\n    in the bottom right corner of our website.\n"
source_yaml_url: https://artifacts.apis.io/prove/privacy/prove-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Prove's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- Authentication
- Phone Intelligence
- KYC
- Fraud Prevention
---
