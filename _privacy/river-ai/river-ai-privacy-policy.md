---
api_specs:
- filename: river-ai-openapi-generated.yml
  format: yaml
  label: River AI, Inc. API
  slug: river-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/river-ai/openapi/_ae-authored/river-ai-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (e.g., name, email, password, year of birth, country, profile image)
  - category: financial
    text: Payment information when required (payment card numbers are processed by our payment provider and are not stored by us)
  - category: device
    text: Device and connection data (IP, OS, browser, identifiers, crash logs)
  - category: behavioral
    text: Usage data (features used, pages viewed, timestamps, referrers)
  - category: location
    text: Approximate location from IP; precise location only with consent
  - category: communication
    text: Communications and support tickets
  - category: other
    text: Inputs and outputs (e.g., prompts, files, images, audio, video, code, and the resulting outputs, plus content from third-party services necessary to provide Services)
  deletion:
    route: Contact [email protected]
    text: you can ask us to delete data we hold by contacting [email protected]
  dpa:
    available: null
    text: This policy does not apply when we process data on behalf of a business customer — for example on our API or enterprise plan — in which case a Data Processing Addendum would apply.
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide and operate the Services, including authenticating you, processing your prompts, and delivering features
  - purpose: Safety and security
    text: Maintain safety, security, and abuse prevention, including automated and human review where appropriate
  - purpose: Marketing
    text: Send marketing, with consent where required and an unsubscribe option in every message
  - purpose: Research and improvement
    text: Research and improve the Services
  residency:
  - region: United States
    text: Our operations and systems are in the United States.
  retention:
  - period: Up to 30 days
    scope: Account & authentication data
    text: Active account, then up to 30 days
  - period: null
    scope: Conversations, inputs, and uploaded data
    text: After ephemeral processing, we do not store these. You store it on your own device or your own cloud system of choice.
  - period: Up to 7 years (varies by law)
    scope: Payment and tax records
    text: Up to 7 years (varies by law)
  - period: Up to 5 years
    scope: Server, security, and audit logs
    text: Up to 5 years; longer if needed for investigations
  - period: null
    scope: Marketing contacts
    text: Until you unsubscribe, and then up to 30 days
  rights:
  - right: access
    text: You may have the right to access, correct, delete, port, restrict, or object to processing of your personal information
  - right: withdraw consent
    text: to withdraw consent
  - right: complaint
    text: to lodge a complaint with a supervisory authority
  - right: opt out (California)
    text: California residents have rights to access, correct, delete, port, opt out, limit, be free from retaliation, and appeal.
  role:
    text: We are River AI Inc. , a Nevada corporation with business operations in San Francisco, California.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, do not share it for cross-context behavioral advertising, and do not make solely automated decisions about you with legal effect.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on EU adequacy decisions where available and otherwise on the EU Standard Contractual Clauses with the UK International Data Transfer Addendum and the Swiss equivalent
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: River AI, Inc.
provenance_date: '2026-11-10'
provider_name: River AI, Inc.
provider_slug: river-ai
slug: river-ai-privacy-policy
source_date: '2026-11-10'
source_filename: river-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://river.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: River AI, Inc.\naid: river-ai\nurl: https://river.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are River AI Inc. , a Nevada corporation with business operations in San Francisco, California.\ndata_categories:\n- category: identifying\n  text: Account information (e.g., name, email, password, year of birth, country, profile image)\n- category: financial\n  text: Payment information when required (payment card numbers are processed by our payment provider and are not\n    stored by us)\n- category: device\n  text: Device and connection data (IP, OS, browser, identifiers,\
  \ crash logs)\n- category: behavioral\n  text: Usage data (features used, pages viewed, timestamps, referrers)\n- category: location\n  text: Approximate location from IP; precise location only with consent\n- category: communication\n  text: Communications and support tickets\n- category: other\n  text: Inputs and outputs (e.g., prompts, files, images, audio, video, code, and the resulting outputs, plus content\n    from third-party services necessary to provide Services)\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide and operate the Services, including authenticating you, processing your prompts, and delivering\n    features\n- purpose: Safety and security\n  text: Maintain safety, security, and abuse prevention, including automated and human review where appropriate\n- purpose: Marketing\n  text: Send marketing, with consent where required and an unsubscribe option in every message\n- purpose: Research and improvement\n  text: Research and improve the Services\n\
  retention:\n- scope: Account & authentication data\n  period: Up to 30 days\n  text: Active account, then up to 30 days\n- scope: Conversations, inputs, and uploaded data\n  period: null\n  text: After ephemeral processing, we do not store these. You store it on your own device or your own cloud system\n    of choice.\n- scope: Payment and tax records\n  period: Up to 7 years (varies by law)\n  text: Up to 7 years (varies by law)\n- scope: Server, security, and audit logs\n  period: Up to 5 years\n  text: Up to 5 years; longer if needed for investigations\n- scope: Marketing contacts\n  period: null\n  text: Until you unsubscribe, and then up to 30 days\nresidency:\n- region: United States\n  text: Our operations and systems are in the United States.\ntransfers:\n- mechanism: SCC\n  text: we rely on EU adequacy decisions where available and otherwise on the EU Standard Contractual Clauses with\n    the UK International Data Transfer Addendum and the Swiss equivalent\nsubprocessors:\n \
  \ url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: This policy does not apply when we process data on behalf of a business customer — for example on our API\n    or enterprise plan — in which case a Data Processing Addendum would apply.\ndeletion:\n  route: Contact [email protected]\n  text: you can ask us to delete data we hold by contacting [email protected]\nrights:\n- right: access\n  text: You may have the right to access, correct, delete, port, restrict, or object to processing of your personal\n    information\n- right: withdraw consent\n  text: to withdraw consent\n- right: complaint\n  text: to lodge a complaint with a supervisory authority\n- right: opt out (California)\n  text: California residents have rights to access, correct, delete, port, opt out, limit, be free from retaliation,\n    and appeal.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, do not share it for cross-context behavioral advertising, and do not\n\
  \    make solely automated decisions about you with legal effect.\n"
source_yaml_url: https://artifacts.apis.io/river-ai/privacy/river-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from River AI, Inc.'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Data Analytics
- Enterprise
---
