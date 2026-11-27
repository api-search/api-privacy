---
api_specs:
- filename: factori-ai-people-api-openapi.yml
  format: yaml
  label: Factori People API
  slug: factori-ai-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factori-ai/openapi/factori-ai-people-api-openapi.yml
- filename: factori-ai-poi-api-openapi.yml
  format: yaml
  label: Factori Poi API
  slug: factori-ai-poi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factori-ai/openapi/factori-ai-poi-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact Informartion (name, work email, phone number, company, job title)
  - category: identifying
    text: Account Informartion (username, authentication details, organization)
  - category: device
    text: Device and browser information (IP address, device type, OS, browser type)
  - category: behavioral
    text: Usage Data (pages viewed, actions taken, time spent, referral URLs)
  - category: location
    text: Geolocation information (approximate location derived from IP address; product-specific datasets may include geo-level insights)
  - category: identifying
    text: Some Data Products may include pseudonymous identifiers (e.g., hashed email or hashed phone, ecosystem identifiers)
  deletion:
    route: Email privacy@factori.ai with the subject "Privacy Request"
    text: You may request that we delete your personal data, subject to applicable legal exceptions (e.g., fraud prevention, compliance with legal obligations).
  dpa:
    available: true
    text: Where required, this will be addressed in contractual terms (e.g., data processing addendum).
    url: null
  purposes:
  - purpose: Provide and operate services
    text: Create and manage accounts
  - purpose: Security and integrity
    text: Monitor for fraud, abuse, and unauthorized access
  - purpose: Improve services
    text: Develop new features and user experiences
  - purpose: Legal compliance
    text: Comply with applicable laws and regulations
  residency:
  - region: United States and other countries
    text: We may process and store information in the United States and other countries where we or our service providers operate.
  retention:
  - period: null
    scope: General retention
    text: 'We retain information for as long as necessary to: provide the Services comply with legal obligations enforce agreements and policies resolve disputes and maintain records'
  rights:
  - right: Access
    text: 'Right to Access : You may request information about the categories of data we collect, how we process it, and request a copy of the personal data we hold about you.'
  - right: Correction
    text: You may request corrections to inaccurate or outdated personal data.
  - right: Deletion
    text: You may request that we delete your personal data, subject to applicable legal exceptions (e.g., fraud prevention, compliance with legal obligations).
  - right: Portability
    text: In applicable jurisdictions, you may request to receive your data in a structured, commonly used, and machine-readable format
  - right: Object/restrict processing
    text: You may object to the processing of your personal data, or request that we restrict processing in certain circumstances
  - right: Withdraw consent
    text: Where processing is based on your consent, you have the right to withdraw it at any time
  - right: Opt out of sale or sharing
    text: you have the right to opt out of the sale or disclosure of your personal data to third parties
  role:
    text: Depending on the product and data flow, Factori may act as a controller/business or a processor/service provider under applicable privacy laws.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Factori does not sell your personal information in the traditional sense of selling a consumer list. However, certain disclosures of personal information (for example, through cookies/advertising technologies or through making certain data products available) may be considered a “sale” or “sharing” under some state privacy laws.
  subprocessors:
    text: We use third-party vendors to support our operations (e.g., hosting, analytics, customer support tools).
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use appropriate safeguards for cross-border transfers (such as contractual protections).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Factori
provenance_date: '2026-11-09'
provider_name: Factori
provider_slug: factori-ai
slug: factori-ai-privacy-policy
source_date: '2026-11-09'
source_filename: factori-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://factori.ai/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Factori\naid: factori-ai\nurl: https://factori.ai/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Depending on the product and data flow, Factori may act as a controller/business or a processor/service\n    provider under applicable privacy laws.\ndata_categories:\n- category: contact\n  text: Contact Informartion (name, work email, phone number, company, job title)\n- category: identifying\n  text: Account Informartion (username, authentication details, organization)\n- category: device\n  text: Device and browser information (IP address, device type, OS, browser type)\n- category:\
  \ behavioral\n  text: Usage Data (pages viewed, actions taken, time spent, referral URLs)\n- category: location\n  text: Geolocation information (approximate location derived from IP address; product-specific datasets may include\n    geo-level insights)\n- category: identifying\n  text: Some Data Products may include pseudonymous identifiers (e.g., hashed email or hashed phone, ecosystem identifiers)\npurposes:\n- purpose: Provide and operate services\n  text: Create and manage accounts\n- purpose: Security and integrity\n  text: Monitor for fraud, abuse, and unauthorized access\n- purpose: Improve services\n  text: Develop new features and user experiences\n- purpose: Legal compliance\n  text: Comply with applicable laws and regulations\nretention:\n- scope: General retention\n  period: null\n  text: 'We retain information for as long as necessary to: provide the Services comply with legal obligations enforce\n    agreements and policies resolve disputes and maintain records'\nresidency:\n\
  - region: United States and other countries\n  text: We may process and store information in the United States and other countries where we or our service providers\n    operate.\ntransfers:\n- mechanism: other\n  text: Where required, we use appropriate safeguards for cross-border transfers (such as contractual protections).\nsubprocessors:\n  url: null\n  text: We use third-party vendors to support our operations (e.g., hosting, analytics, customer support tools).\ndpa:\n  available: true\n  url: null\n  text: Where required, this will be addressed in contractual terms (e.g., data processing addendum).\ndeletion:\n  route: Email privacy@factori.ai with the subject \"Privacy Request\"\n  text: You may request that we delete your personal data, subject to applicable legal exceptions (e.g., fraud prevention,\n    compliance with legal obligations).\nrights:\n- right: Access\n  text: 'Right to Access : You may request information about the categories of data we collect, how we process it,\n\
  \    and request a copy of the personal data we hold about you.'\n- right: Correction\n  text: You may request corrections to inaccurate or outdated personal data.\n- right: Deletion\n  text: You may request that we delete your personal data, subject to applicable legal exceptions (e.g., fraud prevention,\n    compliance with legal obligations).\n- right: Portability\n  text: In applicable jurisdictions, you may request to receive your data in a structured, commonly used, and machine-readable\n    format\n- right: Object/restrict processing\n  text: You may object to the processing of your personal data, or request that we restrict processing in certain\n    circumstances\n- right: Withdraw consent\n  text: Where processing is based on your consent, you have the right to withdraw it at any time\n- right: Opt out of sale or sharing\n  text: you have the right to opt out of the sale or disclosure of your personal data to third parties\nsale_or_sharing:\n  stance: conditional\n  text: Factori\
  \ does not sell your personal information in the traditional sense of selling a consumer list. However,\n    certain disclosures of personal information (for example, through cookies/advertising technologies or through\n    making certain data products available) may be considered a “sale” or “sharing” under some state privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/factori-ai/privacy/factori-ai-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Factori's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Real-World Data
- Forecasting
- Enterprise
- Analytics
---
